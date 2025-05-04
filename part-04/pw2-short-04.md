# Losgrößen- und 

## Ressourceneinsatzplanung# Operative Produktionsplanung und -steuerung 

![img-0.jpeg](img-0.jpeg)
(vgl. Drexl/Fleischmann/Günther/Stadtler/Tempelmeier (1993), Tempelmeier (2008))# Operative Produktionsplanung und -steuerung 

![img-1.jpeg](img-1.jpeg)
(vgl. Drexl/Fleischmann/Günther/Stadtler/Tempelmeier (1993), Tempelmeier (2008))# Losgrößen- und 

## Ressourceneinsatzplanung bei Werkstattproduktion![img-2.jpeg](img-2.jpeg)
(vgl. Günther/Tempelmeier (2016))![img-3.jpeg](img-3.jpeg)
(vgl. Günther/Tempelmeier (2016))Planungsproblem:
Festlegung der Start- und Endtermine für die einzelnen Arbeitsgänge der Produktionsaufträge (Terminplanung)
$\checkmark$ Betrachtung aller zeitverbrauchenden Vorgänge
$\triangleright$ Produktionsaufträge gemäß Losgrößenplanung, Eilaufträge
$\triangleright$ Produktionsaufträge für B- und C-Produkte
$\triangleright$ Produktionsaufträge zur Auffüllung von Sicherheitsbeständen
$\triangleright$ Transportvorgänge, Rüstzeiten, Mindestabstände

- Ziel: Erzeugung durchführbarer Produktions- bzw. Ressourcenbelegungspläne
Daten:
$\triangleright$ Auftragsnetze (Projekte)![img-4.jpeg](img-4.jpeg)Planungsproblem:
Festlegung der Start- und Endtermine für die einzelnen Arbeitsgänge der Produktionsaufträge (Terminplanung)
$\checkmark$ Betrachtung aller zeitverbrauchenden Vorgänge
$\triangleright$ Produktionsaufträge gemäß Losgrößenplanung, Eilaufträge
$\triangleright$ Produktionsaufträge für B- und C-Produkte
$\triangleright$ Produktionsaufträge zur Auffüllung von Sicherheitsbeständen
$\triangleright$ Transportvorgänge, Rüstzeiten, Mindestabstände

- Ziel: Erzeugung durchführbarer Produktions- bzw. Ressourcenbelegungspläne
Daten:
$\triangleright$ Auftragsnetze (Projekte)
$\triangleright$ frühestmögliche und spätestzulässige Produktionstermine
$\Longrightarrow$ Durchlaufterminierung $\Longrightarrow$ Netzplantechnik# Ressourceneinsatzplanung unter der Annahme unbeschränkter Kapazitäten: 

DurchlaufterminierungDaten:
Projektbeginn/„Heute" $\Longrightarrow$ Zeitpunkt 0
Projektende/spätestzulässiger Abschluss der letzten Bearbeitungsvorgänge
Menge $\mathcal{J}$ der einzuplanenden Arbeitsgänge, $\mathcal{J}=\{1, \ldots, J\}$
Dauer $d_{j}$ der einzelnen Arbeitsgänge
Menge $\mathcal{N}_{j}$ der direkten Nachfolgearbeitsgänge des Arbeitsgangs $j$
Menge $\mathcal{V}_{j}$ der direkten Vorgängerarbeitsgänge des Arbeitsgangs $j$
Mindestabstand $d_{j n}$ zwischen den Arbeitsgängen $j$ und $n$
$\triangleright$ positiver Mindestabstand $=$ z. B. Transportzeit, Reinigungszeit, ...
$\triangleright$ negativer Mindestabstand $=$ „offene Produktweitergabe"# Ressourceneinsatzplanung: Durchlaufterminierung 

## Vorwärtsrechnung

Bestimmung der frühestmöglichen Start- und Endtermine der einzelnen Arbeitsgänge

- frühestmöglicher Anfangszeitpunkt des Arbeitsgangs $j$
$=$ spätester (größter) — frühestmöglicher — Endzeitpunkt der notwendigen Vorgängerarbeitsgänge + evtl. Mindestabstand $\mathrm{FAZ}_{j}=\max _{v \in \mathcal{V}_{j}}\left\{\mathrm{FEZ}_{v}+d_{v j}\right\}$
- frühestmöglicher Endzeitpunkt des Arbeitsgangs $j$
$\mathrm{FEZ}_{j}=\mathrm{FAZ}_{j}+d_{j}$# Ressourceneinsatzplanung: Durchlaufterminierung 

## Rückwärtsrechnung

Bestimmung der spätestzulässigen Start- und Endtermine der einzelnen Arbeitsgänge

- spätestzulässiger Endzeitpunkt des Arbeitsgangs $j$
$=$ frühester (kleinster) — spätestzulässiger — Startzeitpunkt der wartenden Nachfolgerarbeitsgänge - evtl. Mindestabstand $\mathrm{SEZ}_{j}=\min _{n \in \mathcal{N}_{j}}\left\{\mathrm{SAZ}_{n}-d_{j n}\right\}$
- spätestzulässiger Anfangszeitpunkt des Arbeitsgangs $j$
$\mathrm{SAZ}_{j}=\mathrm{SEZ}_{j}-d_{j}$# Pufferzeit 

zeitlicher Einplanungsspielraum, ohne dass der spätestzulässige Termin verschoben werden muss

$$
\mathrm{GP}_{j}=\mathrm{SAZ}_{j}-\mathrm{FAZ}_{j}=\mathrm{SEZ}_{j}-\mathrm{FEZ}_{j}
$$

## kritischer Weg

zeitlich längster Weg durch das Auftragsnetz
$=$ Pfad ohne Pufferzeiten (wenn FEZ $_{J}=\mathrm{SEZ}_{J}$ )Gozintograph
![img-5.jpeg](img-5.jpeg)
(mit Vorgangsdauern in Zeiteinheiten (ZE))![img-6.jpeg](img-6.jpeg)
(vgl. Günther/Tempelmeier (2012))

| Arbeitsgang $j$ | Dauer [ZE] | $\mathrm{FAZ}_{j}$ | $\mathrm{FEZ}_{j}$ | $\mathrm{SAZ}_{j}$ | $\mathrm{SEZ}_{j}$ | $\mathrm{GP}_{j}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| A1 | 5 |  |  |  |  |  |
| A2 | 7 |  |  |  |  |  |
| A3 | 11 |  |  |  |  |  |
| B1 | 8 |  |  |  |  |  |
| B2 | 7 |  |  |  |  |  |
| P1 | 8 |  |  |  |  |  |![img-7.jpeg](img-7.jpeg)
(vgl. Günther/Tempelmeier (2012))

| Arbeitsgang $j$ | Dauer [ZE] | $\mathrm{FAZ}_{j}$ | $\mathrm{FEZ}_{j}$ | $\mathrm{SAZ}_{j}$ | $\mathrm{SEZ}_{j}$ | $\mathrm{GP}_{j}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| A1 | 5 | 0 | 5 | 0 | 5 | 0 |
| A2 | 7 | 5 | 12 | 5 | 12 | 0 |
| A3 | 11 | 12 | 23 | 12 | 23 | 0 |
| B1 | 8 | 0 | 8 | 8 | 16 | 8 |
| B2 | 7 | 8 | 15 | 16 | 23 | 8 |
| P1 | 8 | 23 | 31 | 23 | 31 | 0 |# Ressourcenbelegung bei spätestzulässiger Einplanung 

![img-8.jpeg](img-8.jpeg)Ressourcenbelegung bei spätestzulässiger Einplanung
zeitliche Einplanung der Arbeitsgänge
![img-9.jpeg](img-9.jpeg)Ressourcenbelegung bei spätestzulässiger Einplanung
zeitliche Einplanung der Arbeitsgänge
![img-10.jpeg](img-10.jpeg)Ressourcenbelegung bei frühestmöglicher Einplanung
![img-11.jpeg](img-11.jpeg)Ressourcenbelegung bei unvermeidlicher Verspätung
zeitliche Einplanung der Arbeitsgänge
![img-12.jpeg](img-12.jpeg)![img-13.jpeg](img-13.jpeg)
(vgl. Günther/Tempelmeier (2012))

| Arbeitsgang $j$ | Dauer | $[\mathrm{ZE}]$ | $\mathrm{FAZ}_{j}$ | $\mathrm{FEZ}_{j}$ | $\mathrm{SAZ}_{j}$ | $\mathrm{SEZ}_{j}$ | $\mathrm{GP}_{j}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| A1 | 5 | 0 | 5 | 0 | 5 | 0 |  |
| A2 | 7 | 5 | 12 | 5 | 12 | 0 |  |
| A3 | 11 | 12 | 23 | 12 | 23 | 0 |  |
| B1 | 8 | 0 | 8 | 8 | 16 | 8 |  |
| B2 | 7 | 8 | 15 | 16 | 23 | 8 |  |
| P1 | 8 | 23 | 31 | 23 | 31 | 0 |  |

überlappte Produktion („offene Produktweitergabe"): $d_{\mathrm{A} 3, \mathrm{P} 1}=-2$
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
$100-77$![img-14.jpeg](img-14.jpeg)
(vgl. Günther/Tempelmeier (2012))

| Arbeitsgang $j$ | Dauer | $[\mathrm{ZE}]$ | $\mathrm{FAZ}_{j}$ | $\mathrm{FEZ}_{j}$ | $\mathrm{SAZ}_{j}$ | $\mathrm{SEZ}_{j}$ | $\mathrm{GP}_{j}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| A1 | 5 | 0 | 5 | 0 | 5 | 0 |  |
| A2 | 7 | 5 | 12 | 5 | 12 | 0 |  |
| A3 | 11 | 12 | 23 | 12 | 23 | 0 |  |
| B1 | 8 | 0 | 8 | 6 | 14 | 6 |  |
| B2 | 7 | 8 | 15 | 14 | 21 | 6 |  |
| P1 | 8 | 21 | 29 | 21 | 29 | 0 |  |

überlappte Produktion („offene Produktweitergabe"): $d_{\mathrm{A} 3, \mathrm{P} 1}=-2$
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
$100-81$Ressourcenbelegung bei unvermeidlicher Verspätung
zeitliche Einplanung der Arbeitsgänge
![img-15.jpeg](img-15.jpeg)# Ein heuristisches Vorgehen in der Praxis zur kapazitätsorientierten Ressourceneinsatzplanung „Kapazitätsbelastungsausgleich"# Anpassungsmaßnahmen 

Zeitliche Anpassung: Die Arbeitssysteme laufen länger.
Intensitätsmäßige Anpassung: Die Arbeitssysteme laufen schneller.
Quantitative Anpassung: Es laufen mehr Arbeitssysteme.# Anpassung der Belastungsprofile 

... an die vorhandenen Kapazitäten: Kapazitätsbelastungsausgleich
frühestmögliche Einplanung der Arbeitsgänge
Verschiebung innerhalb der Pufferzeit
evtl. gemeinsame Verschiebung mit vorangehenden und nachfolgenden Arbeitsgängen

Ausweichmaßnahmen# Ressourceneinsatzplanung unter Beachtung knapper Kapazitäten <br> - Ressource-Constraint Project <br> Scheduling Problem (RCPSP)# Beispiel 6 Arbeitsgänge 

![img-16.jpeg](img-16.jpeg)# Beispiel 6 Arbeitsgänge 

![img-17.jpeg](img-17.jpeg)

| Arbeitsgang $j$ | Dauer [ZE] | $\mathrm{FAZ}_{j}$ | $\mathrm{FEZ}_{j}$ | $\mathrm{SAZ}_{j}$ | $\mathrm{SEZ}_{j}$ | $\mathrm{GP}_{j}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| A1 | 3 | 0 | 3 | 6 | 9 | 6 |
| A2 | 9 | 0 | 9 | 0 | 9 | 0 |
| A3 | 4 | 9 | 13 | 9 | 13 | 0 |
| B1 | 7 | 0 | 7 | 1 | 8 | 1 |
| B2 | 6 | 0 | 6 | 2 | 8 | 2 |
| B3 | 5 | 7 | 12 | 8 | 13 | 1 |
| Senke | 0 | 13 | 13 | 13 | 13 | 0 |# Ein Optimierungsmodell für die kapazitätsorientierte Ressourceneinsatzplanung# Modell RCPSP 

Was ist gegeben - Daten:
$d_{j} \quad \ldots \quad$ Dauer des Arbeitsgangs $j$
$\mathcal{V}_{j} \quad \ldots \quad$ Menge der Vorgängerarbeitsgänge zu Arbeitsgang $j$ (die Arbeitsgänge, die bei Start des Arbeitsgangs $j$ fertig sein müssen)
$\mathrm{FEZ}_{j} \ldots \quad \downarrow$
$\mathrm{SEZ}_{j} \ldots \quad$ Daten aus der Durchlaufterminierung
$k_{j r} \quad \ldots \quad$ Kapazitätsbedarf des Arbeitsgangs $j$ bezüglich Ressource $r$
$K_{r} \quad \ldots \quad$ Kapazität der Ressource $r$# Modell RCPSP 

Minimiere: $Z=\sum_{t=\mathrm{FEZ}_{J}}^{\mathrm{SEZ}_{J}} t \cdot x_{J t}$

Wähle den Fertigstellungszeitpunkt des Projekts so früh wie möglich !
u. B. d. R.:
$\sum_{t=\mathrm{FEZ}_{j}}^{\mathrm{SEZ}_{j}} x_{j t}=1$
Jeder Arbeitsgang $j=1, \ldots, J$ hat nur einen Endtermin zwischen dem frühestmöglichen $\left(\mathrm{FEZ}_{j}\right)$ und dem spätestzulässigen $\left(\mathrm{SEZ}_{j}\right)$.
$\sum_{t=\mathrm{FEZ}_{h}}^{\mathrm{SEZ}_{h}} t \cdot x_{h t} \leq \sum_{t=\mathrm{FEZ}_{j}}^{\mathrm{SEZ}_{j}}\left(t-d_{j}\right) \cdot x_{j t}$

Die Vorgängerarbeitsgänge $h \in \mathcal{V}_{j}$ der Arbeitsgänge $j \in \mathcal{J} \backslash\{$ Quelle $\}$ müssen jeweils erledigt sein.
$\sum_{j=1}^{J} k_{j r} \cdot \sum_{q=t}^{t+d_{j}-1} x_{j q} \leq K_{r}$

Die Anzahl zeitlich parallel belegter Ressourceneinheiten darf die Anzahl $K_{r}$ verfügbarer Einheiten der Ressourcen $r=1, \ldots, R$ zu keinem Zeitpunkt $t=1, \ldots, T$ überschreiten.# Beispiel 6 Arbeitsgänge 

![img-18.jpeg](img-18.jpeg)# Kapazitätsorientierte Ressourceneinsatzplanung 

Ressourcenbelegung bei beschränkter Kapazität (optimale Lösung)
![img-19.jpeg](img-19.jpeg)# Kapazitätsorientierte Ressourceneinsatzplanung 

Ressourcenbelegung bei beschränkter Kapazität (optimale Lösung)
![img-20.jpeg](img-20.jpeg)# Kapazitätsorientierte Ressourceneinsatzplanung 

Ressourcenbelegung bei beschränkter Kapazität (optimale Lösung)
![img-21.jpeg](img-21.jpeg)Ressourcenbelegung bei beschränkter Kapazität (optimale Lösung)
![img-22.jpeg](img-22.jpeg)# Operative Produktionsplanung und -steuerung 

![img-23.jpeg](img-23.jpeg)
(vgl. Drexl/Fleischmann/Günther/Stadtler/Tempelmeier (1993), Tempelmeier (2008))# Operative Produktionsplanung und -steuerung 

![img-24.jpeg](img-24.jpeg)
(vgl. Drexl/Fleischmann/Günther/Stadtler/Tempelmeier (1993), Tempelmeier (2008))# Operative Produktionsplanung und -steuerung 

![img-25.jpeg](img-25.jpeg)
(vgl. Drexl/Fleischmann/Günther/Stadtler/Tempelmeier (1993), Tempelmeier (2008))# Feinplanung und Steuerung# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunftszeitpunkt | Liefertermin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

![img-26.jpeg](img-26.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-27.jpeg](img-27.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-28.jpeg](img-28.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-29.jpeg](img-29.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

Ressource
![img-30.jpeg](img-30.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

Ressource
![img-31.jpeg](img-31.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |

Ressource
![img-32.jpeg](img-32.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

Ressource
![img-33.jpeg](img-33.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunftszeitpunkt | Liefertermin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

![img-34.jpeg](img-34.jpeg)# Beispiel 3 Produktionsaufträge 

![img-35.jpeg](img-35.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

Ressource
![img-36.jpeg](img-36.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-37.jpeg](img-37.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-38.jpeg](img-38.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-39.jpeg](img-39.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-40.jpeg](img-40.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-41.jpeg](img-41.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

Ressource
![img-42.jpeg](img-42.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

Ressource
![img-43.jpeg](img-43.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

Ressource
![img-44.jpeg](img-44.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |
| 3 | 3 | 8 | C | 1 | 1 | — |  |  |  |  |  |  |  |  |

Ressource
![img-45.jpeg](img-45.jpeg)# Beispiel 3 Produktionsaufträge 

| Auftrag <br> $i$ | Ankunfts- <br> zeitpunkt | Liefer- <br> termin | $j=1$ |  |  |  | Arbeitsgang ij |  |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ | $r$ | $k_{j r}$ | $d_{j}$ |
| 1 | 0 | 11 | A | 1 | 3 | C | 1 | 2 | — |  |  |  |  |  |  |
| 2 | 1 | 10 | C | 1 | 1 | B | 1 | 3 | C | 1 | 3 | A | 1 | 2 |  |
| 3 | 3 | 8 | C | 1 | 1 |  |  |  |  |  |  |  |  |  |  |

Ressource
![img-46.jpeg](img-46.jpeg)