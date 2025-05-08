# Übung 03


## Aufgabe 1: Aggregierte Produktionsplanung

Ein mittelständischer Hersteller von Fahrrädern plant sein
Produktionsprogramm für die kommenden drei Monate (Perioden
$t=1, 2, 3$). Es werden zwei Hauptprodukttypen betrachtet: “Stadtrad
Klassik” (Produkt K) und “Mountainbike Pro” (Produkt M). Das Unternehmen
möchte die Gesamtkosten aus Lagerhaltung und Überstunden minimieren.

**Nachfrage (Stück pro Periode):**

| Produkt | Periode 1 | Periode 2 | Periode 3 |
|---------|-----------|-----------|-----------|
| K       | 100       | 120       | 150       |
| M       | 70        | 80        | 90        |

**Kosten:**

- Lagerkostensatz: 5 EUR/Stück und Periode (für beide Produkte)
- Überstundenkostensatz: 10 EUR/Kapazitätseinheit (personelle Kapazität)

**Kapazitäten**

- Anfangslagerbestand: $L_{K0}=20$ Stück, $L_{M0}=10$ Stück.
- Maximale personelle Kapazität: 250 Einheiten pro Periode.
- Maximale technische Kapazität: 400 Einheiten pro Periode.
- Maximale Zusatzkapazität (Überstunden): 50 Einheiten pro Periode.

**Produktionskoeffizienten (Kapazitätsbedarf pro Stück)**

| Produkt | Personelle Kapazität | Technische Kapazität |
|---------|----------------------|----------------------|
| K       | 1.0                  | 1.5                  |
| M       | 1.2                  | 2.0                  |

**Ihre Aufgaben:**

1.  Zielformulierung: Schreiben Sie die Zielfunktion zur Minimierung der
    Gesamtkosten für die FahrradFreund GmbH explizit auf.

2.  Wichtige Nebenbedingungen formulieren: Formulieren Sie die folgenden
    Nebenbedingungen für die FahrradFreund GmbH:

    1)  Lagerbilanzgleichung für das Stadtrad Klassik (Produkt K) in
        Periode 2.
    2)  Personelle Kapazitätsbeschränkung in Periode 1.
    3)  Technische Kapazitätsbeschränkung in Periode 3.

3.  Bewertung eines Teil-Produktionsplans: Angenommen, die
    Produktionsleitung schlägt für Periode 1 folgende Produktionsmengen
    vor:

    - 90 Stück (Stadtrad Klassik)
    - 70 Stück (Mountainbike Pro)

    Berechnen Sie für Periode 1:

    1)  Den Lagerbestand für beide Produkte am Ende von Periode 1.
    2)  Den Bedarf an personeller Kapazität. Ist die reguläre personelle
        Kapazität ausreichend oder werden Überstunden benötigt? Wenn ja,
        wie viele und was sind die Kosten dafür?
    3)  Den Bedarf an technischer Kapazität. Ist die technische
        Kapazität ausreichend?
    4)  Die gesamten Lagerkosten, die für die in Periode 1 gehaltenen
        Endbestände anfallen.

## Aufgabe 2: Erweiterung um Make-or-Buy-Entscheidungen

Aufbauend auf Aufgabe 1 soll das Planungsmodell nun um die Möglichkeit
erweitert werden, Fahrräder nicht nur selbst zu produzieren, sondern
auch von einem externen Lieferanten zu beziehen.

**Zusätzliche Daten für Make-or-Buy:**

Die Kosten für den Fremdbezug der Fahrräder betragen:

- Stadtrad Klassik (Produkt K): $c_K^B = 85$ EUR/Stück
- Mountainbike Pro (Produkt M): $c_M^B = 100$ EUR/Stück

Alle anderen Daten (Nachfrage, Lagerkosten, Kapazitäten,
Produktionskoeffizienten, Anfangslagerbestände etc.) entsprechen denen
aus Aufgabe 1.

**Ihre Aufgaben:**

1.  Modellformulierung (Erweiterung):
    1)  Definieren Sie die neue(n) Entscheidungsvariable(n), die für die
        Berücksichtigung von Fremdbezugsmengen notwendig ist/sind.
    2)  Formulieren Sie die erweiterte Zielfunktion zur Minimierung der
        Gesamtkosten unter Einbeziehung der Fremdbezugskosten. Die
        Gesamtkosten umfassen nun Lagerhaltungs-, Überstunden- und
        Fremdbezugskosten.
    3)  Wie muss die Lagerbilanzgleichung (Nachfragebefriedigung)
        angepasst werden, um die Fremdbezugsmengen zu berücksichtigen?
        Formulieren Sie die allgemeine, angepasste Lagerbilanzgleichung
        für ein Produkt $k$ in einer Periode $t$.
2.  Bewertung eines kombinierten Produktions- und Bezugsplans für
    Periode 1: Angenommen, die Produktionsleitung schlägt für Periode 1
    folgenden kombinierten Plan vor:
    - Eigenfertigung Stadtrad Klassik ($x_{K1}$): 50 Stück
    - Fremdbezug Stadtrad Klassik ($B_{K1}$): 50 Stück
    - Eigenfertigung Mountainbike Pro ($x_{M1}$): 40 Stück
    - Fremdbezug Mountainbike Pro ($B_{M1}$): 30 Stück

    Berechnen Sie für Periode 1 (unter Verwendung der relevanten Daten
    aus Aufgabe 1 und den neuen Fremdbezugskosten):
    1)  Die Lagerbestände für beide Produkte (K und M) am Ende von
        Periode 1.
    2)  Den Bedarf an personeller Kapazität allein für die
        Eigenfertigung. Ist die reguläre personelle Kapazität (250
        Einheiten) ausreichend oder werden Überstunden benötigt? Wenn
        ja, wie viele Einheiten Überstunden fallen an und was sind die
        Kosten dafür?
    3)  Den Bedarf an technischer Kapazität allein für die
        Eigenfertigung. Ist die technische Kapazität ausreichend?
    4)  Die gesamten Kosten für den Fremdbezug in Periode 1.
    5)  Die gesamten relevanten Kosten gemäß diesem Plan.
