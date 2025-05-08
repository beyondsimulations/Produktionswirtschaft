# Übung 01


## Aufgabe 1: Zerlegung einer Zeitreihe

Eine traditionsreiche Konditorei aus dem Schwarzwald möchte den Verkauf
ihrer berühmten Schwarzwälder Kirschtorte besser verstehen, um
Zutatenbestellungen und Personalplanung zu optimieren. Die
Verkaufszahlen der letzten zwei Jahre (in Stück pro Monat) sind wie
folgt:

| Monat     | Jahr 1 | Jahr 2 |
|-----------|--------|--------|
| Januar    | 80     | 95     |
| Februar   | 75     | 90     |
| März      | 90     | 105    |
| April     | 110    | 125    |
| Mai       | 130    | 150    |
| Juni      | 150    | 175    |
| Juli      | 160    | 190    |
| August    | 155    | 180    |
| September | 120    | 140    |
| Oktober   | 100    | 115    |
| November  | 85     | 100    |
| Dezember  | 100    | 120    |

**Ihre Aufgaben:**

1.  Stellen Sie die Zeitreihe grafisch dar (eine einfache Skizze auf
    Papier genügt).
2.  Beschreiben Sie die Hauptkomponenten (Trend, Saison, Zyklus,
    irreguläre Schwankungen), die Sie in den Verkaufszahlen vermuten.
    Wie würden Sie diese qualitativ charakterisieren? (z.B. steigender
    Trend, saisonale Spitzen im Sommer und zu Weihnachten).
3.  Skizzieren Sie, wie Sie vorgehen würden, um die Trend- und
    Saisonkomponenten grob zu schätzen, basierend auf den im Skript
    vorgestellten Ideen.

## Aufgabe 2: Prognose ohne Trend

Bäckermeisterin Anna Weber in Freiburg möchte die Nachfrage nach ihren
beliebten Roggenbrötchen für den nächsten Tag vorhersagen, um
Überproduktion oder Engpässe zu vermeiden. Sie hat die Verkaufszahlen
der letzten 10 Tage notiert:

| Tag | Verkaufte Roggenbrötchen ($y_t$) |
|-----|----------------------------------|
| 1   | 120                              |
| 2   | 125                              |
| 3   | 115                              |
| 4   | 122                              |
| 5   | 118                              |
| 6   | 128                              |
| 7   | 123                              |
| 8   | 119                              |
| 9   | 126                              |
| 10  | 124                              |

Frau Weber geht davon aus, dass der Verkauf relativ konstant ist, aber
täglichen Schwankungen unterliegt (d.h. kein klarer Trend, konstantes
Niveau).

**Ihre Aufgaben:**

1.  Berechnen Sie einen gleitenden Durchschnitt der Ordnung $n=3$
    (3-Tage-Linie), um eine Prognose für Tag 11 zu erstellen ($p_{11}$).
    Der Prognosewert für Tag $t+1$ ist der Durchschnittswert zum
    Zeitpunkt $t$.
2.  Wenden Sie die exponentielle Glättung erster Ordnung an, um eine
    Prognose für Tag 11 zu erstellen. Verwenden Sie einen
    Glättungsfaktor $\alpha = 0.2$. Als Startwert für den geglätteten
    Wert zum Zeitpunkt $t=0$ (Prognose für Tag 1, $p_1$) nehmen Sie den
    tatsächlichen Verkauf von Tag 1 ($y_1$).
3.  Welche Prognose erscheint Ihnen intuitiv plausibler? Begründen Sie
    kurz.
4.  Berechnen Sie den Prognosefehler mit der mittleren absoluten
    Abweichung (MAE) für alle 10 Tage.

## Aufgabe 3: Prognose mit Trend

Ein aufstrebender YouTuber hat in den letzten 8 Monaten einen stetigen
Zuwachs an neuen Abonnenten verzeichnet. Er möchte die Entwicklung für
die nächsten zwei Monate prognostizieren, um seine Content-Strategie
anzupassen.

| Monat $t$ | Neue Abonnenten $y_t$ |
|-----------|-----------------------|
| 1         | 500                   |
| 2         | 530                   |
| 3         | 520                   |
| 4         | 580                   |
| 5         | 620                   |
| 6         | 670                   |
| 7         | 640                   |
| 8         | 710                   |

Er möchte die Methode der exponentiellen Glättung mit Trendkorrektur
verwenden, wie sie im Skript vorgestellt wird. Nutzen Sie einen
Glättungsfaktor $\alpha = 0.3$. Das geschätzte Niveau zum Zeitpunkt
$t=0$ ist $\widehat{a}_0 = 480$ und der Trend (Steigung) ist
$\widehat{b}_0 = 25$.

**Ihre Aufgaben:**

1.  Berechnen Sie die initialen Werte $y_0^{(1)}$ und $y_0^{(2)}$.
2.  Berechnen Sie iterativ $y_t^{(1)}$, $y_t^{(2)}$, $\widehat{a}_t$ und
    $\widehat{b}_t$ für die Monate $t=1$ bis $t=8$.
3.  Erstellen Sie eine Prognose für die Anzahl neuer Abonnenten für
    Monat 9 und Monat 10.
4.  Berechnen Sie den Prognosefehler mit der mittleren quadratischen
    Abweichung (MSE) für Monat 7 und Monat 8.
