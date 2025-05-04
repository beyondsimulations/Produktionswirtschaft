# Ablaufplanung (,,Scheduling")# Ablaufplanung: Klassifikationsmerkmale 

$\alpha$ Produktionsprozessstruktur
$\beta$ Auftragszugang
$\beta$ Bearbeitungsprozess
$\gamma$ Zielsetzungen

Notation von Graham, Lawler, Lenstra und Rinnooy Kan
$\alpha|\beta| \gamma$# Ablaufplanung: Problemspezifikation 

## Produktionsprozessstruktur

1 eine Maschine (Single-Machine Scheduling)
Pm mehrere parallele Maschinen (Parallel-Machine Scheduling)
Fm Reihenproduktion (Flow-Shop Scheduling)
Jm Werkstattproduktion (Job-Shop Scheduling)
$\triangleright$ general job shop
$\triangleright$ re-entrant flow
Om Open-Shop Scheduling# Ablaufplanung: Problemspezifikation 

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
$\triangleright$ Leerzeiten# Ablaufplanung: Auftragsbezogene Zielgrößen 

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

$p=1, \ldots, P)$

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
$$# Ablaufplanung: Übergeordnete Zielgrößen 

- Bestand $\Longrightarrow$ Kapitalbindung
- termingerechte Auslieferung $\Longrightarrow$ Kundenservice
- Auslastung $\Longrightarrow$ Kapazitätsnutzung# Littles Gesetz 

mittlerer Bestand = Abgangsrate $\cdot$ mittlere Durchlaufzeit

## „Dilemma der Ablaufplanung" (Gutenberg)

Bei dynamisch-stochastischem Auftragseingang steigt die Durchlaufzeit (und damit der Bestand, s. Littles Gesetz), wenn die Auslastung maximiert werden soll.# Ablaufplanung für nur eine MaschinePlanungssituation:
deterministische Bearbeitungszeiten
Notation der Kurzbeschreibung des jeweils betrachteten Spezialproblems:
1|[Anzahl Aufträge]/[Auftragseingang]|[Zielgröße]# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-0.jpeg](img-0.jpeg)# Beispiel 6 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-1.jpeg](img-1.jpeg)Beispiel 6 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 | A6 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 3 ZE | 1 ZE | 2 ZE | 5 ZE | 4 ZE | 7 ZE |

![img-2.jpeg](img-2.jpeg)

Optimalitätsbedingung: $a_{[1]} \leq a_{[2]} \leq a_{[3]} \leq a_{[4]} \leq a_{[5]} \leq a_{[6]}$
$\Longrightarrow$ Kürzeste-Operationszeit-Regel (KOZ-/SPT-Regel)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-3.jpeg](img-3.jpeg)# 1/P Aufträge/statische Situation/maximale Verspätung 

## Beispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-4.jpeg](img-4.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-5.jpeg](img-5.jpeg)# Beispiel 5 Aufträge 

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-6.jpeg](img-6.jpeg)

Optimalitätsbedingung: $\mathrm{LT}_{[1]} \leq \mathrm{LT}_{[2]} \leq \mathrm{LT}_{[3]} \leq \mathrm{LT}_{[4]} \leq \mathrm{LT}_{[5]}$
$\Longrightarrow$ Liefertermin-Regel# Verfahren von Hodgson (Moore) 

1. Sortiere die Aufträge nach der Lieferterminregel!Speichere die Menge der Aufträge als geordnete Menge $\mathcal{R}$ !
2. Suche den ersten verspäteten Auftrag, Auftrag $\alpha$, in $\mathcal{R}$ ! Gibt es keinen, gehe zu Schritt 5!
3. Entferne aus den Aufträgen vor $\alpha$ den Auftrag mit der längsten Bearbeitungsdauer aus der Menge $\mathcal{R}$ ! Dadurch reduziert sich die Verspätung der Aufträge in $\mathcal{R}$ in maximalem Ausmaß.
4. Wiederhole die Schritte 2 und 3, solange es noch Verspätungen in $\mathcal{R}$ gibt!
5. Gibt es keinen verspäteten Auftrag mehr in $\mathcal{R}$, dann sortiere die Aufträge nach Lieferterminregel! Die aussortierten Aufträge können in beliebiger Reihenfolge, z. B. nach KOZ-Regel, eingeplant werden.Beispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-7.jpeg](img-7.jpeg)

Hodgson-Verfahren, Schritt 1: Einplanung nach Liefertermin-RegelBeispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-8.jpeg](img-8.jpeg)

Hodgson-Verfahren, Schritt 1: Einplanung nach Liefertermin-Regel Hodgson-Verfahren, Schritt 2 und 3: Entfernung von Auftrag A2Beispiel 5 Aufträge

| Auftrag $p$ | A1 | A2 | A3 | A4 | A5 |
| :-- | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 4 ZE | 7 ZE | 1 ZE | 6 ZE | 3 ZE |
| Plantermin $p=\mathrm{LT}_{p}$ | 8 | 12 | 4 | 13 | 14 |

![img-9.jpeg](img-9.jpeg)

Hodgson-Verfahren, Schritt 1: Einplanung nach Liefertermin-Regel Hodgson-Verfahren, Schritt 2 und 3: Entfernung von Auftrag A2 Hodgson-Verfahren, Schritt 5: Einplanung der aussortierten Aufträge# Beispiel 3 Aufträge 

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung:
![img-10.jpeg](img-10.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung:
![img-11.jpeg](img-11.jpeg)# Beispiel 3 Aufträge 

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-12.jpeg](img-12.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KOZ-Regel, keine Verdrängung, Stillstand möglich:
![img-13.jpeg](img-13.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KRZ-Regel, Verdrängung möglich:
![img-14.jpeg](img-14.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

## Beispiel 3 Aufträge

| Auftrag $p$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Bearbeitungszeit $a_{p}$ | 7 | 3 | 2 |
| Auftragseingang $p$ | 0 | 1 | 3 |

KRZ-Regel, Verdrängung möglich, Wiederholung nötig:
![img-15.jpeg](img-15.jpeg)# 1 P Aufträge/dynamisch-deterministische Situation 

Erkenntnisse:

- KOZ/KRZ-Regel minimiert die mittlere Durchlaufzeit
$\Rightarrow$ Planungszeitpunkt und Menge der einzuplanenden Aufträge beeinflussen die Lösungsgüte
$\Rightarrow$ hoher Anteil zu früh fertiggestellter Aufträge
$\Rightarrow$ Aufträge mit langer Bearbeitungszeit bleiben liegen
$\Rightarrow$ hohe Streuung der DurchlaufzeitenDie Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |

![img-16.jpeg](img-16.jpeg)Die Zyklusdauer ist nicht mehr gleich der Summe der Bearbeitungszeiten.

# Das Verfahren von Schrage 

Wähle als nächsten zu bearbeitenden Auftrag aus der Menge der aktuell einplanbaren Aufträge denjenigen mit der längsten Nachlaufzeit!

## Beispiel

(vgl. Küpper/Helber (2004))

| Vorgang $j$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| Vorlaufzeit $_{j}$ | 6 | 0 | 0 |
| Bearbeitungszeit $_{j}$ | 3 | 1 | 2 |
| Nachlaufzeit $_{j}$ | 0 | 9 | 5 |


| 2 | 3 |  | Nachlaun |  | 1 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | # 1.4. Aufträge/dynamisch-stochastische Situation 

Die Produktionsaufträge treffen in zufälligen Abständen ein.
Die Durchlaufzeit eines Auftrags ist eine Zufallsvariable.
Weitere stochastische Einflüsse auf die Durchlaufzeit eines Auftrags $i$ :
$\rightarrow$ stochastische Bearbeitungszeit des Auftrags $i$
$\rightarrow$ stochastische Bearbeitungszeiten der vor $i$ wartenden Aufträge
Verdrängung des Auftrags $i$ zu einem zufälligen Zeitpunkt auf Grund der Ankunft eines wichtigeren Auftrags# Warteschlangendisziplinen 

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
FCFS-Regel vermeidet hohen Anteil liegenbleibender Aufträge# Ablaufplanung für parallele Maschinen# Beispiel 

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
![img-17.jpeg](img-17.jpeg)# Beispiel 

( vgl . Jähn/Pesch (2014))

| Vorgang $j$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Bearbeitungszeit $_{j}$ | 9 | 7 | 6 | 5 | 4 | 3 | 3 | 1 |

## LOZ-Regel

![img-18.jpeg](img-18.jpeg)![img-19.jpeg](img-19.jpeg)# Ablaufplanung für mehrere Produktionsstufen# Identische 

## Bearbeitungsreihenfolgen

(Flow Shop)# Ablaufplanung für zwei Maschinen 

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
| Maschine 2 | 2 | 3 | 8 | 6 | 4 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren
$\square$

Maschine
![img-20.jpeg](img-20.jpeg)
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II
135-6# Beispiel 5 Aufträge 

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
![img-21.jpeg](img-21.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Beispiel 8 Aufträge 

## Bearbeitungszeiten

| Auftrag | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Maschine 1 | 4 | 8 | 7 | 8 | 2 | 1 | 3 | 9 |
| Maschine 2 | 6 | 3 | 6 | 4 | 6 | 5 | 7 | 2 |

Auftragsreihenfolgeplanung nach dem Johnson-Verfahren
![img-22.jpeg](img-22.jpeg)

M1
M2
![img-23.jpeg](img-23.jpeg)# Beispiel 8 Aufträge 

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

Unter der Bedingung

$$
\min \left\{a_{i 1}\right\} \geq \max \left\{a_{i 2}\right\} \text { oder } \min \left\{a_{i 3}\right\} \geq \max \left\{a_{i 2}\right\}
$$

kann das Johnson-Verfahren für einen äquivalenten 2-Maschinen-FlowShop angewendet werden:
![img-24.jpeg](img-24.jpeg)

Gilt o. a. Bedingung nicht, dann liefert diese Vorgehensweise als Heuristik dennoch gute Ergebnisse (Giglio/Wagner).# Job-Shop Scheduling# Job-Shop Scheduling 

Kritische Größen:

- Staueffekte
$\triangleright$ hohe Lagerbestände
$\triangleright$ lange Wartezeiten
$\triangleright$ lange Durchlaufzeiten
- Termineinhaltung
$\triangleright$ Verspätungen
$\triangleright$ TerminabweichungenPrioritätsregeln zum Abbau der Staueffekte
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

## Modell von Karmarkar

Man betrachtet eine Werkstatt als ein M/M/1-Warteschlangensystem:
exponentialverteilte Zwischenankunftszeit von Aufträgen
exponentialverteilte Bearbeitungszeiten
$\rightarrow$ ein Server (eine Maschine)
$\rightarrow$ unbegrenzter Warteraum
$\rightarrow$ FCFS# Zusammenhang zwischen Losgröße und Durchlaufzeit 

## Modell von Karmarkar

Ankunftsrate von Werkstücken: $D$
Losgröße: $Q$
Ankunftsrate von Losen: $\lambda=\frac{D}{Q}$
Produktionsrate: $P$
Rüstzeit: $\tau$
mittlere Bearbeitungszeit eines Loses: $\tau+\frac{Q}{P}$
Bearbeitungsrate von Losen: $\mu=\frac{1}{\tau+\frac{Q}{P}}=\frac{P}{P \cdot \tau+Q}$
Auslastung: $\rho=\frac{\lambda}{\mu}=\frac{\frac{D}{Q}}{\frac{P}{P \cdot \tau+Q}}=\frac{D}{P} \cdot \frac{P \cdot \tau+Q}{Q}=\frac{D}{P} \cdot\left(\frac{P}{Q} \cdot \tau+1\right)=\frac{D \cdot \tau}{Q}+\frac{D}{P}$# Zusammenhang zwischen Losgröße und Durchlaufzeit 

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

$$
D=1.5, \tau=1, P=2
$$

![img-25.jpeg](img-25.jpeg)# Einlastungsplanung bei Variantenfließproduktion![img-26.jpeg](img-26.jpeg)
(Quelle: Günther/Tempelmeier (2005))# Variantenfließproduktion 

![img-27.jpeg](img-27.jpeg)
(Quelle: Günther/Tempelmeier (2005))
(C) Univ.-Prof. Dr. Michael Manitz# Weg-Zeit-Diagramm 

![img-28.jpeg](img-28.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Zeit-Weg-Diagramm 

Idealfall: gleiche Arbeitsbelastung für alle in Höhe der Taktzeit
![img-29.jpeg](img-29.jpeg)# Zeit-Weg-Diagramm 

Idealfall: gleiche Arbeitsbelastung für alle in Höhe der Taktzeit
![img-30.jpeg](img-30.jpeg)# Arbeitsbelastung und Reihenfolge 

## Zeit-Weg-Diagramm

Reihenfolge: A-A-A-B-B-B
![img-31.jpeg](img-31.jpeg)
(C) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Arbeitsbelastung und Reihenfolge 

## Zeit-Weg-Diagramm

Reihenfolge: A-B-A-B-A-B
![img-32.jpeg](img-32.jpeg)Ziel: Glättung der Arbeitsbelastung an den einzelnen Stationen

- Level Scheduling (variantenbezogen-bedarfsorientiert)
$\triangleright$ möglichst gleichmäßige zeitliche Verteilung der einzuplanenden Aus-stattungsvarianten
$\triangleright$ Reduktion von Lagerbeständen
- Car Sequencing (variantenbezogen-kapazitätsorientiert)
$\triangleright$ alternierende Auflage von Varianten mit über- und unterdurchschnittlicher Arbeitsbelastung an den Engpassstationen
$\triangleright$ zulässige Einlastungsreihenfolgen in bezug auf gewisse Abstandsregeln
- Mixed-Model Sequencing (werkstückbezogen-kapazitätsorientiert)
$\triangleright$ optimale Reihenfolge der einzelnen Werkstücke mit möglichst wenig überdurchschnittlicher Arbeitsbelastung an den einzelnen Stationen
$\triangleright$ Reduktion der Taktzeitüberschreitungen# Mixed-Model Sequencing# Optimierungsmodell zum Mixed-Model Sequencing 

## Modell MMS

Was muss festgelegt werden:
... Im wievielten Takt innerhalb einer Schicht soll ein bestimmtes Werkstück eingelastet werden?# Optimierungsmodell zum Mixed-Model Sequencing 

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

Gegeben — Indexmengen:
$M$... Anzahl der Bearbeitungsstationen
$T$... Anzahl Takte
$W$... Anzahl zu bearbeitender Werkstücke; $T=W$

Gegeben — Daten:
$\tau_{w m} \ldots$ Bearbeitungszeit (Stationszeit) des Werkstücks $w$ an Station $m$
$l_{m} \quad \ldots$ Länge der Station $m$ (in Zeiteinheiten)
$C \quad \ldots$ Taktzeit; $C \leq l_{m}$
$(m=1, \ldots, M)$# Modell MMS 

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
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

![img-33.jpeg](img-33.jpeg)# Optimierungsmodell zum Mixed-Model Sequencing 

Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

![img-34.jpeg](img-34.jpeg)# Optimierungsmodell zum Mixed-Model Sequencing 

Beispiel Werkstückbezogene Stationszeiten, Taktzeit $=1$

| Auftrag <br> Station | 1 | 2 | 3 | 4 |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 0.3 | 1.5 | 1.5 | 1.7 | Stationslänge $l_{m}$ |
| 2 | 0.5 | 0.5 | 1.5 | 1.5 | 1.5 |

![img-35.jpeg](img-35.jpeg)