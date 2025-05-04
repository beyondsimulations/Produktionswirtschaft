# Ablaufplanung (,,Scheduling")# Ablaufplanung: Klassifikationsmerkmale 

(©) Univ.-Prof. Dr. Michael Manitz# Ablaufplanung: Klassifikationsmerkmale 

Produktionsprozessstruktur
Auftragszugang
Bearbeitungsprozess
Zielsetzungen# Ablaufplanung: Klassifikationsmerkmale 

Produktionsprozessstruktur
Auftragszugang
Bearbeitungsprozess
Zielsetzungen

Notation von Graham, Lawler, Lenstra und Rinnooy Kan
$\alpha|\beta| \gamma$# Ablaufplanung: Klassifikationsmerkmale 

$\alpha$ Produktionsprozessstruktur
$\beta$ Auftragszugang
$\beta$ Bearbeitungsprozess
$\gamma$ Zielsetzungen

Notation von Graham, Lawler, Lenstra und Rinnooy Kan
$\alpha|\beta| \gamma$# Ablaufplanung: Problemspezifikation 

(0) Univ.-Prof. Dr. Michael Manitz# Ablaufplanung: Problemspezifikation 

## Produktionsprozessstruktur

$>$ eine Maschine (Single-Machine Scheduling)
$>$ mehrere parallele Maschinen (Parallel-Machine Scheduling)
$>$ Reihenproduktion (Flow-Shop Scheduling)
Werkstattproduktion (Job-Shop Scheduling)
$\triangleright$ general job shop
$\triangleright$ re-entrant flow# Ablaufplanung: Problemspezifikation 

## Produktionsprozessstruktur

$>$ eine Maschine (Single-Machine Scheduling)
$>$ mehrere parallele Maschinen (Parallel-Machine Scheduling)
Reihenproduktion (Flow-Shop Scheduling)
Werkstattproduktion (Job-Shop Scheduling)
$\triangleright$ general job shop
$\triangleright$ re-entrant flow
$>$ Open-Shop Scheduling# Ablaufplanung: Problemspezifikation 

## Produktionsprozessstruktur

1 eine Maschine (Single-Machine Scheduling)
Pm mehrere parallele Maschinen (Parallel-Machine Scheduling)
Fm Reihenproduktion (Flow-Shop Scheduling)
Jm Werkstattproduktion (Job-Shop Scheduling)
$\triangleright$ general job shop
$\triangleright$ re-entrant flow
Om Open-Shop Scheduling# Ablaufplanung: Problemspezifikation 

## Auftragseingang

statisch
dynamisch
$\triangleright$ deterministisch
$\triangleright$ stochastisch# Ablaufplanung: Problemspezifikation 

## Auftragseingang

$>$ statisch
> dynamisch
$\triangleright$ deterministisch
$\triangleright$ stochastisch

## Bearbeitungszeiten

$>$ deterministisch
$>$ stochastisch# Ablaufplanung: Problemspezifikation 

## Zielsetzung

$\rightarrow$ auftragsbezogen
$\triangleright$ Durchlaufzeiten
$\triangleright$ Wartezeiten
$\triangleright$ Lagerdauern
$\triangleright$ Transportzeiten
$\triangleright$ Liefertermine
$\triangleright$ Terminüberschreitungen
$\triangleright$ Terminabweichungen
$\rightarrow$ ressourcenbezogen
$\triangleright$ Kapazitätsauslastung
$\triangleright$ Gesamtbelegungsdauer
$\triangleright$ Rüstzeiten
$\triangleright$ Leerzeiten# Ablaufplanung: Auftragsbezogene Zielgrößen# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$D_{p}=$ Fertigstellungstermin $_{p}-$ Ankunftszeitpunkt $_{p}$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

$$
(p=1, \ldots, P)
$$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

## Gesamtdurchlaufzeit aller Aufträge

$$
D=\sum_{p=1}^{P} \sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
$$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

## Gesamtdurchlaufzeit aller Aufträge

$$
D=\sum_{p=1}^{P} \sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
$$

mittlere Durchlaufzeit aller Aufträge

$$
\bar{D}=\frac{D}{P}
$$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

## Gesamtwartezeit aller Aufträge

$$
W=\sum_{p=1}^{P} \sum_{m=1}^{M} w_{p m}
$$

mittlere Wartezeit aller Aufträge

$$
\bar{W}=\frac{W}{P}
$$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

$$
(p=1, \ldots, P)
$$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

## Zykluszeit (Makespan)

$$
C=\max _{p}\left\{D_{p}\right\}
$$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

## Zykluszeit (Makespan)

$$
C=\max _{p}\left\{D_{p}\right\}
$$

## Terminabweichung

$$
\Delta_{p}=\left|\text { Fertigstellungstermin }_{p}-\operatorname{Plantermin}_{p}\right|
$$

$$
(p=1, \ldots, P)
$$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

## Zykluszeit (Makespan)

$$
C=\max _{p}\left\{D_{p}\right\}
$$

## Terminüberschreitung (Verspätung, Tardiness)

$$
V_{p}=\max \left\{\text { Fertigstellungstermin }_{p}-\text { Plantermin }_{p}, 0\right\}
$$

$$
(p=1, \ldots, P)
$$# Ablaufplanung: Auftragsbezogene Zielgrößen 

## Durchlaufzeit eines Auftrags $p$

$$
\begin{aligned}
D_{p} & =\text { Fertigstellungstermin }_{p}-\text { Ankunftszeitpunkt }_{p} \\
& =\sum_{m=1}^{M}\left(t_{p m}+w_{p m}+a_{p m}\right)
\end{aligned}
$$

## Zykluszeit (Makespan)

$$
C=\max _{p}\left\{D_{p}\right\}
$$

## Terminüberschreitung (Verspätung, Tardiness)

$$
V_{p}=\max \left\{\text { Fertigstellungstermin }_{p}-\text { Plantermin }_{p}, 0\right\}
$$

## Gesamt-Terminüberschreitung (Summe der Verspätungen)

$$
V=\sum_{p=1}^{P} V_{p}=\sum_{p=1}^{P} \max \left\{\text { Fertigstellungstermin }_{p}-\text { Plantermin }_{p}, 0\right\}
$$# Ablaufplanung: Ressourcenbezogene Zielgrößen# Ablaufplanung: Ressourcenbezogene Zielgrößen 

## Kapazität der Ressourcen

$$
G=\sum_{m=1}^{M} \sum_{p=1}^{P} a_{p m}+\sum_{m=1}^{M} \text { Leerzeit an Maschine } m
$$# Ablaufplanung: Ressourcenbezogene Zielgrößen 

## Kapazität der Ressourcen

$$
G=\sum_{m=1}^{M} \sum_{p=1}^{P} a_{p m}+\sum_{m=1}^{M} \text { Leerzeit an Maschine } m
$$

## produktiv genutzte Zeit

$$
B=\sum_{m=1}^{M} \sum_{p=1}^{P} a_{p m}
$$# Ablaufplanung: Ressourcenbezogene Zielgrößen 

## Kapazität der Ressourcen

$$
G=\sum_{m=1}^{M} \sum_{p=1}^{P} a_{p m}+\sum_{m=1}^{M} \text { Leerzeit an Maschine } m
$$

## produktiv genutzte Zeit

$$
B=\sum_{m=1}^{M} \sum_{p=1}^{P} a_{p m}
$$

## Auslastung

$$
U=\frac{B}{G}
$$# Ablaufplanung: Ressourcenbezogene Zielgrößen 

## Kapazität der Ressourcen

$$
G=\sum_{m=1}^{M} \sum_{p=1}^{P} a_{p m}+\sum_{m=1}^{M} \text { Leerzeit an Maschine } m
$$

## produktiv genutzte Zeit

$$
B=\sum_{m=1}^{M} \sum_{p=1}^{P} a_{p m}
$$

## Auslastung

$$
U=\frac{B}{G}
$$

## Gesamt-Leerzeit

$$
L=\sum_{m=1}^{M} \text { Leerzeit an Maschine } m
$$Ablaufplanung: Übergeordnete Zielgrößen# Ablaufplanung: Übergeordnete Zielgrößen 

Bestand# Ablaufplanung: Übergeordnete Zielgrößen 

Bestand $\Longrightarrow$ Kapitalbindung# Ablaufplanung: Übergeordnete Zielgrößen 

- Bestand $\Longrightarrow$ Kapitalbindung
- termingerechte Auslieferung# Ablaufplanung: Übergeordnete Zielgrößen 

- Bestand $\Longrightarrow$ Kapitalbindung
- termingerechte Auslieferung $\Longrightarrow$ Kundenservice# Ablaufplanung: Übergeordnete Zielgrößen 

- Bestand $\Longrightarrow$ Kapitalbindung
- termingerechte Auslieferung $\Longrightarrow$ Kundenservice
- Auslastung# Ablaufplanung: Übergeordnete Zielgrößen 

- Bestand $\Longrightarrow$ Kapitalbindung
- termingerechte Auslieferung $\Longrightarrow$ Kundenservice
- Auslastung $\Longrightarrow$ Kapazitätsnutzung# Ablaufplanung: Zielbeziehungen 

(©) Univ.-Prof. Dr. Michael Manitz# Littles Gesetz 

mittlerer Bestand = Abgangsrate $\cdot$ mittlere Durchlaufzeit![img-0.jpeg](img-0.jpeg)# Littles Gesetz 

mittlerer Bestand = Abgangsrate $\cdot$ mittlere Durchlaufzeit# Littles Gesetz 

mittlerer Bestand = Abgangsrate $\cdot$ mittlere Durchlaufzeit

## „Dilemma der Ablaufplanung" (Gutenberg)

Bei dynamisch-stochastischem Auftragseingang steigt die Durchlaufzeit (und damit der Bestand, s. Littles Gesetz), wenn die Auslastung maximiert werden soll.# Ablaufplanung für eine Produktionsstufe# Ablaufplanung für nur eine Maschine# Ablaufplanung für eine Maschine 

(©) Univ.-Prof. Dr. Michael ManitzPlanungssituation:
deterministische Bearbeitungszeiten
Notation der Kurzbeschreibung des jeweils betrachteten Spezialproblems:
1|[Anzahl Aufträge]/[Auftragseingang]|[Zielgröße]# 11P Aufträge/statische Situation|mittlere Durchlaufzeit 

## MERsalOR

© Univ.-Prof. Dr. Michael Manitz# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-1.jpeg](img-1.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-2.jpeg](img-2.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-3.jpeg](img-3.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-4.jpeg](img-4.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-5.jpeg](img-5.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-6.jpeg](img-6.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-7.jpeg](img-7.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-8.jpeg](img-8.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-9.jpeg](img-9.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-10.jpeg](img-10.jpeg)# 11P Aufträge/statische Situation|mittlere Durchlaufzeit 

## Beispiel 6 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-11.jpeg](img-11.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-12.jpeg](img-12.jpeg)# 11P Aufträge/statische Situation|mittlere Durchlaufzeit 

## Beispiel 6 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-13.jpeg](img-13.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-14.jpeg](img-14.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-15.jpeg](img-15.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-16.jpeg](img-16.jpeg)Beispiel 6 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-17.jpeg](img-17.jpeg)

Optimalitätsbedingung: $a_{[1]} \leq a_{[2]} \leq a_{[3]} \leq a_{[4]} \leq a_{[5]} \leq a_{[6]}$
$\Longrightarrow$ Kürzeste-Operationszeit-Regel (KOZ-/SPT-Regel)# 1/P Aufträge/statische Situation|maximale Verspätung 

Beispiel 5 Aufträge# 11P Aufträge/statische Situation/maximale Verspätung 

## Beispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-18.jpeg](img-18.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-19.jpeg](img-19.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-20.jpeg](img-20.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-21.jpeg](img-21.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-22.jpeg](img-22.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-23.jpeg](img-23.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-24.jpeg](img-24.jpeg)# 1/P Aufträge/statische Situation/maximale Verspätung 

## Beispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-25.jpeg](img-25.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-26.jpeg](img-26.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-27.jpeg](img-27.jpeg)

Optimalitätsbedingung: $\mathrm{LT}_{[1]} \leq \mathrm{LT}_{[2]} \leq \mathrm{LT}_{[3]} \leq \mathrm{LT}_{[4]} \leq \mathrm{LT}_{[5]}$
$\Longrightarrow$ Liefertermin-Regel# IIP Aufträge/statische Situation \# verspäteter Aufträge 

(©) Univ.-Prof. Dr. Michael Manitz# 11P Aufträge/statische Situation \# verspäteter Aufträge 

## Verfahren von Hodgson (Moore)# 11P Aufträge/statische Situation \# verspäteter Aufträge 

## Verfahren von Hodgson (Moore)

1. Sortiere die Aufträge nach der Lieferterminregel!Speichere die Menge der Aufträge als geordnete Menge $\mathcal{R}$ !# 11P Aufträge/statische Situation \# verspäteter Aufträge 

## Verfahren von Hodgson (Moore)

1. Sortiere die Aufträge nach der Lieferterminregel!Speichere die Menge der Aufträge als geordnete Menge $\mathcal{R}$ !
2. Suche den ersten verspäteten Auftrag, Auftrag $\alpha$, in $\mathcal{R}$ ! Gibt es keinen, gehe zu Schritt 5 !# 11P Aufträge/statische Situation \# verspäteter Aufträge 

## Verfahren von Hodgson (Moore)

1. Sortiere die Aufträge nach der Lieferterminregel!Speichere die Menge der Aufträge als geordnete Menge $\mathcal{R}$ !
2. Suche den ersten verspäteten Auftrag, Auftrag $\alpha$, in $\mathcal{R}$ ! Gibt es keinen, gehe zu Schritt 5!
3. Entferne aus den Aufträgen vor $\alpha$ den Auftrag mit der längsten Bearbeitungsdauer aus der Menge $\mathcal{R}$ !# 11P Aufträge/statische Situation \# verspäteter Aufträge 

## Verfahren von Hodgson (Moore)

1. Sortiere die Aufträge nach der Lieferterminregel!Speichere die Menge der Aufträge als geordnete Menge $\mathcal{R}$ !
2. Suche den ersten verspäteten Auftrag, Auftrag $\alpha$, in $\mathcal{R}$ ! Gibt es keinen, gehe zu Schritt 5!
3. Entferne aus den Aufträgen vor $\alpha$ den Auftrag mit der längsten Bearbeitungsdauer aus der Menge $\mathcal{R}$ ! Dadurch reduziert sich die Verspätung der Aufträge in $\mathcal{R}$ in maximalem Ausmaß.# 11P Aufträge/statische Situation\# verspäteter Aufträge 

## Verfahren von Hodgson (Moore)

1. Sortiere die Aufträge nach der Lieferterminregel!Speichere die Menge der Aufträge als geordnete Menge $\mathcal{R}$ !
2. Suche den ersten verspäteten Auftrag, Auftrag $\alpha$, in $\mathcal{R}$ ! Gibt es keinen, gehe zu Schritt 5!
3. Entferne aus den Aufträgen vor $\alpha$ den Auftrag mit der längsten Bearbeitungsdauer aus der Menge $\mathcal{R}$ ! Dadurch reduziert sich die Verspätung der Aufträge in $\mathcal{R}$ in maximalem Ausmaß.
4. Wiederhole die Schritte 2 und 3, solange es noch Verspätungen in $\mathcal{R}$ gibt!# Verfahren von Hodgson (Moore) 

1. Sortiere die Aufträge nach der Lieferterminregel!Speichere die Menge der Aufträge als geordnete Menge $\mathcal{R}$ !
2. Suche den ersten verspäteten Auftrag, Auftrag $\alpha$, in $\mathcal{R}$ ! Gibt es keinen, gehe zu Schritt 5!
3. Entferne aus den Aufträgen vor $\alpha$ den Auftrag mit der längsten Bearbeitungsdauer aus der Menge $\mathcal{R}$ ! Dadurch reduziert sich die Verspätung der Aufträge in $\mathcal{R}$ in maximalem Ausmaß.
4. Wiederhole die Schritte 2 und 3, solange es noch Verspätungen in $\mathcal{R}$ gibt!
5. Gibt es keinen verspäteten Auftrag mehr in $\mathcal{R}$, dann sortiere die Aufträge nach Lieferterminregel! Die aussortierten Aufträge können in beliebiger Reihenfolge, z. B. nach KOZ-Regel, eingeplant werden.# 11P Aufträge/statische Situation \# verspäteter Aufträge 

## Beispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |Beispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-28.jpeg](img-28.jpeg)

Hodgson-Verfahren, Schritt 1: Einplanung nach Liefertermin-RegelBeispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-29.jpeg](img-29.jpeg)

Hodgson-Verfahren, Schritt 1: Einplanung nach Liefertermin-Regel Hodgson-Verfahren, Schritt 2 und 3: Entfernung von Auftrag A2Beispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-30.jpeg](img-30.jpeg)

Hodgson-Verfahren, Schritt 1: Einplanung nach Liefertermin-Regel Hodgson-Verfahren, Schritt 2 und 3: Entfernung von Auftrag A2 Hodgson-Verfahren, Schritt 5: Einplanung der aussortierten AufträgeBeispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-31.jpeg](img-31.jpeg)

Hodgson-Verfahren, Schritt 1: Einplanung nach Liefertermin-Regel Hodgson-Verfahren, Schritt 2 und 3: Entfernung von Auftrag A2 Hodgson-Verfahren, Schritt 5: Einplanung der aussortierten Aufträge# 1 P Aufträge/dynamisch-deterministische Situation 

$\qquad$# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |# Beispiel 3 Aufträge 

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung:
![img-32.jpeg](img-32.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung:
![img-33.jpeg](img-33.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung:
![img-34.jpeg](img-34.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung:
![img-35.jpeg](img-35.jpeg)# Beispiel 3 Aufträge 

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-36.jpeg](img-36.jpeg)# Beispiel 3 Aufträge 

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-37.jpeg](img-37.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $_{p}$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-38.jpeg](img-38.jpeg)# Beispiel 3 Aufträge 

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-39.jpeg](img-39.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-40.jpeg](img-40.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung:
![img-41.jpeg](img-41.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-42.jpeg](img-42.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-43.jpeg](img-43.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-44.jpeg](img-44.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KRZ-Regel, Verdrängung möglich:
![img-45.jpeg](img-45.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KRZ-Regel, Verdrängung möglich, Wiederholung nötig:
![img-46.jpeg](img-46.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

Erkenntnisse:

- KOZ/KRZ-Regel minimiert die mittlere Durchlaufzeit# 1 P Aufträge/dynamisch-deterministische Situation 

Erkenntnisse:

- KOZ/KRZ-Regel minimiert die mittlere Durchlaufzeit
$\Rightarrow$ Planungszeitpunkt und Menge der einzuplanenden Aufträge beeinflussen die Lösungsgüte# 1 P Aufträge/dynamisch-deterministische Situation 

Erkenntnisse:

- KOZ/KRZ-Regel minimiert die mittlere Durchlaufzeit
$\Rightarrow$ Planungszeitpunkt und Menge der einzuplanenden Aufträge beeinflussen die Lösungsgüte
$\Rightarrow$ hoher Anteil zu früh fertiggestellter Aufträge# 1 P Aufträge/dynamisch-deterministische Situation 

Erkenntnisse:

- KOZ/KRZ-Regel minimiert die mittlere Durchlaufzeit
$\Rightarrow$ Planungszeitpunkt und Menge der einzuplanenden Aufträge beeinflussen die Lösungsgüte
$\Rightarrow$ hoher Anteil zu früh fertiggestellter Aufträge
$\Rightarrow$ Aufträge mit langer Bearbeitungszeit bleiben liegen# 1 P Aufträge/dynamisch-deterministische Situation 

Erkenntnisse:

- KOZ/KRZ-Regel minimiert die mittlere Durchlaufzeit
$\Rightarrow$ Planungszeitpunkt und Menge der einzuplanenden Aufträge beeinflussen die Lösungsgüte
$\Rightarrow$ hoher Anteil zu früh fertiggestellter Aufträge
$\Rightarrow$ Aufträge mit langer Bearbeitungszeit bleiben liegen
$\Rightarrow$ hohe Streuung der Durchlaufzeiten1) $\infty$ Aufträge/dynamisch-stochastische Situation $\mid$ MERSAţORDie Produktionsaufträge treffen in zufälligen Abständen ein.# 1.4.2 Aufträge/dynamisch-stochastische Situation 

Die Produktionsaufträge treffen in zufälligen Abständen ein.
Die Durchlaufzeit eines Auftrags ist eine Zufallsvariable.# 1.4 Aufträge/dynamisch-stochastische Situation 

Die Produktionsaufträge treffen in zufälligen Abständen ein.
Die Durchlaufzeit eines Auftrags ist eine Zufallsvariable.
Weitere stochastische Einflüsse auf die Durchlaufzeit eines Auftrags $i$ :# 1.4 Aufträge/dynamisch-stochastische Situation 

Die Produktionsaufträge treffen in zufälligen Abständen ein.
Die Durchlaufzeit eines Auftrags ist eine Zufallsvariable.
Weitere stochastische Einflüsse auf die Durchlaufzeit eines Auftrags $i$ :
$\rightarrow$ stochastische Bearbeitungszeit des Auftrags $i$# 1.4 Aufträge/dynamisch-stochastische Situation 

Die Produktionsaufträge treffen in zufälligen Abständen ein.
Die Durchlaufzeit eines Auftrags ist eine Zufallsvariable.
Weitere stochastische Einflüsse auf die Durchlaufzeit eines Auftrags $i$ :
$\rightarrow$ stochastische Bearbeitungszeit des Auftrags $i$
$\rightarrow$ stochastische Bearbeitungszeiten der vor $i$ wartenden Aufträge# 1.4. Aufträge/dynamisch-stochastische Situation 

Die Produktionsaufträge treffen in zufälligen Abständen ein.
Die Durchlaufzeit eines Auftrags ist eine Zufallsvariable.
Weitere stochastische Einflüsse auf die Durchlaufzeit eines Auftrags $i$ :
$\rightarrow$ stochastische Bearbeitungszeit des Auftrags $i$
$\rightarrow$ stochastische Bearbeitungszeiten der vor $i$ wartenden Aufträge
Verdrängung des Auftrags $i$ zu einem zufälligen Zeitpunkt auf Grund der Ankunft eines wichtigeren Auftrags# 100 

## Warteschlangendisziplinen

FCFS (first come first served)
LCFS (last come first served)
SRO (service in random order)
PR (priority service)# Warteschlangendisziplinen 

- FCFS (first come first served)
- LCFS (last come first served)
- SRO (service in random order)
- PR (priority service)


## Prioritätsregeln

KOZ-Regel (Kürzeste-Operationszeit-Regel)
LOZ-Regel (Längste-Operationszeit-Regel)
GRB-Regel (Größte-Restbearbeitungszeit-Regel)
KRB-Regel (Kürzeste-Restbearbeitungszeit-Regel)
Liefertermin-Regel
...# 1.4. 

Erkenntnisse aus Simulationsuntersuchungen:
KOZ-Regel minimiert die mittlere Durchlaufzeit
$\Rightarrow$ hoher Anteil zu früh fertiggestellter Aufträge
$\Rightarrow$ Aufträge mit langer erwarteter Bearbeitungszeit bleiben liegen
$\Rightarrow$ hohe Streuung der Durchlaufzeiten
Liefertermin-Regel reduziert die Streuung der Durchlaufzeit
FCFS-Regel vermeidet hohen Anteil liegenbleibender AufträgeReihenfolgeabhängige Rüstzeiten# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$\Longrightarrow$ Travelling-Salesman Problem# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3 \rightarrow 10$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3 \rightarrow 10 \rightarrow 4$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3 \rightarrow 10 \rightarrow 4 \rightarrow 13$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3 \rightarrow 10 \rightarrow 4 \rightarrow 13 \rightarrow 5$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3 \rightarrow 10 \rightarrow 4 \rightarrow 13 \rightarrow 5 \rightarrow 14$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3 \rightarrow 10 \rightarrow 4 \rightarrow 13 \rightarrow 5 \rightarrow 14 \rightarrow 8$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3 \rightarrow 10 \rightarrow 4 \rightarrow 13 \rightarrow 5 \rightarrow 14 \rightarrow 8 \rightarrow 9$# Beispiel Umrüstzeiten bei der Schokoladenproduktion 

| auf Sorte $j$ <br> von Sorte $i$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 2 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 3 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 4 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 5 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |
| 6 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 7 | 32 | 7 | 5 | 34 | 481 | 0 | 0 | 481 | 481 | 6 | 32 | 8 | 34 | 481 |
| 8 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 0 | 3 | 33 | 32 | 33 | 34 | 4 |
| 9 | 32 | 33 | 33 | 34 | 3 | 33 | 33 | 5 | 0 | 33 | 32 | 33 | 34 | 4 |
| 10 | 32 | 2 | 0 | 34 | 481 | 4 | 5 | 481 | 481 | 0 | 32 | 3 | 34 | 481 |
| 11 | 0 | 33 | 33 | 34 | 481 | 33 | 33 | 481 | 481 | 33 | 0 | 33 | 34 | 481 |
| 12 | 32 | 0 | 5 | 34 | 481 | 4 | 5 | 481 | 481 | 6 | 32 | 0 | 34 | 481 |
| 13 | 32 | 33 | 33 | 0 | 481 | 33 | 33 | 481 | 481 | 33 | 32 | 33 | 0 | 481 |
| 14 | 32 | 33 | 33 | 34 | 0 | 33 | 33 | 2 | 3 | 33 | 32 | 33 | 34 | 0 |

$1 \rightarrow 11 \rightarrow 2 \rightarrow 12 \rightarrow 6 \rightarrow 7 \rightarrow 3 \rightarrow 10 \rightarrow 4 \rightarrow 13 \rightarrow 5 \rightarrow 14 \rightarrow 8 \rightarrow 9$Nach- und VorlaufzeitenDie Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |

![img-47.jpeg](img-47.jpeg)Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |

![img-48.jpeg](img-48.jpeg)Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |

![img-49.jpeg](img-49.jpeg)Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |


| 2 | 3 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |


| 2 | 3 |  | Nachlaufzeit |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |


| 2 | 3 |  | Nachlaun |  | 1 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | # Ablaufplanung für parallele Maschinen# Pm|P Aufträge/statische Situation|Zykluszeit# P2P Aufträge/statische Situation|Zykluszeit# Beispiel 

| Vorgang $j$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $_{j}$ | 9 | 7 | 6 | 5 | 4 | 3 | 3 | 1 |

(vgl. Jähn/Pesch (2014))

## (c) Univ.-Prof. Dr. Michael Manitz# Beispiel 

( vgl . Jähn/Pesch (2014))

| Vorgang $j$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $_{j}$ | 9 | 7 | 6 | 5 | 4 | 3 | 3 | 1 |

KOZ-Regel
![img-50.jpeg](img-50.jpeg)# Beispiel 

( vgl . Jähn/Pesch (2014))

| Vorgang $j$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $_{j}$ | 9 | 7 | 6 | 5 | 4 | 3 | 3 | 1 |

## LOZ-Regel

![img-51.jpeg](img-51.jpeg)![img-52.jpeg](img-52.jpeg)

# LOZ-Regel 

![img-53.jpeg](img-53.jpeg)

## Optimale Lösung

![img-54.jpeg](img-54.jpeg)

| Maschine 2 | 2 |  |  |  |  |  | 3 |  | 4 |  | 8 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Maschine 1 |  | 1 |  |  |  |  |  | 5 | 6 |  | 7 |
| 0 | 12 | 34 | 56 | 78 | 910 | 1112 | 1314 | 1516 | 1718 | 19 | 20 |

Termin![img-55.jpeg](img-55.jpeg)# Ablaufplanung für mehrere Produktionsstufen# Identische 

## Bearbeitungsreihenfolgen

(Flow Shop)# Ablaufplanung für zwei Maschinen 

(©) Univ.-Prof. Dr. Michael Manitz# Ablaufplanung für zwei Maschinen 

Johnson-Verfahren# Ablaufplanung für zwei Maschinen 

## Johnson-Verfahren

1. Suche den kürzesten, noch nicht eingeplanten Arbeitsgang!

Ist dieser Arbeitsgang einer an der ersten Maschine, dann ordne diesen möglichst weit vorn in die Bearbeitungsreihenfolge ein!
Ist dieser Arbeitsgang einer an der zweiten Maschine, dann ordne diesen möglichst weit hinten in die Bearbeitungsreihenfolge ein!
2. Wiederhole Schritt 1 !# Ablaufplanung für zwei Maschinen 

## Johnson-Verfahren

1. Suche den kürzesten, noch nicht eingeplanten Arbeitsgang!

- Ist dieser Arbeitsgang einer an der ersten Maschine, dann ordne diesen möglichst weit vorn in die Bearbeitungsreihenfolge ein!
- Ist dieser Arbeitsgang einer an der zweiten Maschine, dann ordne diesen möglichst weit hinten in die Bearbeitungsreihenfolge ein!

2. Wiederhole Schritt 1 !

Optimalitätsbedingung:
Erledige Auftrag $i$ vor $j$, falls $\min \left\{a_{i 1}, a_{j 2}\right\} \leq \min \left\{a_{i 2}, a_{j 1}\right\}$ !
( $a_{p m}=$ Dauer des Auftrags $p$ an Maschine $m$ )# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren
$\square$

Maschine
![img-56.jpeg](img-56.jpeg)
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
135-6# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren
$\square$

Maschine
![img-57.jpeg](img-57.jpeg)
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
$135-7$# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

## Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 |  |  |  | A |
| :-- | :-- | :-- | :-- | :-- |
|  |  |  |  |  |

Maschine
![img-58.jpeg](img-58.jpeg)# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 <br> Schritt 2 |  |  |  | B | A |
| :-- | :-- | :-- | :-- | :-- | :-- |
|  |  |  |  |  |  |

Maschine
![img-59.jpeg](img-59.jpeg)# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

## Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 <br> Schritt 2 <br> Schritt 3 | D |  |  | B | A |
| :-- | :-- | :-- | :-- | :-- | :-- |
|  |  |  |  | B | A |
|  |  |  |  |  |  |

Maschine
![img-60.jpeg](img-60.jpeg)# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

## Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 |  |  |  |  | A |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 |  |  | B | A |  |
| Schritt 3 | D |  |  | B | A |
| Schritt 4 | D |  | E | B | A |

Maschine
![img-61.jpeg](img-61.jpeg)# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 |  |  |  |  | A |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 |  |  |  | B | A |
| Schritt 3 | D |  |  | B | A |
| Schritt 4 | D |  | E | B | A |
| Schritt 5 | D | C | E | B | A |

Maschine
![img-62.jpeg](img-62.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Beispiel 5 Aufträge 

## Bearbeitungszeiten

| Auftrag | A | B | C | D | E |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 3 | 6 | 9 | 4 | 7 |
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 |  |  |  |  | A |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 |  |  |  | B | A |
| Schritt 3 | D |  |  | B | A |
| Schritt 4 | D |  | E | B | A |
| Schritt 5 | D | C | E | B | A |

Maschine
![img-63.jpeg](img-63.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Ablaufplanung für zwei Maschinen 

## Beispiel 8 Aufträge# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren
![img-64.jpeg](img-64.jpeg)

M1
M2
![img-65.jpeg](img-65.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren
![img-66.jpeg](img-66.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |

M1 M2

0
0
2
4
6
8
10
12
14
16
18
20
22
24
26
28
30
32
34
36
38
40
42
![img-67.jpeg](img-67.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |

M1
![img-68.jpeg](img-68.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
|  |  |  |  |  |  |  |  |  |

M1 5
M2
![img-69.jpeg](img-69.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
|  |  |  |  |  |  |  |  |  |

M1 5
M2
![img-70.jpeg](img-70.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |

M1 5 7
M2
![img-71.jpeg](img-71.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
|  |  |  |  |  |  |  |  |  |

M1 6 5 7 1
M2
![img-72.jpeg](img-72.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |

M1 6 5 7 1
M2
![img-73.jpeg](img-73.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1 6 5 7 1 3 4 2 8
M2
![img-74.jpeg](img-74.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1
![img-75.jpeg](img-75.jpeg)
![img-76.jpeg](img-76.jpeg)
![img-77.jpeg](img-77.jpeg)
![img-78.jpeg](img-78.jpeg)
![img-79.jpeg](img-79.jpeg)
![img-80.jpeg](img-80.jpeg)
![img-81.jpeg](img-81.jpeg)
![img-82.jpeg](img-82.jpeg)
![img-83.jpeg](img-83.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1 6 5 7 1 3 4 2 8
M2 6 5 5

| 0 | 2 | 4 | 6 | 8 | 10 | 12 | 14 | 16 | 18 | 20 | 22 | 24 | 26 | 28 | 30 | 32 | 34 | 36 | 38 | 40 | 42 | 44 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |

(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
$135-28$# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1 6 5 7 1 3 4 2 8
M2 6 5 7 1 3 4 2 8
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
$135-29$# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1 6 5 7 1 3 4 2 8
M2
![img-84.jpeg](img-84.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1 6 5 7 1 3 4 2 8
M2
![img-85.jpeg](img-85.jpeg)# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1 6 5 7 1 3 4 2 8
M2 6 5 7 1 3 4 2 8
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
$135-32$# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1 6 5 7 1 3 4 2 8
M2 6 5 7 1 3 4 2 8
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
135-33# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren

| Schritt 1 | 6 | - | - | - | - | - | - | - |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Schritt 2 | 6 | 5 | - | - | - | - | - | - |
| Schritt 3 | 6 | 5 | - | - | - | - | - | 8 |
| Schritt 4 | 6 | 5 | - | - | - | - | 2 | 8 |
| Schritt 5 | 6 | 5 | 7 | - | - | - | 2 | 8 |
| Schritt 6 | 6 | 5 | 7 | 1 | - | - | 2 | 8 |
| Schritt 7 | 6 | 5 | 7 | 1 | - | 4 | 2 | 8 |
| Schritt 8 | 6 | 5 | 7 | 1 | 3 | 4 | 2 | 8 |

M1 6 5 7 1 3 4 2 8
M2 6 5 7 1 3 4 2 8
$0 \quad 2 \quad 4 \quad 6 \quad 8 \quad 10 \quad 12 \quad 14 \quad 16 \quad 18 \quad 20 \quad 22 \quad 24 \quad 26 \quad 28 \quad 30 \quad 32 \quad 34 \quad 36 \quad 38 \quad 40 \quad 42 \quad 44$
( Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
135-34# Ablaufplanung für drei Maschinen 

## MERCATOR

© Univ.-Prof. Dr. Michael Manitz# Ablaufplanung für drei Maschinen 

Unter der Bedingung

$$
\min \left\{a_{i 1}\right\} \geq \max \left\{a_{i 2}\right\} \text { oder } \min \left\{a_{i 3}\right\} \geq \max \left\{a_{i 2}\right\}
$$

kann das Johnson-Verfahren für einen äquivalenten 2-Maschinen-FlowShop angewendet werden:# Ablaufplanung für drei Maschinen 

Unter der Bedingung

$$
\min \left\{a_{i 1}\right\} \geq \max \left\{a_{i 2}\right\} \text { oder } \min \left\{a_{i 3}\right\} \geq \max \left\{a_{i 2}\right\}
$$

kann das Johnson-Verfahren für einen äquivalenten 2-Maschinen-FlowShop angewendet werden:

$$
1 \rightarrow 2 \rightarrow 3
$$# Ablaufplanung für drei Maschinen 

Unter der Bedingung

$$
\min \left\{a_{i 1}\right\} \geq \max \left\{a_{i 2}\right\} \text { oder } \min \left\{a_{i 3}\right\} \geq \max \left\{a_{i 2}\right\}
$$

kann das Johnson-Verfahren für einen äquivalenten 2-Maschinen-FlowShop angewendet werden:
![img-86.jpeg](img-86.jpeg)# Ablaufplanung für drei Maschinen 

Unter der Bedingung

$$
\min \left\{a_{i 1}\right\} \geq \max \left\{a_{i 2}\right\} \text { oder } \min \left\{a_{i 3}\right\} \geq \max \left\{a_{i 2}\right\}
$$

kann das Johnson-Verfahren für einen äquivalenten 2-Maschinen-FlowShop angewendet werden:
![img-87.jpeg](img-87.jpeg)

Gilt o. a. Bedingung nicht, dann liefert diese Vorgehensweise als Heuristik dennoch gute Ergebnisse (Giglio/Wagner).![img-88.jpeg](img-88.jpeg)# Ablaufplanung für M Maschinen 

![img-89.jpeg](img-89.jpeg)# Ablaufplanung für M Maschinen 

![img-90.jpeg](img-90.jpeg)# Ablaufplanung für M Maschinen 

![img-91.jpeg](img-91.jpeg)# Ablaufplanung für M Maschinen 

![img-92.jpeg](img-92.jpeg)# Ablaufplanung für M Maschinen 

![img-93.jpeg](img-93.jpeg)# Ablaufplanung für M Maschinen 

![img-94.jpeg](img-94.jpeg)# Ablaufplanung für M Maschinen 

![img-95.jpeg](img-95.jpeg)# Ablaufplanung für M/Maschinen 

## NEH-Heuristik

1. Sortiere die Produktionsaufträge nach der Summe der Arbeitsgangdauern!
2. Bestimme die zykluszeitminimale Reihenfolge für die beiden längsten Aufträge!
3. Füge den nächstkürzeren Auftrag an die Stelle der bisher gefundenen Reihenfolge ein, an der die Zykluszeit minimal wird!
4. Wiederhole Schritt 3, bis alle Aufträge eingefügt worden sind!# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | 9 | 8 | 10 | 1 |
| A2 | 9 | 3 | 10 | 1 | 8 |
| A3 | 9 | 4 | 5 | 8 | 6 |
| A4 | 4 | 8 | 8 | 7 | 2 |# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

![img-96.jpeg](img-96.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

![img-97.jpeg](img-97.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

![img-98.jpeg](img-98.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

![img-99.jpeg](img-99.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

![img-100.jpeg](img-100.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

![img-101.jpeg](img-101.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

![img-102.jpeg](img-102.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

![img-103.jpeg](img-103.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

![img-104.jpeg](img-104.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

![img-105.jpeg](img-105.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

![img-106.jpeg](img-106.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

![img-107.jpeg](img-107.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: A3 $\rightarrow$ A1
![img-108.jpeg](img-108.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: A3 $\rightarrow$ A1
![img-109.jpeg](img-109.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: A3 $\rightarrow$ A1
![img-110.jpeg](img-110.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: A3 $\rightarrow$ A1
![img-111.jpeg](img-111.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-112.jpeg](img-112.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-113.jpeg](img-113.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-114.jpeg](img-114.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-115.jpeg](img-115.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-116.jpeg](img-116.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-117.jpeg](img-117.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-118.jpeg](img-118.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-119.jpeg](img-119.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-120.jpeg](img-120.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-121.jpeg](img-121.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-122.jpeg](img-122.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-123.jpeg](img-123.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-124.jpeg](img-124.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-125.jpeg](img-125.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1$
![img-126.jpeg](img-126.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-127.jpeg](img-127.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-128.jpeg](img-128.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-129.jpeg](img-129.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-130.jpeg](img-130.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-131.jpeg](img-131.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-132.jpeg](img-132.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-133.jpeg](img-133.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-134.jpeg](img-134.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-135.jpeg](img-135.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-136.jpeg](img-136.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-137.jpeg](img-137.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-138.jpeg](img-138.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-139.jpeg](img-139.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-140.jpeg](img-140.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-141.jpeg](img-141.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-142.jpeg](img-142.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-143.jpeg](img-143.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-144.jpeg](img-144.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-145.jpeg](img-145.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-146.jpeg](img-146.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-147.jpeg](img-147.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-148.jpeg](img-148.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-149.jpeg](img-149.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-150.jpeg](img-150.jpeg)# Ablaufplanung für 1/ Maschinen: NEH-Heuristik 

## Beispiel 4 Aufträge, 5 Bearbeitungsstufen

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-151.jpeg](img-151.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 | $\Sigma$ |
| A1 |  | 5 | 9 | 8 | 10 | 1 | 33 |
| A2 |  | 9 | 3 | 10 | 1 | 8 | 31 |
| A3 |  | 9 | 4 | 5 | 8 | 6 | 32 |
| A4 |  | 4 | 8 | 8 | 7 | 2 | 29 |

Beste gefundene Reihenfolge: $\mathrm{A} 4 \rightarrow \mathrm{~A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2$
![img-152.jpeg](img-152.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | 9 | 8 | 10 | 1 |
| A2 | 9 | 3 | 10 | 1 | 8 |
| A3 | 9 | 4 | 5 | 8 | 6 |
| A4 | 4 | 8 | 8 | 7 | 2 |

![img-153.jpeg](img-153.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 32 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 28 |
| A2 | 23 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 22 |
| A3 | 26 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 23 |
| A4 | 27 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 25 |

![img-154.jpeg](img-154.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 32 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 28 |
| A2 | 23 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 22 |
| A3 | 26 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 23 |
| A4 | 27 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 25 |

![img-155.jpeg](img-155.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |  |
| A1 | 32 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 28 |  |
| A2 | 23 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 22 |  |
| A3 | 26 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 23 |  |
| A4 | 27 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 25 |  |

![img-156.jpeg](img-156.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |  |
| A1 | 32 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 28 |  |
| A2 | 23 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 22 |  |
| A3 | 26 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 23 |  |
| A4 | 27 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 25 |  |

![img-157.jpeg](img-157.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 |
| A1 |  | 32 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 28 |
| A2 |  | 23 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 22 |
| A3 |  | 26 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 23 |
| A4 |  | 27 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 25 |

![img-158.jpeg](img-158.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 |
| A1 |  | 32 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 28 |
| A2 |  | 23 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 22 |
| A3 |  | 26 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 23 |
| A4 |  | 27 | $\leftrightarrows$ | $\leftrightarrows$ | $\leftrightarrows$ | 25 |

Beste gefundene Reihenfolge: $\mathrm{A} 1 \rightarrow \mathrm{~A} 4 \rightarrow \mathrm{~A} 3 \rightarrow \mathrm{~A} 2$
![img-159.jpeg](img-159.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | 9 | 8 | 10 | 1 |
| A2 | 9 | 3 | 10 | 1 | 8 |
| A3 | 9 | 4 | 5 | 8 | 6 |
| A4 | 4 | 8 | 8 | 7 | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 1 \rightarrow \mathrm{~A} 4 \rightarrow \mathrm{~A} 3 \rightarrow \mathrm{~A} 2$
![img-160.jpeg](img-160.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A2 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A3 | 18 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A4 | 20 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 17 |

Beste gefundene Reihenfolge: $\mathrm{A} 1 \rightarrow \mathrm{~A} 4 \rightarrow \mathrm{~A} 3 \rightarrow \mathrm{~A} 2$
![img-161.jpeg](img-161.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A2 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A3 | 18 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A4 | 20 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 17 |

Beste gefundene Reihenfolge: $\mathrm{A} 1 \rightarrow \mathrm{~A} 4 \rightarrow \mathrm{~A} 3 \rightarrow \mathrm{~A} 2$
![img-162.jpeg](img-162.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A2 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A3 | 18 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A4 | 20 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 17 |

Beste gefundene Reihenfolge: $\mathrm{A} 1 \rightarrow \mathrm{~A} 4 \rightarrow \mathrm{~A} 3 \rightarrow \mathrm{~A} 2$
![img-163.jpeg](img-163.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A2 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A3 | 18 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |
| A4 | 20 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 17 |

Beste gefundene Reihenfolge: $\mathrm{A} 1 \rightarrow \mathrm{~A} 4 \rightarrow \mathrm{~A} 3 \rightarrow \mathrm{~A} 2$
![img-164.jpeg](img-164.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |  |
| A1 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |  |
| A2 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |  |
| A3 | 18 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |  |
| A4 | 20 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 17 |  |

Beste gefundene Reihenfolge: $\mathrm{A} 1 \rightarrow \mathrm{~A} 4 \rightarrow \mathrm{~A} 3 \rightarrow \mathrm{~A} 2$
![img-165.jpeg](img-165.jpeg)# Ablaufplanung für M/Maschinen: Johnson-Verfahren 

## Beispiel 4 Aufträge, 5 Bearbeitungsstufen

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |  |
| A1 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |  |
| A2 | 22 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |  |
| A3 | 18 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 19 |  |
| A4 | 20 | $\leftarrow$ | $\leftrightarrows$ | $\rightarrow$ | 17 |  |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 4$
![img-166.jpeg](img-166.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | 9 | 8 | 10 | 1 |
| A2 | 9 | 3 | 10 | 1 | 8 |
| A3 | 9 | 4 | 5 | 8 | 6 |
| A4 | 4 | 8 | 8 | 7 | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 4$
![img-167.jpeg](img-167.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | 9 | $\cdot$ | 10 | 1 |
| A2 | 9 | 3 | $\cdot$ | 1 | 8 |
| A3 | 9 | 4 | $\cdot$ | 8 | 6 |
| A4 | 4 | 8 | $\cdot$ | 7 | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 4$
![img-168.jpeg](img-168.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 14 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 11 |
| A2 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |
| A3 | 13 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 14 |
| A4 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 4$
![img-169.jpeg](img-169.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 14 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 11 |
| A2 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |
| A3 | 13 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 14 |
| A4 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 4$
![img-170.jpeg](img-170.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 14 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 11 |
| A2 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |
| A3 | 13 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 14 |
| A4 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 4$
![img-171.jpeg](img-171.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 14 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 11 |
| A2 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |
| A3 | 13 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 14 |
| A4 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 4$
![img-172.jpeg](img-172.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |  |
| A1 | 14 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 11 |  |
| A2 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |  |
| A3 | 13 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 14 |  |
| A4 | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |  |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 4$
![img-173.jpeg](img-173.jpeg)# Ablaufplanung für M/Maschinen: Johnson-Verfahren 

## Beispiel 4 Aufträge, 5 Bearbeitungsstufen

| Auftrag | Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | M1 | M2 | M3 | M4 | M5 |
| A1 |  | 14 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 11 |
| A2 |  | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |
| A3 |  | 13 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 14 |
| A4 |  | 12 | $\leftarrow$ | $\cdot$ | $\rightarrow$ | 9 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 4$
![img-174.jpeg](img-174.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | 9 | $\cdot$ | 10 | 1 |
| A2 | 9 | 3 | $\cdot$ | 1 | 8 |
| A3 | 9 | 4 | $\cdot$ | 8 | 6 |
| A4 | 4 | 8 | $\cdot$ | 7 | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 4$
![img-175.jpeg](img-175.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | $\cdot$ | $\cdot$ | $\cdot$ | 1 |
| A2 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 8 |
| A3 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 6 |
| A4 | 4 | $\cdot$ | $\cdot$ | $\cdot$ | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 4$
![img-176.jpeg](img-176.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | $\cdot$ | $\cdot$ | $\cdot$ | 1 |
| A2 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 8 |
| A3 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 6 |
| A4 | 4 | $\cdot$ | $\cdot$ | $\cdot$ | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 4$
![img-177.jpeg](img-177.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | $\cdot$ | $\cdot$ | $\cdot$ | 1 |
| A2 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 8 |
| A3 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 6 |
| A4 | 4 | $\cdot$ | $\cdot$ | $\cdot$ | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 4$
![img-178.jpeg](img-178.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | $\cdot$ | $\cdot$ | $\cdot$ | 1 |
| A2 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 8 |
| A3 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 6 |
| A4 | 4 | $\cdot$ | $\cdot$ | $\cdot$ | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 4$
![img-179.jpeg](img-179.jpeg)# Beispiel 4 Aufträge, 5 Bearbeitungsstufen 

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |  |
| A1 | 5 | $\cdot$ | $\cdot$ | $\cdot$ | 1 |  |
| A2 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 8 |  |
| A3 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 6 |  |
| A4 | 4 | $\cdot$ | $\cdot$ | $\cdot$ | 2 |  |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 4$
![img-180.jpeg](img-180.jpeg)# Ablaufplanung für M/Maschinen: Johnson-Verfahren 

## Beispiel 4 Aufträge, 5 Bearbeitungsstufen

| Auftrag Maschine/Stufe | Bearbeitungszeit |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | M1 | M2 | M3 | M4 | M5 |
| A1 | 5 | $\cdot$ | $\cdot$ | $\cdot$ | 1 |
| A2 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 8 |
| A3 | 9 | $\cdot$ | $\cdot$ | $\cdot$ | 6 |
| A4 | 4 | $\cdot$ | $\cdot$ | $\cdot$ | 2 |

Beste gefundene Reihenfolge: $\mathrm{A} 3 \rightarrow \mathrm{~A} 1 \rightarrow \mathrm{~A} 2 \rightarrow \mathrm{~A} 4$
![img-181.jpeg](img-181.jpeg)# Job-Shop Scheduling# Die Shifting-Bottleneck-HeuristikJob-Shop Scheduling: Shifting-Bottleneck Procedure1. Löse für jedes Arbeitssystem („Maschine") ein einstufiges SchedulingProblem! Eine noch nicht geplante Maschine mit der längsten Zykluszeit ist die Engpassmaschine.
2. Bestimme für diese Engpassmaschine die zykluszeitminimale Auftragsreihenfolge!
3. Aktualisiere die Vorlaufzeiten für die einzelnen Aufträge auf Basis der bisher eingeplanten Reihenfolgen und den daraus resultierenden Wartezeiten!
4. Für alle noch nicht geplanten Maschinen: Gehe zu Schritt 1!
5. EndePrioritätsregelbasierte VerfahrenJob-Shop Scheduling# Job-Shop Scheduling 

Kritische Größen:
Staueffekte
$\triangleright$ hohe Lagerbestände
$\triangleright$ lange Wartezeiten
$\triangleright$ lange Durchlaufzeiten
Termineinhaltung
$\triangleright$ Verspätungen
$\triangleright$ Terminabweichungen# Job-Shop Scheduling 

Prioritätsregeln zum Abbau der Staueffekte
KOZ-Regel
$\triangleright$ Maximierung der Anzahl fertig bearbeiteter Aufträge
$\triangleright$ Minimierung der Durchlaufzeit
$\triangleright$ Erhöhung der Varianz der Durchlaufzeit
$\triangleright$ FCFS-Regel
$\triangleright$ Abbau des Bestands an liegengebliebenen AufträgenPrioritätsregeln zum Abbau der Staueffekte
KOZ-Regel
$\triangleright$ Maximierung der Anzahl fertig bearbeiteter Aufträge
$\triangleright$ Minimierung der Durchlaufzeit
$\triangleright$ Erhöhung der Varianz der Durchlaufzeit
$\Delta$ FCFS-Regel
$\triangleright$ Abbau des Bestands an liegengebliebenen Aufträgen

Anwendung der Prioritätsregeln
$\checkmark$ simultan: KOZ-Regel bis kritische Wartezeit, dann FCFS
$\checkmark$ abwechselnd
$\triangleright$ situationsabhängig: FCFS bis kritischer Bestand, dann KOZ-Regel bis untere Grenze beim Auftragsbestand, dann wieder FCFS usw.
$\triangleright$ regelmäßig: fester Rhythmus zwischen KOZ- und FCFS-RegelPrioritätsregeln zum Abbau der Staueffekte
KOZ-Regel
$\triangleright$ Maximierung der Anzahl fertig bearbeiteter Aufträge
$\triangleright$ Minimierung der Durchlaufzeit
$\triangleright$ Erhöhung der Varianz der Durchlaufzeit
$\Delta$ FCFS-Regel
$\triangleright$ Abbau des Bestands an liegengebliebenen Aufträgen

Anwendung der Prioritätsregeln
$\checkmark$ simultan: KOZ-Regel bis kritische Wartezeit, dann FCFS
abwechselnd $\Longrightarrow$ geringerer Anstieg der Durchlaufzeiten
$\triangleright$ situationsabhängig: FCFS bis kritischer Bestand, dann KOZ-Regel bis untere Grenze beim Auftragsbestand, dann wieder FCFS usw.
$\triangleright$ regelmäßig: fester Rhythmus zwischen KOZ- und FCFS-Regel"globale", bestandsorientierte Prioritätsregeln zum Abbau der Staueffekte
WINQ-Regel (work in next queue): Der Auftrag mit der kleinsten Warteschlange vor der nächsten anzulaufenden Maschine hat höchste Priorität.

- XWINQ-Regel (expected work in next queue): Der Auftrag mit der kleinsten Warteschlange - zuzüglich der bis dahin erwarteten zusätzlichen Aufträge - vor der nächsten anzulaufenden Maschine hat höchste Priorität.kombinierte Anwendung der Prioritätsregeln zum Abbau der Staueffekte

| Prioritätsregelkombination | mittlere Anzahl wartender Aufträge |
| :--: | :--: |
| KOZ | 23.25 |
| WINQ | 40.43 |
| XWINQ | 34.03 |
| $0.5 \cdot \mathrm{KOZ}+0.5 \cdot \mathrm{WINQ}$ | 30.14 |
| $0.9 \cdot \mathrm{KOZ}+0.1 \cdot \mathrm{WINQ}$ | 23.76 |
| $0.95 \cdot \mathrm{KOZ}+0.05 \cdot \mathrm{WINQ}$ | 23.00 |
| $0.97 \cdot \mathrm{KOZ}+0.03 \cdot \mathrm{WINQ}$ | 22.83 |
| $0.94 \cdot \mathrm{KOZ}+0.06 \cdot \mathrm{XWINQ}$ | 23.26 |
| $0.96 \cdot \mathrm{KOZ}+0.04 \cdot \mathrm{XWINQ}$ | 22.67 |
| $0.98 \cdot \mathrm{KOZ}+0.02 \cdot \mathrm{XWINQ}$ | 22.74 |kombinierte Anwendung der Prioritätsregeln zum Abbau der Staueffekte

| Prioritätsregelkombination | mittlere Anzahl wartender Aufträge |
| :--: | :--: |
| KOZ | 23.25 |
| WINQ | 40.43 |
| XWINQ | 34.03 |
| $0.5 \cdot \mathrm{KOZ}+0.5 \cdot \mathrm{WINQ}$ | 30.14 |
| $0.9 \cdot \mathrm{KOZ}+0.1 \cdot \mathrm{WINQ}$ | 23.76 |
| $0.95 \cdot \mathrm{KOZ}+0.05 \cdot \mathrm{WINQ}$ | 23.00 |
| $0.97 \cdot \mathrm{KOZ}+0.03 \cdot \mathrm{WINQ}$ | 22.83 |
| $0.94 \cdot \mathrm{KOZ}+0.06 \cdot \mathrm{XWINQ}$ | 23.26 |
| $0.96 \cdot \mathrm{KOZ}+0.04 \cdot \mathrm{XWINQ}$ | 22.67 |
| $0.98 \cdot \mathrm{KOZ}+0.02 \cdot \mathrm{XWINQ}$ | 22.74 |

$\Longrightarrow$ komplizierte Anwendung, aber nur geringe EffektePrioritätsregeln zur Einhaltung der Termine
Liefertermin-Regel (DDATE): Der Auftrag mit dem nächsten Liefertermin hat höchste Priorität.

Schlupfzeit-Regel (SLACK): Der Auftrag mit der geringsten Differenz aus Liefertermin und aktuellem Datum abzüglich der noch verbleibenden Bearbeitungszeiten hat höchste Priorität.

Schlupfzeit-pro-Arbeitsgang-Regel (SLACK/OPN): Der Auftrag mit dem geringsten Quotienten aus Schlupfzeit und Anzahl noch verbleibender Bearbeitungsvorgänge hat höchste Priorität.Conways Simulationsergebnisse (9 Maschinen, 8700 Aufträge)

| Prioritätsregel | Anzahl <br> Aufträge mit <br> Verspätung | mittlere <br> Terminab- <br> weichung | Varianz der <br> Terminab- <br> weichungen | mittlere <br> Durchlauf- <br> zeit |
| :-- | :--: | :--: | :--: | :--: |
| DDATE | $15.75 \%$ | -15.5 | 432 | 63.7 |
| SLACK | $22.02 \%$ | -13.1 | 433 | 65.8 |
| SLACK/OPN | $3.71 \%$ | -12.8 | 266 | 66.1 |
| KOZ | $5.02 \%$ | -44.9 | 2878 | 34.0 |
| FCFS | $44.79 \%$ | -4.5 | 1686 | 74.4 |# Zusammenhang zwischen Losgröße und Durchlaufzeit# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## MERsalOR

(©) Univ.-Prof. Dr. Michael Manitz# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Man betrachtet eine Werkstatt als ein M/M/1-Warteschlangensystem.# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Man betrachtet eine Werkstatt als ein M/M/1-Warteschlangensystem:
exponentialverteilte Zwischenankunftszeit von Aufträgen
exponentialverteilte Bearbeitungszeiten
$\rightarrow$ ein Server (eine Maschine)
$\rightarrow$ unbegrenzter Warteraum
$\rightarrow$ FCFS# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}=\frac{1}{\frac{P \cdot \tau+Q}{P}}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}=\frac{P}{P \cdot \tau+Q}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}=\frac{P}{P \cdot \tau+Q}$
Auslastung: $\rho=\frac{\lambda}{\mu}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}=\frac{P}{P \cdot \tau+Q}$
Auslastung: $\rho=\frac{\lambda}{\mu}=\frac{\frac{D}{Q}}{P \cdot \tau+Q}$
(c) Univ.-Prof. Dr. Michael Manitz# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}=\frac{P}{P \cdot \tau+Q}$
Auslastung: $\rho=\frac{\lambda}{\mu}=\frac{\frac{D}{Q}}{\frac{P}{P \cdot \tau+Q}}=\frac{D}{P} \cdot \frac{P \cdot \tau+Q}{Q}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}=\frac{P}{P \cdot \tau+Q}$
Auslastung: $\rho=\frac{\lambda}{\mu}=\frac{\frac{D}{Q}}{\frac{P}{P \cdot \tau+Q}}=\frac{D}{P} \cdot \frac{P \cdot \tau+Q}{Q}=\frac{D}{P} \cdot\left(\frac{P}{Q} \cdot \tau+1\right)$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}=\frac{P}{P \cdot \tau+Q}$
Auslastung: $\rho=\frac{\lambda}{\mu}=\frac{\frac{D}{Q}}{\frac{P}{P \cdot \tau+Q}}=\frac{D}{P} \cdot \frac{P \cdot \tau+Q}{Q}=\frac{D}{P} \cdot\left(\frac{P}{Q} \cdot \tau+1\right)=\frac{D \cdot \tau}{Q}+\frac{D}{P}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Wegen $\rho=\frac{D \cdot \tau}{Q}+\frac{D}{P} \stackrel{!}{<} 1 \Longleftrightarrow 1-\frac{D}{P}>\frac{D \cdot \tau}{Q}$ muss gelten:# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Wegen $\rho=\frac{D \cdot \tau}{Q}+\frac{D}{P} \stackrel{!}{<} 1 \Longleftrightarrow 1-\frac{D}{P}>\frac{D \cdot \tau}{Q}$ muss gelten:
$Q \stackrel{!}{>} \frac{D \cdot \tau}{1-\frac{D}{P}}$
(Untergrenze für die Losgröße)# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Wegen $\rho=\frac{D \cdot \tau}{Q}+\frac{D}{P} \stackrel{!}{<} 1 \Longleftrightarrow 1-\frac{D}{P}>\frac{D \cdot \tau}{Q}$ muss gelten:
$Q \stackrel{!}{>} \frac{D \cdot \tau}{1-\frac{D}{P}}$
(Untergrenze für die Losgröße)
mittlere Durchlaufzeit

$$
W=\frac{1}{\mu-\lambda}
$$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Wegen $\rho=\frac{D \cdot \tau}{Q}+\frac{D}{P} \stackrel{!}{<} 1 \Longleftrightarrow 1-\frac{D}{P}>\frac{D \cdot \tau}{Q}$ muss gelten:
$Q \stackrel{!}{>} \frac{D \cdot \tau}{1-\frac{D}{P}}$
(Untergrenze für die Losgröße)
mittlere Durchlaufzeit

$$
W=\frac{1}{\mu-\lambda}=\frac{1}{\frac{P}{P \cdot \tau+Q}-\frac{D}{Q}}
$$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Wegen $\rho=\frac{D \cdot \tau}{Q}+\frac{D}{P} \stackrel{!}{<} 1 \Longleftrightarrow 1-\frac{D}{P}>\frac{D \cdot \tau}{Q}$ muss gelten:
$Q \stackrel{!}{>} \frac{D \cdot \tau}{1-\frac{D}{P}}$
(Untergrenze für die Losgröße)
mittlere Durchlaufzeit

$$
W=\frac{1}{\mu-\lambda}=\frac{1}{\frac{P}{P \cdot \tau+Q}-\frac{D}{Q}}=\frac{1}{\frac{P-\frac{D}{Q} \cdot(P \cdot \tau+Q)}{P \cdot \tau+Q}}
$$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Wegen $\rho=\frac{D \cdot \tau}{Q}+\frac{D}{P} \stackrel{!}{<} 1 \Longleftrightarrow 1-\frac{D}{P}>\frac{D \cdot \tau}{Q}$ muss gelten:
$Q \stackrel{!}{>} \frac{D \cdot \tau}{1-\frac{D}{P}}$
(Untergrenze für die Losgröße)
mittlere Durchlaufzeit

$$
W=\frac{1}{\mu-\lambda}=\frac{1}{\frac{P}{P \cdot \tau+Q}-\frac{D}{Q}}=\frac{1}{\frac{P-\frac{D}{Q} \cdot(P \cdot \tau+Q)}{P \cdot \tau+Q}}=\frac{P \cdot \tau+Q}{P-\frac{D}{Q} \cdot(P \cdot \tau+Q)}
$$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Wegen $\rho=\frac{D \cdot \tau}{Q}+\frac{D}{P} \stackrel{!}{<} 1 \Longleftrightarrow 1-\frac{D}{P}>\frac{D \cdot \tau}{Q}$ muss gelten:
$Q \stackrel{!}{>} \frac{D \cdot \tau}{1-\frac{D}{P}}$
(Untergrenze für die Losgröße)

## mittlere Durchlaufzeit

$$
\begin{aligned}
W & =\frac{1}{\mu-\lambda}=\frac{1}{\frac{P}{P \cdot \tau+Q}-\frac{D}{Q}}=\frac{1}{\frac{P-\frac{D}{Q} \cdot(P \cdot \tau+Q)}{P \cdot \tau+Q}}=\frac{P \cdot \tau+Q}{P-\frac{D}{Q} \cdot(P \cdot \tau+Q)} \\
& =\frac{\tau+\frac{Q}{P}}{1-\frac{D \cdot \tau}{Q}-\frac{D}{P}}
\end{aligned}
$$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

$D=1.5, \tau=1, P=2$
![img-182.jpeg](img-182.jpeg)# Zusammenhang zwischen Losgröße und Durchlaufzeit 

$$
D=1.5, \tau=1, P=2
$$

![img-183.jpeg](img-183.jpeg)# Zusammenhang zwischen Losgröße und Durchlaufzeit 

$$
D=1.5, \tau=1, P=2
$$

![img-184.jpeg](img-184.jpeg)# Zusammenhang zwischen Losgröße und Durchlaufzeit 

$$
D=1.5, \tau=1, P=2
$$

![img-185.jpeg](img-185.jpeg)# Losgrößen- und 

## Ressourceneinsatzplanung bei

## Fließproduktion# Losgrößen- und 

## Reihenfolgeplanung bei

## Sortenproduktion# Sortenproduktion auf einer Anlage 

## MERCATOR

© Univ.-Prof. Dr. Michael Manitzkontinuierlicher, regelmäßiger Bedarf auf hohem Niveau# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau $\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell)

Minimiere $Z\left(\right.$ Losgröße $\left.q_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{D_{k}}{q_{k}} \cdot s_{k}+\frac{q_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau $\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell)

Minimiere $Z\left(\right.$ Losgröße $\left.q_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{D_{k}}{q_{k}} \cdot s_{k}+\frac{q_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$ $\frac{\mathrm{d} Z}{\mathrm{~d} q_{k}}=-\frac{D_{k}}{q_{k}^{2}} \cdot s_{k}+\frac{1}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau $\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell))

Minimiere $Z\left(\right.$ Losgröße $\left.q_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{D_{k}}{q_{k}} \cdot s_{k}+\frac{q_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$ $\frac{\mathrm{d} Z}{\mathrm{~d} q_{k}}=-\frac{D_{k}}{q_{k}^{2}} \cdot s_{k}+\frac{1}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow q_{k}=q_{k}^{\text {opt }}=\sqrt{\frac{2 \cdot D_{k} \cdot s_{k}}{\left(1-\rho_{k}\right) \cdot h_{k}}}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell))

Minimiere $Z\left(\right.$ Losgröße $\left.q_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{D_{k}}{q_{k}} \cdot s_{k}+\frac{q_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$ $\frac{\mathrm{d} Z}{\mathrm{~d} q_{k}}=-\frac{D_{k}}{q_{k}^{2}} \cdot s_{k}+\frac{1}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow q_{k}=q_{k}^{\mathrm{opt}}=\sqrt{\frac{2 \cdot D_{k} \cdot s_{k}}{\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Reichweite/Zykluslänge für Produkt $k: T_{k}=\frac{q_{k}}{D_{k}}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell))

Minimiere $Z\left(\right.$ Losgröße $\left.q_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{D_{k}}{q_{k}} \cdot s_{k}+\frac{q_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$ $\frac{\mathrm{d} Z}{\mathrm{~d} q_{k}}=-\frac{D_{k}}{q_{k}^{2}} \cdot s_{k}+\frac{1}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow q_{k}=q_{k}^{\mathrm{opt}}=\sqrt{\frac{2 \cdot D_{k} \cdot s_{k}}{\left(1-\rho_{k}\right) \cdot h_{k}}}$ $\Longrightarrow T_{k}=\frac{q_{k}}{D_{k}}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell))

Minimiere $Z\left(\right.$ Losgröße $\left.q_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{D_{k}}{q_{k}} \cdot s_{k}+\frac{q_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$ $\frac{\mathrm{d} Z}{\mathrm{~d} q_{k}}=-\frac{D_{k}}{q_{k}^{2}} \cdot s_{k}+\frac{1}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow q_{k}=q_{k}^{\mathrm{opt}}=\sqrt{\frac{2 \cdot D_{k} \cdot s_{k}}{\left(1-\rho_{k}\right) \cdot h_{k}}}$ $\Longrightarrow T_{k}=\frac{q_{k}}{D_{k}} \Longleftrightarrow q_{k}=D_{k} \cdot T_{k}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell))

Minimiere $Z$ (Zykluslänge $\left.T_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{D_{k}}{D_{k} \cdot T_{k}} \cdot s_{k}+\frac{D_{k} \cdot T_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$ $\frac{\mathrm{d} Z}{\mathrm{~d} q_{k}}=-\frac{D_{k}}{q_{k}^{2}} \cdot s_{k}+\frac{1}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow q_{k}=q_{k}^{\mathrm{opt}}=\sqrt{\frac{2 \cdot D_{k} \cdot s_{k}}{\left(1-\rho_{k}\right) \cdot h_{k}}}$ $\Longrightarrow T_{k}=\frac{q_{k}}{D_{k}} \Longleftrightarrow q_{k}=D_{k} \cdot T_{k}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell))

Minimiere $Z$ (Zykluslänge $\left.T_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T_{k}} \cdot s_{k}+\frac{D_{k} \cdot T_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$ $\frac{\mathrm{d} Z}{\mathrm{~d} q_{k}}=-\frac{D_{k}}{q_{k}^{2}} \cdot s_{k}+\frac{1}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow q_{k}=q_{k}^{\mathrm{opt}}=\sqrt{\frac{2 \cdot D_{k} \cdot s_{k}}{\left(1-\rho_{k}\right) \cdot h_{k}}}$ $\Longrightarrow T_{k}=\frac{q_{k}}{D_{k}} \Longleftrightarrow q_{k}=D_{k} \cdot T_{k}$# Sortenproduktion auf einer Anlage 

- kontinuierlicher, regelmäßiger Bedarf auf hohem Niveau
$\Rightarrow$ Bedarfsrate $D_{k}$ (für Produkt $k \in \mathcal{K}$ )
wechselnde Massenproduktion $\Rightarrow$ Rüstkostensatz $s_{k}$
endliche Produktionsgeschwindigkeit $\Rightarrow$ Produktionsrate $p_{k}$
$p_{k}>D_{k} \Rightarrow$ Lagerkostensatz $h_{k}$
- Produktionszeitanteil (Auslastung) für Produkt $k: \rho_{k}=\frac{D_{k}}{p_{k}}$


## Modell EOQ (klassisches Losgrößenmodell))

Minimiere $Z$ (Zykluslänge $\left.T_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T_{k}} \cdot s_{k}+\frac{D_{k} \cdot T_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$ $\frac{\mathrm{d} Z}{\mathrm{~d} T_{k}}=-\frac{1}{T_{k}^{2}} \cdot s_{k}+\frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T_{k}=T_{k}^{\text {opt }}=\sqrt{\frac{2 \cdot s_{k}}{D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$ $\Longrightarrow T_{k}=\frac{q_{k}}{D_{k}} \Longleftrightarrow q_{k}=D_{k} \cdot T_{k}$# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt <br> $k$ | Nachfrage- <br> rate $D_{k}$ | Produktions- <br> rate $p_{k}$ | Rüst- <br> zeit $\tau_{k}$ | Rüstkosten- <br> satz $s_{k}$ | Lagerkosten- <br> satz $h_{k}$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 4 | 150 | 18 | 5 | 0.000005 |
| 2 | 36 | 150 | 18 | 5 | 0.000005 |
| 3 | 25 | 150 | 18 | 5 | 0.000005 |
| 4 | 3 | 150 | 18 | 5 | 0.000005 |
| 5 | 2 | 150 | 18 | 5 | 0.000005 |
| 6 | 21 | 150 | 18 | 5 | 0.000005 |
| 7 | 9 | 150 | 18 | 5 | 0.000005 |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt <br> $k$ | Nachfrage- <br> rate $D_{k}$ | Produktions- <br> rate $p_{k}$ | Rüst- <br> zeit $\tau_{k}$ | Rüstkosten- <br> satz $s_{k}$ | Lagerkosten- <br> satz $h_{k}$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 4 | 150 | 18 | 5 | 0.000005 |
| 2 | 36 | 150 | 18 | 5 | 0.000005 |
| 3 | 25 | 150 | 18 | 5 | 0.000005 |
| 4 | 3 | 150 | 18 | 5 | 0.000005 |
| 5 | 2 | 150 | 18 | 5 | 0.000005 |
| 6 | 21 | 150 | 18 | 5 | 0.000005 |
| 7 | 9 | 150 | 18 | 5 | 0.000005 |


| $k$ | Losgröße $q_{k}$ |
| :-- | :--: |
| 1 | 2866.91 |
| 2 | 9733.29 |
| 3 | 7745.97 |
| 4 | 2474.36 |
| 5 | 2013.47 |
| 6 | 6988.36 |
| 7 | 4375.95 |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt <br> $k$ | Nachfrage- <br> rate $D_{k}$ | Produktions- <br> rate $p_{k}$ | Rüst- <br> zeit $\tau_{k}$ | Rüstkosten- <br> satz $s_{k}$ | Lagerkosten- <br> satz $h_{k}$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 4 | 150 | 18 | 5 | 0.000005 |
| 2 | 36 | 150 | 18 | 5 | 0.000005 |
| 3 | 25 | 150 | 18 | 5 | 0.000005 |
| 4 | 3 | 150 | 18 | 5 | 0.000005 |
| 5 | 2 | 150 | 18 | 5 | 0.000005 |
| 6 | 21 | 150 | 18 | 5 | 0.000005 |
| 7 | 9 | 150 | 18 | 5 | 0.000005 |


| $k$ | Losgröße $q_{k}$ | Produktionszeit |
| :-- | :--: | :--: |
| 1 | 2866.91 | 19.11 |
| 2 | 9733.29 | 64.89 |
| 3 | 7745.97 | 51.64 |
| 4 | 2474.36 | 16.50 |
| 5 | 2013.47 | 13.42 |
| 6 | 6988.36 | 46.59 |
| 7 | 4375.95 | 29.17 |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Produktionszeit | 19.11 | 64.89 | 51.64 | 16.50 | 13.42 | 46.59 | 29.17 |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Produktionszeit | 19.11 | 64.89 | 51.64 | 16.50 | 13.42 | 46.59 | 29.17 |

![img-186.jpeg](img-186.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Produktionszeit | 19.11 | 64.89 | 51.64 | 16.50 | 13.42 | 46.59 | 29.17 |

![img-187.jpeg](img-187.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Produktionszeit | 19.11 | 64.89 | 51.64 | 16.50 | 13.42 | 46.59 | 29.17 |

![img-188.jpeg](img-188.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Produktionszeit | 19.11 | 64.89 | 51.64 | 16.50 | 13.42 | 46.59 | 29.17 |

![img-189.jpeg](img-189.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt <br> $k$ | Nachfrage- <br> rate $D_{k}$ | Produktions- <br> rate $p_{k}$ | Rüst- <br> zeit $\tau_{k}$ | Rüstkosten- <br> satz $s_{k}$ | Lagerkosten- <br> satz $h_{k}$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 4 | 150 | 18 | 5 | 0.000005 |
| 2 | 36 | 150 | 18 | 5 | 0.000005 |
| 3 | 25 | 150 | 18 | 5 | 0.000005 |
| 4 | 3 | 150 | 18 | 5 | 0.000005 |
| 5 | 2 | 150 | 18 | 5 | 0.000005 |
| 6 | 21 | 150 | 18 | 5 | 0.000005 |
| 7 | 9 | 150 | 18 | 5 | 0.000005 |


| $k$ | Losgröße $q_{k}$ | Produktionszeit |
| :-- | :--: | :--: |
| 1 | 2866.91 | 19.11 |
| 2 | 9733.29 | 64.89 |
| 3 | 7745.97 | 51.64 |
| 4 | 2474.36 | 16.50 |
| 5 | 2013.47 | 13.42 |
| 6 | 6988.36 | 46.59 |
| 7 | 4375.95 | 29.17 |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt <br> $k$ | Nachfrage- <br> rate $D_{k}$ | Produktions- <br> rate $p_{k}$ | Rüst- <br> zeit $\tau_{k}$ | Rüstkosten- <br> satz $s_{k}$ | Lagerkosten- <br> satz $h_{k}$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 4 | 150 | 18 | 5 | 0.000005 |
| 2 | 36 | 150 | 18 | 5 | 0.000005 |
| 3 | 25 | 150 | 18 | 5 | 0.000005 |
| 4 | 3 | 150 | 18 | 5 | 0.000005 |
| 5 | 2 | 150 | 18 | 5 | 0.000005 |
| 6 | 21 | 150 | 18 | 5 | 0.000005 |
| 7 | 9 | 150 | 18 | 5 | 0.000005 |


| $k$ | Losgröße $q_{k}$ | Produktionszeit | Reichweite (Produktionszyklus) $T_{k}$ |
| :--: | :--: | :--: | :--: |
| 1 | 2866.91 | 19.11 | 716.73 |
| 2 | 9733.29 | 64.89 | 270.37 |
| 3 | 7745.97 | 51.64 | 309.84 |
| 4 | 2474.36 | 16.50 | 824.79 |
| 5 | 2013.47 | 13.42 | 1006.74 |
| 6 | 6988.36 | 46.59 | 332.78 |
| 7 | 4375.95 | 29.17 | 486.22 |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 716.73 | 270.37 | 309.84 | 824.79 | 1006.73 | 332.78 | 486.22 |

![img-190.jpeg](img-190.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 716.73 | 270.37 | 309.84 | 824.79 | 1006.73 | 332.78 | 486.22 |

![img-191.jpeg](img-191.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 716.73 | 270.37 | 309.84 | 824.79 | 1006.73 | 332.78 | 486.22 |

![img-192.jpeg](img-192.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 716.73 | 270.37 | 309.84 | 824.79 | 1006.73 | 332.78 | 486.22 |

![img-193.jpeg](img-193.jpeg)# Das Problem der Zulässigkeit# Das Problem der Zulässigkeit 

Produktionszeitraum: $T$# Das Problem der Zulässigkeit 

Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$# Das Problem der Zulässigkeit 

Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$# Das Problem der Zulässigkeit 

Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T
$$Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}}\left(\frac{\tau_{k}}{T_{k}}+\frac{D_{k}}{p_{k}}\right) \leq 1
$$Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}}\left(\frac{\tau_{k}}{T_{k}}+\frac{D_{k}}{p_{k}}\right) \leq 1
$$

# Beispiel 2 Produkte 

Zykluslängen: $T_{1}=1, T_{2}=2$
Rüstzeiten: $\tau_{1}=\tau_{2}=0.25$
Produktionszeitanteile: $\frac{D_{1}}{p_{1}}=0.25, \frac{D_{2}}{p_{2}}=0 . \overline{3}$Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}}\left(\frac{\tau_{k}}{T_{k}}+\frac{D_{k}}{p_{k}}\right) \leq 1
$$

# Beispiel 2 Produkte 

$\frac{\tau_{1}}{T_{1}}+\frac{D_{1}}{p_{1}}+\frac{\tau_{2}}{T_{2}}+\frac{D_{2}}{p_{2}}=\frac{0.25}{1}+0.25+\frac{0.25}{2}+0.3=\frac{6}{24}+\frac{6}{24}+\frac{3}{24}+\frac{8}{24}=\frac{23}{24}<1$Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}}\left(\frac{\tau_{k}}{T_{k}}+\frac{D_{k}}{p_{k}}\right) \leq 1
$$

# Beispiel 2 Produkte 

$\frac{\tau_{1}}{T_{1}}+\frac{D_{1}}{p_{1}}+\frac{\tau_{2}}{T_{2}}+\frac{D_{2}}{p_{2}}=\frac{0.25}{1}+0.25+\frac{0.25}{2}+0.3=\frac{6}{24}+\frac{6}{24}+\frac{3}{24}+\frac{8}{24}=\frac{23}{24}<1$
$\Longrightarrow$ notwendige Bedingung erfülltProduktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}}\left(\frac{\tau_{k}}{T_{k}}+\frac{D_{k}}{p_{k}}\right) \leq 1
$$

# Beispiel 2 Produkte 

$\frac{\tau_{1}}{T_{1}}+\frac{D_{1}}{p_{1}}+\frac{\tau_{2}}{T_{2}}+\frac{D_{2}}{p_{2}}=\frac{0.25}{1}+0.25+\frac{0.25}{2}+0.3=\frac{6}{24}+\frac{6}{24}+\frac{3}{24}+\frac{8}{24}=\frac{23}{24}<1$
![img-194.jpeg](img-194.jpeg)Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}}\left(\frac{\tau_{k}}{T_{k}}+\frac{D_{k}}{p_{k}}\right) \leq 1
$$

# Beispiel 2 Produkte 

$\frac{\tau_{1}}{T_{1}}+\frac{D_{1}}{p_{1}}+\frac{\tau_{2}}{T_{2}}+\frac{D_{2}}{p_{2}}=\frac{0.25}{1}+0.25+\frac{0.25}{2}+0.3=\frac{6}{24}+\frac{6}{24}+\frac{3}{24}+\frac{8}{24}=\frac{23}{24}<1$
![img-195.jpeg](img-195.jpeg)Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}}\left(\frac{\tau_{k}}{T_{k}}+\frac{D_{k}}{p_{k}}\right) \leq 1
$$

# Beispiel 2 Produkte 

$\frac{\tau_{1}}{T_{1}}+\frac{D_{1}}{p_{1}}+\frac{\tau_{2}}{T_{2}}+\frac{D_{2}}{p_{2}}=\frac{0.25}{1}+0.25+\frac{0.25}{2}+0.3=\frac{6}{24}+\frac{6}{24}+\frac{3}{24}+\frac{8}{24}=\frac{23}{24}<1$
![img-196.jpeg](img-196.jpeg)Produktionszeitraum: $T$
Produktionszeit (produktiv genutzte Zeit) für Produkt $k: \frac{D_{k}}{p_{k}} \cdot T$
Rüstzeit für Produkt $k: \tau_{k}$
Gesamte Rüstzeit für Produkt $k$ im Produktionszeitraum: $\tau_{k} \cdot \frac{T}{T_{k}}$
$\Longrightarrow$ Notwendige Bedingung für einen zulässigen Produktionsplan:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k} \cdot \frac{T}{T_{k}}+\frac{D_{k}}{p_{k}} \cdot T\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}}\left(\frac{\tau_{k}}{T_{k}}+\frac{D_{k}}{p_{k}}\right) \leq 1
$$

# Beispiel 2 Produkte 

$\frac{\tau_{1}}{T_{1}}+\frac{D_{1}}{p_{1}}+\frac{\tau_{2}}{T_{2}}+\frac{D_{2}}{p_{2}}=\frac{0.25}{1}+0.25+\frac{0.25}{2}+0.3=\frac{6}{24}+\frac{6}{24}+\frac{3}{24}+\frac{8}{24}=\frac{23}{24}<1$
![img-197.jpeg](img-197.jpeg)# Modell EOQ (Klassisches Losgrößenmodell) 

Minimiere $Z\left(\right.$ Losgröße $\left.q_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{D_{k}}{q_{k}} \cdot s_{k}+\frac{q_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} q_{k}}=-\frac{D_{k}}{q_{k}^{2}} \cdot s_{k}+\frac{1}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow q_{k}=q_{k}^{\mathrm{opt}}=\sqrt{\frac{2 \cdot D_{k} \cdot s_{k}}{\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Reichweite/Zykluslänge für Produkt $k: T_{k}=\frac{q_{k}^{\text {opt }}}{D_{k}}=\sqrt{\frac{2 \cdot s_{k}}{D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$# Modell EOQ (Klassisches Losgrößenmodell) 

Minimiere $Z\left(\right.$ Zykluslänge $\left.T_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T_{k}} \cdot s_{k}+\frac{D_{k} \cdot T_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} T_{k}}=-\frac{1}{T_{k}^{2}} \cdot s_{k}+\frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T_{k}=\sqrt{\frac{2 \cdot s_{k}}{D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T_{k}$# Identische Produktionszyklen# Modell EOQ (Klassisches Losgrößenmodell) 

Minimiere $Z\left(\right.$ Zykluslänge $\left.T_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T_{k}} \cdot s_{k}+\frac{D_{k} \cdot T_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} T_{k}}=-\frac{1}{T_{k}^{2}} \cdot s_{k}+\frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T_{k}=\sqrt{\frac{2 \cdot s_{k}}{D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T_{k}$# Modell ELSP (Common-Cycle Policy) 

Minimiere $Z$ (Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T} \cdot s_{k}+\frac{D_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} T}=-\frac{1}{T^{2}} \cdot \sum_{k \in \mathcal{K}} s_{k}+\sum_{k \in \mathcal{K}} \frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T=\sqrt{\frac{2 \cdot \sum_{k \in \mathcal{K}} s_{k}}{\sum_{k \in \mathcal{K}}} D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T$# Modell ELSP (Common-Cycle Policy) 

Minimiere $Z$ (Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T} \cdot s_{k}+\frac{D_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} T}=-\frac{1}{T^{2}} \cdot \sum_{k \in \mathcal{K}} s_{k}+\sum_{k \in \mathcal{K}} \frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T=\sqrt{\frac{2 \cdot \sum_{k \in \mathcal{K}} s_{k}}{\sum_{k \in \mathcal{K}}} D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T$
u. B. d. R.:

$$
\sum_{k \in \mathcal{K}}\left(\text { Rüstzeit }_{k}+\text { Produktionszeit }_{k}\right) \leq T
$$# Modell ELSP (Common-Cycle Policy) 

Minimiere $Z($ Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T} \cdot s_{k}+\frac{D_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} T}=-\frac{1}{T^{2}} \cdot \sum_{k \in \mathcal{K}} s_{k}+\sum_{k \in \mathcal{K}} \frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T=\sqrt{\frac{2 \cdot \sum_{k \in \mathcal{K}} s_{k}}{\sum_{k \in \mathcal{K}}} D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T$
u. B. d. R.:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k}+\frac{D_{k} \cdot T}{p_{k}}\right) \leq T
$$# Modell ELSP (Common-Cycle Policy) 

Minimiere $Z$ (Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T} \cdot s_{k}+\frac{D_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{d} T}=-\frac{1}{T^{2}} \cdot \sum_{k \in \mathcal{K}} s_{k}+\sum_{k \in \mathcal{K}} \frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T=\sqrt{\frac{2 \cdot \sum_{k \in \mathcal{K}} s_{k}}{\sum_{k \in \mathcal{K}}} D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T$
u. B. d. R.:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k}+\frac{D_{k} \cdot T}{p_{k}}\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}} \tau_{k} \leq T-\sum_{k \in \mathcal{K}} \frac{D_{k} \cdot T}{p_{k}}
$$# Modell ELSP (Common-Cycle Policy) 

Minimiere $Z$ (Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T} \cdot s_{k}+\frac{D_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} T}=-\frac{1}{T^{2}} \cdot \sum_{k \in \mathcal{K}} s_{k}+\sum_{k \in \mathcal{K}} \frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T=\sqrt{\frac{2 \cdot \sum_{k \in \mathcal{K}} s_{k}}{\sum_{k \in \mathcal{K}}} D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T$
u. B. d. R.:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k}+\frac{D_{k} \cdot T}{p_{k}}\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}} \tau_{k} \leq T \cdot\left(1-\sum_{k \in \mathcal{K}} \frac{D_{k}}{p_{k}}\right)
$$# Modell ELSP (Common-Cycle Policy) 

Minimiere $Z($ Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T} \cdot s_{k}+\frac{D_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} T}=-\frac{1}{T^{2}} \cdot \sum_{k \in \mathcal{K}} s_{k}+\sum_{k \in \mathcal{K}} \frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T=\sqrt{\frac{2 \cdot \sum_{k \in \mathcal{K}} s_{k}}{\sum_{k \in \mathcal{K}}} D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T$
u. B. d. R.:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k}+\frac{D_{k} \cdot T}{p_{k}}\right) \leq T \Longleftrightarrow \sum_{k \in \mathcal{K}} \tau_{k} \leq T \cdot\left(1-\sum_{k \in \mathcal{K}} \rho_{k}\right)
$$# Modell ELSP (Common-Cycle Policy) 

Minimiere $Z$ (Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T} \cdot s_{k}+\frac{D_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\frac{\mathrm{d} Z}{\mathrm{~d} T}=-\frac{1}{T^{2}} \cdot \sum_{k \in \mathcal{K}} s_{k}+\sum_{k \in \mathcal{K}} \frac{D_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k} \stackrel{!}{=} 0 \Longleftrightarrow T=\sqrt{\frac{2 \cdot \sum_{k \in \mathcal{K}} s_{k}}{\sum_{k \in \mathcal{K}}} D_{k} \cdot\left(1-\rho_{k}\right) \cdot h_{k}}}$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T$
u. B. d. R.:

$$
\sum_{k \in \mathcal{K}}\left(\tau_{k}+\frac{D_{k} \cdot T}{p_{k}}\right) \leq T \Longleftrightarrow \frac{\sum_{k \in \mathcal{K}} \tau_{k}}{1-\sum_{k \in \mathcal{K}} \rho_{k}} \leq T
$$# Losgrößen- und Reihenfolgeplanung bei Sortenproduktion 

## Beispiel Auspuffkrümmerfertigung an einer Blechpresse# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

Mindestzykluslänge: $T \geq \frac{126}{1-0.6}=378$# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

Mindestzykluslänge: $T \geq \frac{126}{1-0.6}=378$
Optimale Zykluslänge: $T_{\text {opt }}=\sqrt{\frac{2 \cdot 35}{0.0004176}}=409.420$# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

Mindestzykluslänge: $T \geq \frac{126}{1-0.6}=378$
Optimale Zykluslänge: $T_{\text {opt }}=\sqrt{\frac{2 \cdot 35}{0.0004176}}=409.420$

| Produkt | optimale Losgröße | Produktionszeit |
| :--: | :--: | :--: |
| 1 | $409.420 \cdot 4=\quad 1637.679$ | $\frac{1637.679}{150}=10.981$ |
| 2 | $409.420 \cdot 36=14739.110$ | $\frac{14739.110}{150}=98.261$ |
| 3 | $409.420 \cdot 25=10235.490$ | $\frac{10235.490}{150}=68.237$ |
| 4 | $409.420 \cdot 3=\quad 1228.259$ | $\frac{1228.259}{150}=8.188$ |
| 5 | $409.420 \cdot 2=\quad 818.839$ | $\frac{818.839}{150}=5.459$ |
| 6 | $409.420 \cdot 21=\quad 8597.814$ | $\frac{8597.814}{150}=57.319$ |
| 7 | $409.420 \cdot 9=\quad 3684.778$ | $\frac{3684.778}{150}=24.565$ |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

Mindestzykluslänge: $T \geq \frac{126}{1-0.6}=378$
Optimale Zykluslänge: $T_{\text {opt }}=\sqrt{\frac{2 \cdot 35}{0.0004176}}=409.420$

| Produkt | optimale Losgröße | Produktionszeit |
| :--: | :--: | :--: |
| 1 | $409.420 \cdot 4=\quad 1637.679$ | $\frac{1637.679}{150}=10.981$ |
| 2 | $409.420 \cdot 36=14739.110$ | $\frac{14739.110}{150}=98.261$ |
| 3 | $409.420 \cdot 25=10235.490$ | $\frac{10235.490}{150}=68.237$ |
| 4 | $409.420 \cdot 3=\quad 1228.259$ | $\frac{1228.259}{150}=8.188$ |
| 5 | $409.420 \cdot 2=\quad 818.839$ | $\frac{818.839}{150}=5.459$ |
| 6 | $409.420 \cdot 21=\quad 8597.814$ | $\frac{8597.814}{150}=57.319$ |
| 7 | $409.420 \cdot 9=\quad 3684.778$ | $\frac{3684.778}{150}=24.565$ |


| R | R | 2 | R | 3 | R | R | R | 6 | R | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 | 50 | 100 | 150 | 200 | 250 | 300 | 350 | 400 |  |  |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 716.728 | 270.369 | 309.839 | 824.786 | 1006.734 | 332.779 | 486.217 |
| Produktionszeit $\frac{q_{k}}{p_{k}}$ | 19.113 | 64.889 | 51.640 | 16.496 | 13.423 | 46.589 | 29.173 |

![img-198.jpeg](img-198.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 402.420 | 402.420 | 402.420 | 402.420 | 402.420 | 402.420 | 402.420 |
| Produktionszeit $\frac{q_{k}}{p_{k}}$ | 10.981 | 98.261 | 68.237 | 8.188 | 5.459 | 57.319 | 24.565 |

![img-199.jpeg](img-199.jpeg)# Produktspezifische Produktionszyklen# Modell EOQ (Klassisches Losgrößenmodell) 

Minimiere $Z\left(\right.$ Zykluslänge $\left.T_{k}\right)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T_{k}} \cdot s_{k}+\frac{D_{k} \cdot T_{k}}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T_{k}$
Notwendige Zulässigkeitsbedigung:

$$
\sum_{k \in \mathcal{K}}\left(\frac{T}{T_{k}} \cdot \tau_{k}+\frac{D_{k} \cdot T}{p_{k}}\right) \leq T
$$# Modell ELSP (Common-Cycle Policy) 

Minimiere $Z($ Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{T} \cdot s_{k}+\frac{D_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot T$
Notwendige Zulässigkeitsbedigung:

$$
\sum_{k \in \mathcal{K}}\left(\frac{T}{T} \cdot \tau_{k}+\frac{D_{k} \cdot T}{p_{k}}\right) \leq T
$$# Modell ELSP (Unique-Cycle Policy) 

Minimiere $Z$ (Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{m_{k} \cdot T} \cdot s_{k}+\frac{D_{k} \cdot m_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot m_{k} \cdot T$
Notwendige Zulässigkeitsbedigung:

$$
\sum_{k \in \mathcal{K}}\left(\frac{T}{m_{k} \cdot T} \cdot \tau_{k}+\frac{D_{k} \cdot m_{k} \cdot T}{p_{k}}\right) \leq T
$$# Modell ELSP (Unique-Cycle Policy) 

Minimiere $Z$ (Zykluslänge $T)=\sum_{k \in \mathcal{K}}\left(\frac{1}{m_{k} \cdot T} \cdot s_{k}+\frac{D_{k} \cdot m_{k} \cdot T}{2} \cdot\left(1-\rho_{k}\right) \cdot h_{k}\right)$
$\Longrightarrow$ Losgröße für Produkt $k: q_{k}^{\text {opt }}=D_{k} \cdot m_{k} \cdot T$
Notwendige Zulässigkeitsbedingung:

$$
\sum_{k \in \mathcal{K}}\left(\frac{T}{m_{k} \cdot T} \cdot \tau_{k}+\frac{D_{k} \cdot m_{k} \cdot T}{p_{k}}\right) \leq T
$$

Hinreichende Zulässigkeitsbedingungen:

- Wiederholung des gesamten Produktionszyklus nach $M=\max _{k}\left\{m_{k}\right\}$ Perioden
- Auflagehäufigkeit eines Produkts $k$ in diesem Zyklus: $\frac{M}{m_{k}}$
- Notwendige Bedingung: $\sum_{k \in \mathcal{K} \mid m_{k}=1}\left(\frac{\tau_{k}}{m_{k}}+\frac{D_{k} \cdot m_{k} \cdot T}{p_{k}}\right) \leq T$# Das Verfahren von Haessler# Optimierung von $T$ und $m_{k}$ für alle Produkte 

1. Bestimme für jedes Produkt isoliert-optimale Produktionszykluslängen $T_{k}$ nach dem Klassischen Losgrößenmodell!
2. Wie groß sollte eine Basiszykluslänge $T$ sein: zunächst $T=\min _{k}\left\{T_{k}\right\}$ ?
3. Falls $T_{k} \leq T: m_{k}=1$ !

Falls $T_{k}>T$ : Suche den minimalen $a_{k}$-Wert, für den $a_{k} \leq \frac{T_{k}}{T} \leq 2 \cdot a_{k}$ gilt, und berechne die Kosten für $m_{k}=a_{k}$ und $m_{k}=2 \cdot a_{k}$ ! Wähle $m_{k}$ entsprechend !
4. Bestimme günstige und zulässige Werte von $T$ mit aktuellen $m_{k}$-Werten!
5. Gehe mit neuen Werten für $T$ und $m_{k}$ zurück zur Abschätzung (s. o.)!# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 716.728 | 270.369 | 309.839 | 824.786 | 1006.734 | 332.779 | 486.217 |
| Produktionszeit $\frac{q_{k}}{p_{k}}$ | 19.113 | 64.889 | 51.640 | 16.496 | 13.423 | 46.589 | 29.173 |

![img-200.jpeg](img-200.jpeg)# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | $\mathbf{1}$ | $\mathbf{2}$ | $\mathbf{3}$ | $\mathbf{4}$ | $\mathbf{5}$ | $\mathbf{6}$ | $\mathbf{7}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 716.728 | 270.369 | 309.839 | 824.786 | 1006.734 | 332.779 | 486.217 |
| Produktionszeit $\frac{q_{k}}{p_{k}}$ | 19.113 | 64.889 | 51.640 | 16.496 | 13.423 | 46.589 | 29.173 |

Es ist $T=\min _{k}\left\{T_{k}\right\}=270.369$.
Liegt $\frac{T_{k}}{T}$ zwischen 1 und 2, zwischen 2 und 4, zwischen 4 und 8 usw. ? Und was ist dann der bessere $m_{k}$-Wert?
$\Longrightarrow m_{1}=2, m_{2}=1, m_{3}=1, m_{4}=4, m_{5}=4, m_{6}=1, m_{7}=2$
Neues optimales $T$ bei diesen neu bestimmten $m_{k}$-Werten: $T=285.239$
Nächste Iteration: $m_{1}=2, m_{2}=1, m_{3}=1, m_{4}=4, m_{5}=4, m_{6}=1, m_{7}=2$
Die $m_{k}$-Werte ändern sich nicht mehr.# Zulässiger Produktionsplan mit aktuellen $m_{k}$-Werten für alle Produkte 

1. Können durch Verdopplung von $m_{k}$ bessere Lösungen erzielt werden ?
2. Sortiere die Erzeugnisse nach $m_{k}$ aufsteigend und - nachrangig nach Belegungsdauern absteigend!
3. Erhöhe $T$, falls nicht alle vorgesehenen Produkte in der Basisperiode $T$ produziert werden können!
4. Versuche ggf. Verbesserungen zu entdecken!# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | $\mathbf{1}$ | $\mathbf{2}$ | $\mathbf{3}$ | $\mathbf{4}$ | $\mathbf{5}$ | $\mathbf{6}$ | $\mathbf{7}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Reichweite $T_{k}$ | 716.728 | 270.369 | 309.839 | 824.786 | 1006.734 | 332.779 | 486.217 |
| Produktionszeit $\frac{q_{k}}{p_{k}}$ | 19.113 | 64.889 | 51.640 | 16.496 | 13.423 | 46.589 | 29.173 |

Es ist letztlich $T=\min _{k}\left\{T_{k}\right\}=301.179$.
Dann ergeben sich neue Werte:
$\Longrightarrow m_{1}=2, m_{2}=1, m_{3}=1, m_{4}=2, m_{5}=4, m_{6}=1, m_{7}=2$
$T$ ist dafür zu kurz. Die Basisperiodenlänge muss erhöht werden!
Letztlich ergibt sich: $T=321.429$
Das heißt: $q_{1}=2571.429, q_{2}=11571.430, q_{3}=8035.715, q_{4}=1928.572, q_{5}=$ $2571.429, q_{6}=6750.001, q_{7}=5785.715$# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Losgröße $q_{k}$ | 2571.429 | 11571.430 | 8035.715 | 1928.572 | 2571.429 | 6750.001 | 5785.715 |
| Produktionszeit $\frac{q_{k}}{p_{k}}$ | 17.143 | 77.143 | 53.571 | 12.857 | 17.143 | 45.000 | 38.571 |# Beispiel Auspuffkrümmerfertigung an einer Blechpresse 

| Produkt $k$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Losgröße $q_{k}$ | 2571.429 | 11571.430 | 8035.715 | 1928.572 | 2571.429 | 6750.001 | 5785.715 |
| Produktionszeit $\frac{q_{k}}{p_{k}}$ | 17.143 | 77.143 | 53.571 | 12.857 | 17.143 | 45.000 | 38.571 |

![img-201.jpeg](img-201.jpeg)# Einlastungsplanung bei Variantenfließproduktion![img-202.jpeg](img-202.jpeg)
(Quelle: Günther/Tempelmeier (2005))# Variantenfließproduktion 

![img-203.jpeg](img-203.jpeg)
(Quelle: Günther/Tempelmeier (2005))
(C) Univ.-Prof. Dr. Michael Manitz# Weg-Zeit-Diagramm 

![img-204.jpeg](img-204.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Zeit-Weg-Diagramm 

![img-205.jpeg](img-205.jpeg)# Zeit-Weg-Diagramm 

![img-206.jpeg](img-206.jpeg)# Zeit-Weg-Diagramm 

![img-207.jpeg](img-207.jpeg)# Zeit-Weg-Diagramm 

![img-208.jpeg](img-208.jpeg)# Zeit-Weg-Diagramm 

![img-209.jpeg](img-209.jpeg)# Zeit-Weg-Diagramm 

![img-210.jpeg](img-210.jpeg)# Zeit-Weg-Diagramm 

![img-211.jpeg](img-211.jpeg)# Zeit-Weg-Diagramm 

![img-212.jpeg](img-212.jpeg)# Zeit-Weg-Diagramm 

Idealfall: gleiche Arbeitsbelastung für alle in Höhe der Taktzeit
![img-213.jpeg](img-213.jpeg)# Zeit-Weg-Diagramm 

![img-214.jpeg](img-214.jpeg)![img-215.jpeg](img-215.jpeg)# Zeit-Weg-Diagramm 

![img-216.jpeg](img-216.jpeg)# Zeit-Weg-Diagramm 

Idealfall: gleiche Arbeitsbelastung für alle in Höhe der Taktzeit
![img-217.jpeg](img-217.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Arbeitsbelastung und Reihenfolge 

## Zeit-Weg-Diagramm

Reihenfolge: A-A-A-B-B-B
![img-218.jpeg](img-218.jpeg)# Arbeitsbelastung und Reihenfolge 

## Zeit-Weg-Diagramm

Reihenfolge: A-A-A-B-B-B
![img-219.jpeg](img-219.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Arbeitsbelastung und Reihenfolge 

## Zeit-Weg-Diagramm

Reihenfolge: A-A-A-B-B-B
![img-220.jpeg](img-220.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Arbeitsbelastung und Reihenfolge 

## Zeit-Weg-Diagramm

Reihenfolge: A-B-A-B-A-B
![img-221.jpeg](img-221.jpeg)# Einlastungsplanung 

(6) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
$162-1$Ziel: Glättung der Arbeitsbelastung an den einzelnen StationenZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

# Level SchedulingZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

# - Level Scheduling (variantenbezogen-bedarfsorientiert)Ziel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus stattungsvariantenZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von LagerbeständenZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car SequencingZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car Sequencing (variantenbezogen-kapazitätsorientiert)Ziel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car Sequencing (variantenbezogen-kapazitätsorientiert)
$\triangleright$ alternierende Auflage von Varianten mit über- und unterdurchschnittlicher Arbeitsbelastung an den EngpassstationenZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car Sequencing (variantenbezogen-kapazitätsorientiert)
$\triangleright$ alternierende Auflage von Varianten mit über- und unterdurchschnittlicher Arbeitsbelastung an den Engpassstationen
$\triangleright$ zulässige Einlastungsreihenfolgen in bezug auf gewisse AbstandsregelnZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car Sequencing (variantenbezogen-kapazitätsorientiert)
$\triangleright$ alternierende Auflage von Varianten mit über- und unterdurchschnittlicher Arbeitsbelastung an den Engpassstationen
$\triangleright$ zulässige Einlastungsreihenfolgen in bezug auf gewisse Abstandsregeln
- Mixed-Model SequencingZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car Sequencing (variantenbezogen-kapazitätsorientiert)
$\triangleright$ alternierende Auflage von Varianten mit über- und unterdurchschnittlicher Arbeitsbelastung an den Engpassstationen
$\triangleright$ zulässige Einlastungsreihenfolgen in bezug auf gewisse Abstandsregeln
- Mixed-Model Sequencing (werkstückbezogen-kapazitätsorientiert)Ziel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car Sequencing (variantenbezogen-kapazitätsorientiert)
$\triangleright$ alternierende Auflage von Varianten mit über- und unterdurchschnittlicher Arbeitsbelastung an den Engpassstationen
$\triangleright$ zulässige Einlastungsreihenfolgen in bezug auf gewisse Abstandsregeln
- Mixed-Model Sequencing (werkstückbezogen-kapazitätsorientiert)
$\triangleright$ optimale Reihenfolge der einzelnen Werkstücke mit möglichst wenig überdurchschnittlicher Arbeitsbelastung an den einzelnen StationenZiel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car Sequencing (variantenbezogen-kapazitätsorientiert)
$\triangleright$ alternierende Auflage von Varianten mit über- und unterdurchschnittlicher Arbeitsbelastung an den Engpassstationen
$\triangleright$ zulässige Einlastungsreihenfolgen in bezug auf gewisse Abstandsregeln
- Mixed-Model Sequencing (werkstückbezogen-kapazitätsorientiert)
$\triangleright$ optimale Reihenfolge der einzelnen Werkstücke mit möglichst wenig überdurchschnittlicher Arbeitsbelastung an den einzelnen Stationen
$\triangleright$ Reduktion der Taktzeitüberschreitungen# Level Scheduling# Level Scheduling 

## MERCATOR

© Univ.-Prof. Dr. Michael ManitzAnzahl Slots (Positionen, Takte) in einer Schicht: $T$# Level Scheduling 

Anzahl Slots (Positionen, Takte) in einer Schicht: $T$
Anzahl zu produzierender Einheiten von Variante $v: d_{v} \quad(v \in \mathcal{V})$# Level Scheduling 

Anzahl Slots (Positionen, Takte) in einer Schicht: $T$
Anzahl zu produzierender Einheiten von Variante $v: d_{v} \quad(v \in \mathcal{V})$
Es muss in bezug auf eine Schichtlänge $T$ gelten:

$$
\sum_{v \in \mathcal{V}} d_{v}=T
$$# Level Scheduling 

Anzahl Slots (Positionen, Takte) in einer Schicht: $T$
Anzahl zu produzierender Einheiten von Variante $v: d_{v} \quad(v \in \mathcal{V})$
Es muss in bezug auf eine Schichtlänge $T$ gelten:

$$
\sum_{v \in \mathcal{V}} d_{v}=T
$$

Möglicherweise findet sich ein kleinerer Zyklus, der sich immer wieder wiederholt, wenn man die Bedarfsmengen pro Schicht durch den größten gemeinsamen Teiler dividiert.# Level Scheduling 

Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$# Level Scheduling 

![img-222.jpeg](img-222.jpeg)# Level Scheduling 

![img-223.jpeg](img-223.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$# Level Scheduling 

Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$
![img-224.jpeg](img-224.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ |
| :--: | :--: | :--: |
| 1 | 1 | 1.5 |
| 1 | 2 | 4.5 |
| 2 | 1 | 0.75 |
| 2 | 2 | 2.25 |
| 2 | 3 | 3.75 |
| 2 | 4 | 5.25 |# Level Scheduling 

Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$
![img-225.jpeg](img-225.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt |
| :--: | :--: | :--: | :--: |
| 1 | 1 | 1.5 | 2 |
| 1 | 2 | 4.5 | 5 |
| 2 | 1 | 0.75 | 1 |
| 2 | 2 | 2.25 | 3 |
| 2 | 3 | 3.75 | 4 |
| 2 | 4 | 5.25 | 6 |# Level Scheduling 

Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$
![img-226.jpeg](img-226.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt |
| :--: | :--: | :--: | :--: |
| 1 | 1 | 1.5 | 2 |
| 1 | 2 | 4.5 | 5 |
| 2 | 1 | 0.75 | 1 |
| 2 | 2 | 2.25 | 3 |
| 2 | 3 | 3.75 | 4 |
| 2 | 4 | 5.25 | 6 |# Level Scheduling 

Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$
![img-227.jpeg](img-227.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt |
| :--: | :--: | :--: | :--: |
| 1 | 1 | 1.5 | 2 |
| 1 | 2 | 4.5 | 5 |
| 2 | 1 | 0.75 | 1 |
| 2 | 2 | 2.25 | 3 |
| 2 | 3 | 3.75 | 4 |
| 2 | 4 | 5.25 | 6 |# Level Scheduling 

Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$
![img-228.jpeg](img-228.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt |
| :--: | :--: | :--: | :--: |
| 2 | 1 | 0.75 | 1 |
| 1 | 1 | 1.5 | 2 |
| 2 | 2 | 2.25 | 3 |
| 2 | 3 | 3.75 | 4 |
| 1 | 2 | 4.5 | 5 |
| 2 | 4 | 5.25 | 6 |Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$
![img-229.jpeg](img-229.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt |
| :--: | :--: | :--: | :--: |
| 2 | 1 | 0.75 | 1 |
| 1 | 1 | 1.5 | 2 |
| 2 | 2 | 2.25 | 3 |
| 2 | 3 | 3.75 | 4 |
| 1 | 2 | 4.5 | 5 |
| 2 | 4 | 5.25 | 6 |

Optimierungsproblem: Minimiere die Abweichungen zum Idealtermin!# APPLICATION 

## Modell LEVEL SCHEDULING# Modell LEVEL SCHEDULING 

Was muss festgelegt werden:
... Im wievielten Takt innerhalb eines Produktionszyklus der Länge $T$ soll eine bestimmte Produktvariante eingelastet werden?# Optimierungsmodell zum Level Scheduling 

## Modell LEVEL SCHEDULING

Was muss festgelegt werden - Entscheidungsvariable:
$x_{v w} \in\{1, \ldots, T\} \ldots$ Takt/Position des $w$-ten Werkstücks der Variante $v$# Optimierungsmodell zum Level Scheduling 

## Modell LEVEL SCHEDULING

Gegeben:
... die Menge der einzuschleusenden Varianten# Optimierungsmodell zum Level Scheduling 

## Modell LEVEL SCHEDULING

Gegeben:
... die Menge der einzuschleusenden Varianten
... die Anzahl zu bearbeitender Werkstücke# Optimierungsmodell zum Level Scheduling 

## Modell LEVEL SCHEDULING

Gegeben — Indexmengen:
$\mathcal{V} \ldots$ die Menge der einzuschleusenden Varianten
$d_{v} \ldots$ die Anzahl zu bearbeitender Werkstücke von Variante $v ; v \in \mathcal{V}$# Modell LEVEL SCHEDULING 

Gegeben — Indexmengen:
$\mathcal{V} \ldots$ die Menge der einzuschleusenden Varianten
$d_{v} \ldots$ die Anzahl zu bearbeitender Werkstücke von Variante $v ; v \in \mathcal{V}$

Gegeben:
... der optimale Einlastungszeitpunkt der einzelnen Werkstücke# Modell LEVEL SCHEDULING 

Gegeben — Indexmengen:
$\mathcal{V} \ldots$ die Menge der einzuschleusenden Varianten
$d_{v} \ldots$ die Anzahl zu bearbeitender Werkstücke von Variante $v ; v \in \mathcal{V}$

Gegeben — Daten:
$t_{v w} \ldots$ Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$# APPLICATION 

## Modell LEVEL SCHEDULING# Modell LEVEL SCHEDULING 

Minimiere

## Abweichungen zur optimalen Position der Werkstücke

$$
Z=\sum_{v \in \mathcal{V}} \sum_{w=1}^{d_{v}}\left(x_{v w}-t_{v w}\right)^{2}
$$

u. B. d. R.:

Anstieg der Positionen (fortlaufende Numerierung der Takte)

$$
x_{v, w+1} \geq x_{v w}+1 \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

Verhinderung der Doppel- bzw. Mehrfachzuweisung

$$
x_{v w} \neq x_{v^{\prime} w^{\prime}} \quad\left(v, v^{\prime} \in \mathcal{V} ; w, w^{\prime}=1, \ldots, d_{v} ;(v w) \neq\left(v^{\prime} w^{\prime}\right)\right)
$$# Level Scheduling 

Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$
![img-230.jpeg](img-230.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt |
| :--: | :--: | :--: | :--: |
| 2 | 1 | 0.75 | 1 |
| 1 | 1 | 1.5 | 2 |
| 2 | 2 | 2.25 | 3 |
| 2 | 3 | 3.75 | 4 |
| 1 | 2 | 4.5 | 5 |
| 2 | 4 | 5.25 | 6 |# Level Scheduling 

Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$
![img-231.jpeg](img-231.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt $x_{v w}$ |
| :--: | :--: | :--: | :--: |
| 2 | 1 | 0.75 | 1 |
| 1 | 1 | 1.5 | 2 |
| 2 | 2 | 2.25 | 3 |
| 2 | 3 | 3.75 | 4 |
| 1 | 2 | 4.5 | 5 |
| 2 | 4 | 5.25 | 6 |# Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$ 

![img-232.jpeg](img-232.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt $x_{v w}$ | $\left(x_{v w}-t_{v w}\right)$ | $\left(x_{v w}-t_{v w}\right)^{2}$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 2 | 1 | 0.75 | 1 | 0.25 | 0.0625 |
| 1 | 1 | 1.5 | 2 | 0.50 | 0.2500 |
| 2 | 2 | 2.25 | 3 | 0.75 | 0.5625 |
| 2 | 3 | 3.75 | 4 | 0.25 | 0.0625 |
| 1 | 2 | 4.5 | 5 | 0.50 | 0.2500 |
| 2 | 4 | 5.25 | 6 | 0.75 | 0.5625 |# Beispiel 2 Varianten $\left(d_{1}=2, d_{2}=4 \Longrightarrow T=6\right)$ 

![img-233.jpeg](img-233.jpeg)

Optimaler Einplanungszeitpunkt des $w$-ten Werkstücks von Variante $v$ :

$$
t_{v w}=\frac{w-\frac{1}{2}}{d_{v}} \cdot T \quad\left(v \in \mathcal{V} ; w=1, \ldots, d_{v}\right)
$$

| Variante $v$ | Werkstück $w$ | $t_{v w}$ | Takt $x_{v w}$ | $\left(x_{v w}-t_{v w}\right)$ | $\left(x_{v w}-t_{v w}\right)^{2}$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 2 | 1 | 0.75 | 1 | 0.25 | 0.0625 |
| 1 | 1 | 1.5 | 2 | 0.50 | 0.2500 |
| 2 | 2 | 2.25 | 3 | 0.75 | 0.5625 |
| 2 | 3 | 3.75 | 4 | 0.25 | 0.0625 |
| 1 | 2 | 4.5 | 5 | 0.50 | 0.2500 |
| 2 | 4 | 5.25 | 6 | 0.75 | 0.5625 |
|  |  |  |  | Summe | 1.75 |# Car Sequencing# APPLICATION 

## Modell CAR SEQUENCING# APPLIED 

## Modell CAR SEQUENCING

Was muss festgelegt werden:
... Im wievielten Takt innerhalb einer Produktionsperiode (z. B. in einer Schicht) soll eine bestimmte Produktvariante eingelastet werden?# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

Was muss festgelegt werden - Entscheidungsvariable:
$x_{v t} \in\{0 ; 1\} \ldots$ Im wievielten Takt innerhalb einer Produktionsperiode (z. B. in einer Schicht) soll eine bestimmte Produktvariante eingelastet werden?

$$
x_{v t}=\left\{\begin{array}{l}
1, \text { wenn Variante } v \text { im } t \text {-ten Takt eingelastet wird, d. h. an } \\
t \text {-ter Stelle in der Auftragsreihenfolge einer Schicht steht } \\
0 \text { sonst }
\end{array}\right.
$$# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

Gegeben:
... die Anzahl Slots (Takte) in einer Schicht
... die Menge der einzuschleusenden Varianten
... die Menge der verfügbaren Optionen# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

Gegeben — Indexmengen:
$T$... die Anzahl Slots (Takte) in einer Schicht
$\mathcal{V} \ldots$ die Menge der einzuschleusenden Varianten
$\mathcal{O} \ldots$ die Menge der verfügbaren Optionen# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

Gegeben — Indexmengen:
$T$... die Anzahl Slots (Takte) in einer Schicht
$\mathcal{V} \ldots$ die Menge der einzuschleusenden Varianten
$\mathcal{O} \ldots$ die Menge der verfügbaren Optionen
Gegeben:
... Optionenkatalog für einzelne Varianten# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

Gegeben — Indexmengen:
$T \ldots$ die Anzahl Slots (Takte) in einer Schicht
$\mathcal{V} \ldots$ die Menge der einzuschleusenden Varianten
$\mathcal{O} \ldots$ die Menge der verfügbaren Optionen
Gegeben:
$a_{v o} \ldots$ Indikator, der durch den Wert 1 anzeigt, ob Option $o$ bei Variante $v$ enthalten ist# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

Gegeben — Indexmengen:
$T \ldots$ die Anzahl Slots (Takte) in einer Schicht
$\mathcal{V} \ldots$ die Menge der einzuschleusenden Varianten
$\mathcal{O} \ldots$ die Menge der verfügbaren Optionen
Gegeben:
$a_{v o} \ldots$ Indikator, der durch den Wert 1 anzeigt, ob Option $o$ bei Variante $v$ enthalten ist
$d_{v} \ldots$ Anzahl zu produzierender Einheiten von Variante $v$# APPLICATION 

## Modell CAR SEQUENCING# APPLICATION 

## Modell CAR SEQUENCING

## $h_{o}: n_{o}$-Forderung# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

## $h_{o}: n_{o}$-Forderung

Für jede Option o müssen gewisse Mindestabstände eingehalten werden.# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

## $h_{o}: n_{o}$-Forderung

Für jede Option o müssen gewisse Mindestabstände eingehalten werden, d. h., in den $n_{o}$ Takten $t, t+1, \ldots, t+n_{o}-1$ dürfen höchstens $h_{o}$ Einheiten der Varianten $v$, die die Option o benötigen, eingelastet werden# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

## $h_{o}: n_{o}$-Forderung

Für jede Option o müssen gewisse Mindestabstände eingehalten werden, d. h., in den $n_{o}$ Takten $t, t+1, \ldots, t+n_{o}-1$ dürfen höchstens $h_{o}$ Einheiten der Varianten $v$, die die Option o benötigen, eingelastet werden

$$
\sum_{v \in \mathcal{V}} \sum_{j=t}^{t+n_{o}-1} a_{v o} \cdot x_{v j} \leq h_{o} \quad\left(o \in \mathcal{O} ; t=1, \ldots, T-n_{o}+1\right)
$$# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

## $h_{o}: n_{o}$-Forderung

Für jede Option o müssen gewisse Mindestabstände eingehalten werden, d. h., in den $n_{o}$ Takten $t, t+1, \ldots, t+n_{o}-1$ dürfen höchstens $h_{o}$ Einheiten der Varianten $v$, die die Option o benötigen, eingelastet werden

$$
\sum_{v \in \mathcal{V}} \sum_{j=t}^{t+n_{o}-1} a_{v o} \cdot x_{v j} \leq h_{o} \quad\left(o \in \mathcal{O} ; t=1, \ldots, T-n_{o}+1\right)
$$

## Nachfrage

$$
\sum_{t=1}^{T} x_{v t}=d_{v}
$$# Optimierungsmodell zum Car Sequencing 

## Modell CAR SEQUENCING

## $h_{o}: n_{o}$-Forderung

Für jede Option o müssen gewisse Mindestabstände eingehalten werden, d. h., in den $n_{o}$ Takten $t, t+1, \ldots, t+n_{o}-1$ dürfen höchstens $h_{o}$ Einheiten der Varianten $v$, die die Option o benötigen, eingelastet werden

$$
\sum_{v \in \mathcal{V}} \sum_{j=t}^{t+n_{o}-1} a_{v o} \cdot x_{v j} \leq h_{o} \quad\left(o \in \mathcal{O} ; t=1, \ldots, T-n_{o}+1\right)
$$

## Nachfrage

$$
\sum_{t=1}^{T} x_{v t}=d_{v} \quad(v \in \mathcal{V})
$$

## Takt

$$
\sum_{v \in \mathcal{V}} x_{v t}=1 \quad(t=1, \ldots, T)
$$# Car Sequencing 

## Beispiel 4 Optionen, 6 Varianten# Beispiel 4 Optionen, 6 Varianten 

Variantenbildung aus verschiedenen Optionen $\left(a_{v o}\right)$ :

| Option $o=$ <br> Variante $v=$ | A | B | C | D |
| :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 0 | 0 | 1 |
| 2 | 1 | 0 | 1 | 0 |
| 3 | 1 | 1 | 0 | 0 |
| 4 | 1 | 1 | 0 | 0 |
| 5 | 0 | 0 | 1 | 0 |
| 6 | 1 | 0 | 0 | 0 |# Beispiel 4 Optionen, 6 Varianten 

Variantenbildung aus verschiedenen Optionen $\left(a_{v o}\right)$ :

| Option $o=$ | A | B | C | D |
| :--: | :--: | :--: | :--: | :--: |
| Variante $v=$ |  |  |  |  |
| 1 | 0 | 0 | 0 | 1 |
| 2 | 1 | 0 | 1 | 0 |
| 3 | 1 | 1 | 0 | 0 |
| 4 | 1 | 1 | 0 | 0 |
| 5 | 0 | 0 | 1 | 0 |
| 6 | 1 | 0 | 0 | 0 |

Bedarfsmengen $\left(d_{v}\right)$ :

| Variante $v=$ | 1 | 2 | 3 | 4 | 5 | 6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bedarf $d_{v}=$ | 4 | 1 | 2 | 2 | 2 | 3 |# Beispiel 4 Optionen, 6 Varianten 

Variantenbildung aus verschiedenen Optionen ( $a_{v o}$ ):

| Option $o=$ | A | B | C | D |
| :--: | :--: | :--: | :--: | :--: |
| Variante $v=$ |  |  |  |  |
| 1 | 0 | 0 | 0 | 1 |
| 2 | 1 | 0 | 1 | 0 |
| 3 | 1 | 1 | 0 | 0 |
| 4 | 1 | 1 | 0 | 0 |
| 5 | 0 | 0 | 1 | 0 |
| 6 | 1 | 0 | 0 | 0 |

Bedarfsmengen $\left(d_{v}\right)$ :

| Variante $v=$ | 1 | 2 | 3 | 4 | 5 | 6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bedarf $d_{v}=$ | 4 | 1 | 2 | 2 | 2 | 3 |

Kapazitätsrestriktionen $\left(h_{o}: n_{o}\right)$ :
$h_{\mathrm{A}}: n_{\mathrm{A}}=2: 3$
$h_{\mathrm{B}}: n_{\mathrm{B}}=2: 4$
$h_{\mathrm{C}}: n_{\mathrm{C}}=3: 5$
$h_{\mathrm{D}}: n_{\mathrm{D}}=2: 6$# Mixed-Model Sequencing# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Was muss festgelegt werden:
... Im wievielten Takt innerhalb einer Schicht soll ein bestimmtes Werkstück eingelastet werden?# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Was muss festgelegt werden - Entscheidungsvariable:
$x_{w t} \in\{0,1\} \ldots$ Takt/Position des $w$-ten Werkstücks

$$
x_{w t}=\left\{\begin{array}{l}
1, \text { wenn Werkstück } w \text { an Position } t, \text { d. h. im } \\
\quad \text { Takt } t, \text { eingelastet wird } \\
0 \text { sonst }
\end{array}\right.
$$# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Was muss festgelegt werden - Entscheidungsvariable:
$x_{w t} \in\{0,1\} \ldots$ Takt/Position des $w$-ten Werkstücks

$$
x_{w t}=\left\{\begin{array}{l}
1, \text { wenn Werkstück } w \text { an Position } t, \text { d. h. im } \\
\text { Takt } t, \text { eingelastet wird } \\
0 \text { sonst }
\end{array}\right.
$$

$o_{m t} \geq 0 \quad \ldots$ Springereinsatzzeit („Overtime") im Takt $t$ an Station $m$# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Was muss festgelegt werden - Entscheidungsvariable:
$x_{w t} \in\{0,1\} \ldots$ Takt/Position des $w$-ten Werkstücks

$$
x_{w t}=\left\{\begin{array}{l}
1, \text { wenn Werkstück } w \text { an Position } t, \text { d. h. im } \\
\text { Takt } t, \text { eingelastet wird } \\
0 \text { sonst }
\end{array}\right.
$$

$o_{m t} \geq 0 \quad \ldots$ Springereinsatzzeit („Overtime") im Takt $t$ an Station $m$
$s_{m t} \geq 0 \quad \ldots$ Startposition der Werker an Station $m$ zu Bearbeitungsbeginn im Takt $t$ (in Zeiteinheiten ab Taktzeitbeginn gemessen)# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben:
... Menge der Bearbeitungsstationen# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$\mathcal{M}$... Menge der Bearbeitungsstationen# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$\mathcal{M}$... Menge der Bearbeitungsstationen
(topologisch sortiert durchnumeriert)# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte
$W$... Anzahl zu bearbeitender Werkstücke# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte
$W$... Anzahl zu bearbeitender Werkstücke; $T=W$# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben - Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte
$W$... Anzahl zu bearbeitender Werkstücke; $T=W$

Gegeben - Daten:# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte
$W$... Anzahl zu bearbeitender Werkstücke; $T=W$

Gegeben — Daten:
$\tau_{w m} \ldots$ Bearbeitungszeit (Stationszeit) des Werkstücks $w$ an Station $m$# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte
$W$... Anzahl zu bearbeitender Werkstücke; $T=W$

Gegeben — Daten:
$\tau_{w m}$... Bearbeitungszeit (Stationszeit) des Werkstücks $w$ an Station $m$
$l_{m} \quad$... Länge der Station $m$ (in Zeiteinheiten)# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte
$W$... Anzahl zu bearbeitender Werkstücke; $T=W$

Gegeben — Daten:
$\tau_{w m}$... Bearbeitungszeit (Stationszeit) des Werkstücks $w$ an Station $m$
$l_{m} \quad$... Länge der Station $m$ (in Zeiteinheiten)
$C \quad$... Taktzeit# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte
$W$... Anzahl zu bearbeitender Werkstücke; $T=W$

Gegeben — Daten:
$\tau_{w m}$... Bearbeitungszeit (Stationszeit) des Werkstücks $w$ an Station $m$
$l_{m} \quad$... Länge der Station $m$ (in Zeiteinheiten)
$C \quad$... Taktzeit; $C \leq l_{m}$
$(m=1, \ldots, M)$# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Minimiere die Summe der benötigten Springereinsatzzeit# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$

## Springereinsatz# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz
Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz
Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$

$$
s_{m t}
$$

$(m=1, \ldots, M ; t=1, \ldots, T)$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t}
$$

Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$

$$
(m=1, \ldots, M ; t=1, \ldots, T)
$$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz
Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t} \leq l_{m}
$$

$$
(m=1, \ldots, M ; t=1, \ldots, T)
$$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz
Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t} \leq l_{m}+o_{m t}
$$

$$
(m=1, \ldots, M ; t=1, \ldots, T)
$$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz
Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t}-o_{m t} \leq l_{m}
$$

$$
(m=1, \ldots, M ; t=1, \ldots, T)
$$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz
Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t}-o_{m t} \leq l_{m}
$$

$$
(m=1, \ldots, M ; t=1, \ldots, T)
$$

Werkerposition beim nächsten Bearbeitungsbeginn

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t}-o_{m t}
$$

$$
(m=1, \ldots, M ; t=1, \ldots, T-1)
$$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz
Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t}-o_{m t} \leq l_{m}
$$

$$
(m=1, \ldots, M ; t=1, \ldots, T)
$$

Werkerposition beim nächsten Bearbeitungsbeginn

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t}-o_{m t}-C
$$

$$
(m=1, \ldots, M ; t=1, \ldots, T-1)
$$# Modell MMS 

Minimiere die Summe der benötigten Springereinsatzzeit

$$
Z=\sum_{m=1}^{M} \sum_{t=1}^{T} o_{m t}
$$

u. B. d. R.:

## Zuordnung

$\sum_{t=1}^{T} x_{w t}=1 \quad(w=1, \ldots, W)$ und $\sum_{w=1}^{W} x_{w t}=1 \quad(t=1, \ldots, T)$
Springereinsatz
Ausgangsposition: $s_{m 1}=0(m=1, \ldots, M)$

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t}-o_{m t} \leq l_{m}
$$

$$
(m=1, \ldots, M ; t=1, \ldots, T)
$$

Werkerposition beim nächsten Bearbeitungsbeginn

$$
s_{m t}+\sum_{w=1}^{W} \tau_{w m} \cdot x_{w t}-o_{m t}-C \leq s_{m, t+1} \quad(m=1, \ldots, M ; t=1, \ldots, T-1)
$$# Optimierungsmodell zum Mixed-Model Sequencing 

Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 |  |  |  |  | Stationslänge $l_{m}$ |
| 2 | 0.3 | 1.5 | 1.5 | 1.7 | 1.5 |
|  | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |# Optimierungsmodell zum Mixed-Model Sequencing 

Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

![img-234.jpeg](img-234.jpeg)# Optimierungsmodell zum Mixed-Model Sequencing 

Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

![img-235.jpeg](img-235.jpeg)# Optimierungsmodell zum Mixed-Model Sequencing 

Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

![img-236.jpeg](img-236.jpeg)# Ein heuristisches Lösungswerfahren zum Mixed-Model Sequencing auf Basis der Vogelschen <br> Approximationsmethode# Eine Heuristik zum Mixed-Model Sequencing 

1. Berechne die Zielfunktionswerte (= Summe der Springereinsatzzeiten) für die Aneinanderreihung von jeweils zwei partiellen Reihenfolgen!
2. Berechne für jede Zeile und Spalte die „Kosten"-Differenzen zwischen der besten und der zweitgünstigsten Reihung!
3. Wähle die opportunitätskostenmaximale Zeile bzw. Spalte und dort die Zelle (partielle Reihenfolge) mit dem besten Zielfunktionswert!

- Bei Indifferenz entscheidet die niedrigste Werkerposition (,, Tiebreaker") am Ende der partiellen Reihenfolge.
- Bei weiterer Indifferenz wählt man die partielle Reihenfolge mit der geringsten Leerzeit, um eine möglichst gleichmäßige Arbeitsbelastung zu erreichen.

4. Gehe zu Schritt 1, solange noch keine vollständige Reihenfolge gebildet worden ist.# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 |  |  |  |  | Stationslänge $l_{m}$ |
| 2 | 0.3 | 1.5 | 1.5 | 1.7 | 1.5 |
|  | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

Summe der Springereinsatzzeiten an beiden Stationen bei folgenden partiellen Einlastungsreihenfolgen (erst Auftrag ..., dann Auftrag ...):

| Auftrag unmittelbar vor Auftrag | 1 | 2 | 3 | 4 | $\Delta$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | - | 0.0 | 0.0 | 0.2 | 0.0 |
| 2 | 0.0 | - | 0.5 | 0.7 | 0.5 |
| 3 | 0.0 | 0.5 | - | 1.2 | 0.5 |
| 4 | 0.2 | 0.7 | 1.2 | - | 0.5 |
| $\Delta$ | 0.0 | 0.5 | 0.5 | 0.5 |  |Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

Summe der Springereinsatzzeiten an beiden Stationen bei folgenden partiellen Einlastungsreihenfolgen (erst Auftrag ..., dann Auftrag ...):

| Auftrag unmittelbar vor Auftrag | 1 | 2 | 3 | 4 | $\Delta$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | - | 0.0 | 0.0 | 0.2 | 0.0 |
| 2 | 0.0 | - | 0.5 | 0.7 | 0.5 |
| 3 | 0.0 | 0.5 | - | 1.2 | 0.5 |
| 4 | 0.2 | 0.7 | 1.2 | - | 0.5 |
| $\Delta$ | 0.0 | 0.5 | 0.5 | 0.5 |  |

(Summe der) Werkerpositionen (bei den opportunitätskostenmaximalen Reihenfolgen und minimalem Springereinsatz (je Zeile/Spalte)):

| Reihenfolge | $2-1$ | $3-1$ | $4-1$ | $1-2$ | $1-3$ | $1-4$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Position | 0.0 | 0.0 | 0.0 | 0.5 | 1.0 | 1.0 |# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

Summe der Springereinsatzzeiten an beiden Stationen bei folgenden partiellen Einlastungsreihenfolgen (erst Auftrag ..., dann Auftrag ...):

| Auftrag unmittelbar vor Auftrag | 2 | 3 | $4-1$ | $\Delta$ |
| :--: | :--: | :--: | :--: | :--: |
| 2 | - | 0.5 | 0.7 | 0.2 |
| 3 | 0.5 | - | 1.2 | 0.7 |
| $4-1$ | 0.2 | 0.2 | - | 0.0 |
| $\Delta$ | 0.3 | 0.3 | 0.5 |  |# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

Summe der Springereinsatzzeiten an beiden Stationen bei folgenden partiellen Einlastungsreihenfolgen (erst Auftrag ..., dann Auftrag ...):
Teilreihenfolge $(3-2)-(4-1)$

| Station $m$ | $t /$ Auftrag $w$ | Springereinsatzzeit $o_{m t}$ | Werkerstartposition $s_{m, t+1}$ |
| :--: | :--: | :--: | :--: |
| 1 | $t=1 / w=3$ | 0.0 | 0.5 |
| 1 | $t=2 / w=2$ | 0.5 | 0.5 |
| 1 | $t=3 / w=4$ | 0.7 | 0.5 |
| 1 | $t=4 / w=1$ | 0.0 | 0.0 |
| 2 | $t=1 / w=3$ | 0.0 | 0.5 |
| 2 | $t=2 / w=2$ | 0.0 | 0.0 |
| 2 | $t=3 / w=4$ | 0.0 | 0.5 |
| 2 | $t=4 / w=1$ | 0.0 | 0.0 |
|  | Summe | 1.2 | 2.5 |# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

Summe der Springereinsatzzeiten an beiden Stationen bei folgenden partiellen Einlastungsreihenfolgen (erst Auftrag ..., dann Auftrag ...):
Teilreihenfolge $(4-1)-(3-2)$

| Station $m$ | $t /$ Auftrag $w$ | Springereinsatzzeit $o_{m t}$ | Werkerstartposition $s_{m, t+1}$ |
| :--: | :--: | :--: | :--: |
| 1 | $t=1 / w=4$ | 0.2 | 0.5 |
| 1 | $t=2 / w=1$ | 0.0 | 0.0 |
| 1 | $t=3 / w=3$ | 0.0 | 0.5 |
| 1 | $t=4 / w=2$ | 0.5 | 0.0 |
| 2 | $t=1 / w=4$ | 0.0 | 0.5 |
| 2 | $t=2 / w=1$ | 0.0 | 0.0 |
| 2 | $t=3 / w=3$ | 0.0 | 0.5 |
| 2 | $t=4 / w=2$ | 0.0 | 0.0 |
|  | Summe | 0.7 | 2.0 |# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

Summe der Springereinsatzzeiten an beiden Stationen bei folgenden partiellen Einlastungsreihenfolgen (erst Auftrag ..., dann Auftrag ...):

| Auftrag |  |  |
| :--: | :--: | :--: |
| unmittelbar vor Auftrag | $3-2$ | $4-1$ |
| $3-2$ | - | 1.2 |
| $4-1$ | 0.7 | - |# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

Summe der Springereinsatzzeiten an beiden Stationen bei folgenden partiellen Einlastungsreihenfolgen (erst Auftrag ..., dann Auftrag ...):

| Auftrag |  |  |
| :--: | :--: | :--: |
| unmittelbar vor Auftrag | $3-2$ | $4-1$ |
| $3-2$ | - | 1.2 |
| $4-1$ | 0.7 | - |

Beste gefundene Lösung:
Reihenfolge $(4-1)-(3-2)$# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

Summe der Springereinsatzzeiten an beiden Stationen bei folgenden partiellen Einlastungsreihenfolgen (erst Auftrag ..., dann Auftrag ...):

| Auftrag |  |  |
| :--: | :--: | :--: |
| unmittelbar vor Auftrag | $3-2$ | $4-1$ |
| $3-2$ | - | 1.2 |
| $4-1$ | 0.7 | - |

Beste gefundene Lösung:
Reihenfolge $4-1-3-2$# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

![img-237.jpeg](img-237.jpeg)# Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$ 

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

![img-238.jpeg](img-238.jpeg)