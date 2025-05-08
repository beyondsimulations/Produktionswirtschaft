# Übung 05


## Aufgabe 1: Optimierung der Montage

Cyber Systems steht vor der Herausforderung, die Montage ihrer neuesten
Endoskelett-Arme zu optimieren. In der Endmontage gibt es eine einzelne
Station, die für die finale Qualitätsprüfung und Kalibrierung zuständig
ist. Für eine Charge von 6 Armen sind die Bearbeitungszeiten (in
Stunden) für diese Station bekannt. Die Aufträge sind in der Reihenfolge
ihres Eintreffens (FCFS) nummeriert.

| Auftrag (Arm-ID) | Bearbeitungszeit $a_p$ (Stunden) |
|------------------|----------------------------------|
| A001             | 3                                |
| A002             | 5                                |
| A003             | 2                                |
| A004             | 8                                |
| A005             | 4                                |
| A006             | 6                                |

**Ihre Aufgaben:**

1.  Ermitteln Sie die Auftragsreihenfolge nach der FCFS-Regel (First
    Come, First Served). Berechnen Sie für diese Reihenfolge:
    - Den Fertigstellungszeitpunkt $F_p$ für jeden Auftrag.
    - Die Durchlaufzeit $D_p$ für jeden Auftrag (da alle Aufträge zum
      Zeitpunkt 0 eintreffen, gilt $D_p = F_p$).
    - Die mittlere Durchlaufzeit $\bar{D}$.
2.  Ermitteln Sie die Auftragsreihenfolge nach der KOZ-Regel (Kürzeste
    Operationszeit-Regel, auch SPT-Regel). Berechnen Sie für diese
    Reihenfolge ebenfalls $F_p$, $D_p$ und $\bar{D}$.
3.  Vergleichen Sie die Ergebnisse der FCFS- und KOZ-Regel. Welche Regel
    führt zu einer geringeren mittleren Durchlaufzeit?
4.  Diskutieren Sie kurz, warum die KOZ-Regel in Bezug auf die mittlere
    Durchlaufzeit optimal ist, aber welche potenziellen Nachteile sie
    haben könnte.

## Aufgabe 2: Einhaltung von Produktionsfristen

Wey Corp. steht unter Druck, kritische Navigationskomponenten für ihre
nächste Generation von Frachtern der “Nostromos”-Klasse zu fertigen.
Jeder Komponententyp durchläuft eine spezielle Endmontage- und
Teststation. Für die aktuelle Produktionswoche liegen fünf dringende
Aufträge vor, jeweils mit bekannter Bearbeitungszeit an dieser Station
und einem festen Auslieferungstermin (Plantermin). Das Management möchte
die Anzahl der verspäteten Aufträge minimieren. Alle Aufträge sind zu
Beginn der Woche (Zeitpunkt 0) verfügbar.

| Auftrag (Komponente) | Bearbeitungszeit $a_p$ (Tage) | Plantermin $LT_p$ (Tag) |
|----------------------|-------------------------------|-------------------------|
| C01                  | 3                             | 7                       |
| C02                  | 5                             | 10                      |
| C03                  | 2                             | 5                       |
| C04                  | 6                             | 12                      |
| C05                  | 4                             | 8                       |

**Ihre Aufgaben:**

1.  Sortieren Sie die Aufträge zunächst nach der Liefertermin-Regel
    (EDD - Earliest Due Date). Erstellen Sie einen Plan und ermitteln
    Sie für jeden Auftrag den Fertigstellungszeitpunkt $F_p$ und die
    Verspätung $V_p = \max(0, F_p - LT_p)$. Wie viele Aufträge sind
    verspätet?
2.  Wenden Sie nun das\*Hodgson-Verfahren an, um die Anzahl der
    verspäteten Aufträge zu minimieren.
3.  Erstellen Sie den finalen Ablaufplan. Berechnen Sie für diesen Plan:
    - Den Fertigstellungszeitpunkt $F_p$ für jeden Auftrag.
    - Die Verspätung $V_p$ für jeden Auftrag.
    - Die Gesamtzahl der verspäteten Aufträge.
    - Die maximale Verspätung.
4.  Vergleichen Sie das Ergebnis des Hodgson-Verfahrens mit dem der
    reinen Liefertermin-Regel hinsichtlich der Anzahl verspäteter
    Aufträge.

## Aufgabe 3: Produktionsoptimierung

Johnson-Industries arbeitet an der Fertigung von Schlüsselkomponenten
für ein neues, fortschrittliches Verteidigungssystem, Projekt “Aegis”.
Jede Komponente muss zwei Hauptproduktionsstufen durchlaufen: Zuerst
eine Präzisionsbearbeitung auf Maschine A und anschließend eine komplexe
Montage auf Maschine B. Die Aufträge können nicht überholt werden und
die Reihenfolge der Bearbeitung ist auf beiden Maschinen gleich (Flow
Shop). Ziel ist es, die Gesamtfertigungszeit für alle anstehenden
Komponenten (den Makespan) zu minimieren.

Für die anstehende Produktionscharge sind die Bearbeitungszeiten (in
Stunden) für fünf Komponenten bekannt:

| Komponente (ID) | Bearbeitungszeit Maschine A (Stunden) | Bearbeitungszeit Maschine B (Stunden) |
|----|----|----|
| ARC-01 | 5 | 2 |
| REP-02 | 1 | 6 |
| UNI-03 | 9 | 7 |
| THR-04 | 3 | 8 |
| STA-05 | 10 | 4 |

**Ihre Aufgaben:**

1.  Wenden Sie den **Johnson-Algorithmus** an, um die optimale
    Auftragsreihenfolge zu bestimmen, die den Makespan minimiert.
    Dokumentieren Sie Ihre Schritte zur Herleitung der Reihenfolge.
    Geben Sie die finale, optimale Auftragsreihenfolge an.
2.  Erstellen Sie einen detaillierten Belegungsplan (Gantt-Diagramm) für
    die ermittelte Reihenfolge. Zeichnen Sie die Belegung für Maschine A
    und Maschine B.
3.  Berechnen Sie den minimalen Makespan (Gesamtfertigungszeit) für
    diese Auftragscharge.
