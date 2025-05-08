# Übung 02


## Aufgabe 1: Prognose mit Trend und Saison

Luigi’s Eisdiele in München hat saisonal stark schwankende
Verkaufszahlen (in hundert Litern Eis). Es gibt vier Quartale pro Jahr.
Luigi hat die Verkaufszahlen der letzten **zwei** Jahre gesammelt:

| Jahr | Quartal | Verkauf (100L) $y_t$ |
|------|---------|----------------------|
| 1    | Q1      | 8                    |
| 1    | Q2      | 20                   |
| 1    | Q3      | 25                   |
| 1    | Q4      | 10                   |
| 2    | Q1      | 10                   |
| 2    | Q2      | 24                   |
| 2    | Q3      | 30                   |
| 2    | Q4      | 12                   |

Luigi hat bereits (vereinfachte) **Saisonindizes** für die vier Quartale
bestimmt:

- Q1: 0.6
- Q2: 1.4
- Q3: 1.7
- Q4: 0.8

Er geht von einem multiplikativen Saisonmodell aus
($Y = T \cdot S \cdot I$).

Ihre Aufgaben:

1.  Bereinigen Sie die Verkaufszahlen, indem Sie jeden Wert durch den
    entsprechenden Saisonindex teilen. Diese Werte $Y_d$ repräsentieren
    die Trend-Komponente (plus Rest).
2.  Auf die bereinigten Daten $Y_d$ wenden Sie nun eine Prognosemethode
    für Trenddaten an. Verwenden Sie hierfür die exponentielle Glättung
    mit Trendkorrektur.
    - Nutzen Sie einen Glättungsfaktor $\alpha = 0.2$.
    - Initialisierungswerte für die bereinigten Daten ($Y_d$) zum
      Zeitpunkt $t=0$:
      - Geschätztes Niveau $\widehat{a}_{d,0} = 13$
      - Geschätzter Trend $\widehat{b}_{d,0} = 0.5$
    - Berechnen Sie zuerst $y_{d,0}^{(1)}$ und $y_{d,0}^{(2)}$ basierend
      auf $\widehat{a}_{d,0}$, $\widehat{b}_{d,0}$ und $\alpha$.
3.  Prognostizieren Sie die bereinigten Werte für die vier Quartale des
    nächsten Jahres (Jahr 3, Q1 bis Q4). Hier ist $t$ der Index des
    letzten Beobachtungspunktes der bereinigten Reihe.
4.  Saisonalisieren Sie diese Prognosen, indem Sie sie mit den
    entsprechenden Saisonindizes multiplizieren, um die finalen
    Verkaufsprognosen zu erhalten.

## Aufgabe 2: Saisonindizes selbst berechnen

Das Unternehmen “Frosty”, das auch die Eisdiele von Luigi beliefert, hat
sich auf die Herstellung und den Verkauf von handgemachtem Eis
spezialisiert. Die Geschäftsführerin hat festgestellt, dass die
Verkaufszahlen (in tausend Euro) stark von der Jahreszeit abhängen. Um
die Produktionsmengen besser planen und Marketingkampagnen gezielter
ausrichten zu können, möchte sie die saisonalen Schwankungen genauer
verstehen. Sie hat die Verkaufsdaten der letzten **drei** Jahre
gesammelt:

| Jahr | Quartal | Verkauf (Tsd. €) $y_t$ |
|------|---------|------------------------|
| 1    | Q1      | 150                    |
| 1    | Q2      | 250                    |
| 1    | Q3      | 350                    |
| 1    | Q4      | 180                    |
| 2    | Q1      | 170                    |
| 2    | Q2      | 280                    |
| 2    | Q3      | 390                    |
| 2    | Q4      | 210                    |
| 3    | Q1      | 190                    |
| 3    | Q2      | 310                    |
| 3    | Q3      | 430                    |
| 3    | Q4      | 240                    |

Die Geschäftsführerin geht von einem multiplikativen Saisonmodell aus
($Y = T \cdot C \cdot S \cdot I$) und möchte die Saisonindizes mit der
“Ratio to Moving Average”-Methode bestimmen. Da es vier Quartale pro
Jahr gibt, wird ein gleitender Durchschnitt der Ordnung 4 verwendet.

Ihre Aufgaben:

1.  Berechnen Sie den zentrierten gleitenden Durchschnitt (ZGD) der
    Ordnung 4 für die Verkaufsdaten.
2.  Bestimmen Sie die Roh-Saisonfaktoren ($si_{tm}$), indem Sie die
    tatsächlichen Verkaufszahlen $y_{tm}$ durch die entsprechenden
    ZGD-Werte teilen.
3.  Berechnen Sie die durchschnittlichen Saisonfaktoren ($s_m$) für
    jedes Quartal, indem Sie die Roh-Saisonfaktoren für das jeweilige
    Quartal über die Jahre mitteln.
4.  Normieren Sie die durchschnittlichen Saisonfaktoren, sodass ihre
    Summe der Anzahl der Saisons (hier 4) entspricht. Diese normierten
    Werte sind die finalen Saisonindizes ($\widehat{s}_m$).

## Aufgabe 3: Holt’s Methode für Trenddaten

Das kleine Startup “Deep Learning” im Herzen von Duisburg hat kürzlich
ein neues KI-Tool für die Analyse von Textdaten auf den Markt gebracht.
Die Kunden sind begeistert, und die Verkaufszahlen steigen stetig. Die
Firma möchte nun die zukünftige Nachfrage besser planen können, um
genügend Mitarbeiter zur Betreuung der Kunden zu haben und gleichzeitig
Überstunden zu vermeiden. Die Firma hat die Verkaufszahlen der letzten 8
Monate sorgfältig dokumentiert:

| Monat (t) | Verkäufe ($y_t$) |
|-----------|------------------|
| 1         | 50               |
| 2         | 52               |
| 3         | 58               |
| 4         | 69               |
| 5         | 70               |
| 6         | 72               |
| 7         | 77               |
| 8         | 83               |

Deep Learning hat sich entschieden, das **Verfahren von Holt** zu
verwenden, um eine Prognose zu erstellen. Dieses Verfahren
berücksichtigt sowohl das aktuelle Niveau der Nachfrage als auch den
Trend.

**Ihre Aufgaben:**

1.  Verwenden Sie das Verfahren von Holt, um die geglätteten Werte für
    das Niveau ($\widehat{a}_t$) und den Trend ($\widehat{b}_t$) für die
    Monate $t=1$ bis $t=8$ zu berechnen.
    - Nutzen Sie die folgenden Glättungsfaktoren:
      - $\alpha = 0.3$ (für das Niveau)
      - $\beta = 0.2$ (für den Trend)
    - Die Initialisierungswerte zum Zeitpunkt $t=0$ sind:
      - Geschätztes Niveau $\widehat{a}_{0} = 48$ Verkäufe
      - Geschätzter Trend $\widehat{b}_{0} = 4$ Verkäufe pro Monat
2.  Erstellen Sie eine Prognose für die Verkaufszahlen der nächsten
    **zwei** Monate (Monat 9 und Monat 10).
3.  Was ist der Unterschied zwischen der Prognose aus der letzten Übung
    und dem Verfahren von Holt?
4.  Würden Sie denken, dass das Verfahren von Holt und Winters besser
    geeignet wäre, um die Verkaufszahlen zu prognostizieren?
