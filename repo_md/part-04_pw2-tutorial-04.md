# Übung 04


## Aufgabe 1: Montageplanung

Die “Fahrzeugfertigung Zwickau GmbH” ist ein traditionsreicher Standort
im Automobilbau und hat sich auf die Produktion von Komponenten und die
Endmontage von Elektrofahrzeugen spezialisiert. Für die Einführung einer
neuen Montagelinie zur Fertigung von Batteriemodulen für das Modell
“Saxon-E” müssen die einzelnen Arbeitsschritte genau geplant werden. Das
Projektmanagement-Team hat die folgende Liste von Arbeitsgängen (AG),
deren Dauer in Stunden (Std.) und die direkten Vorgänger identifiziert:

| Arbeitsgang | Beschreibung | Dauer (Std.) | Direkte Vorgänger |
|----|----|----|----|
| A | Materialbereitstellung Rahmen | 3 | \- |
| B | Vormontage Zellhalterungen | 5 | A |
| C | Einbau Zellhalterungen in Rahmen | 4 | B |
| D | Materialbereitstellung Elektronik | 2 | \- |
| E | Vormontage Steuerungseinheit | 6 | D |
| F | Integration Steuerungseinheit | 3 | C, E |
| G | Qualitätsprüfung & Endverschluss | 2 | F |

Der Projektstart (Beginn von A und D) ist zum Zeitpunkt 0. Der
spätestzulässige Fertigstellungstermin für den gesamten Prozess (Ende
von G) ist Stunde 25.

**Ihre Aufgaben:**

1.  Erstellen Sie ein Netzplan-Diagramm für dieses Projekt.
2.  Führen Sie eine Vorwärtsrechnung durch, um die frühestmöglichen
    Anfangszeitpunkte (FAZ) und Endzeitpunkte (FEZ) für jeden
    Arbeitsgang zu bestimmen.
3.  Führen Sie eine Rückwärtsrechnung durch, um die spätestzulässigen
    Anfangszeitpunkte (SAZ) und Endzeitpunkte (SEZ) für jeden
    Arbeitsgang zu bestimmen. Gehen Sie davon aus, dass der FEZ des
    letzten Arbeitsgangs (G) dem spätestzulässigen Projektendtermin
    entspricht, falls er diesen nicht überschreitet. Andernfalls ist der
    spätestzulässige Endtermin des Projekts maßgebend für SEZ(G).
4.  Berechnen Sie die Gesamtpufferzeit (GP) für jeden Arbeitsgang.
5.  Identifizieren Sie den kritischen Weg im Projekt.

## Aufgabe 2: Kapazitätsabgleich

Die “Duisburg Flugzeugwerke GmbH” in Duisburg ist spezialisiert auf die
Umrüstung von Passagierflugzeugen in Frachtflugzeuge (P2F - Passenger to
Freighter). Bei der Umrüstung eines A320-Flugzeugs müssen mehrere neue
Bodenstrukturelemente im Frachtraum installiert werden. Diese Arbeiten
erfordern den Einsatz einer speziellen, hochpräzisen mobilen Nietanlage,
von der im Hangar für dieses Projekt aktuell nur **eine** Einheit zur
Verfügung steht (Kapazität = 1).

Das Projektmanagement-Team hat folgende Arbeitsgänge (AG), deren Dauer
in Tagen, die direkten Vorgänger und den Bedarf an der mobilen
Nietanlage (NA) identifiziert:

| AG | Beschreibung | Dauer (Tage) | Direkte Vorgänger | Benötigt Nietanlage (NA=1) |
|----|----|----|----|----|
| A | Vorbereitung Sektion 1 | 2 | \- | Nein |
| B | Vorbereitung Sektion 2 | 1 | \- | Nein |
| C | Nietarbeiten Sektion 1 | 3 | A | Ja |
| D | Nietarbeiten Sektion 2 | 4 | B | Ja |
| E | Montage Hilfsstruktur | 2 | \- | Nein |
| F | Finale Niet-Verbindung | 3 | C, D, E | Ja |
| G | Inspektion & Abschluss | 1 | F | Nein |

Projektstart ist zum Zeitpunkt 0.

**Ihre Aufgaben:**

1.  Durchlaufterminierung (ohne Kapazitätsbeschränkung):
    1.  Bestimmen Sie die frühestmöglichen Anfangs- (FAZ) und
        Endzeitpunkte (FEZ) für alle Arbeitsgänge.
    2.  Bestimmen Sie die spätestzulässigen Anfangs- (SAZ) und
        Endzeitpunkte (SEZ) für alle Arbeitsgänge. Nehmen Sie für die
        Rückwärtsrechnung an, dass SEZ(G) = FEZ(G) ist, um den
        kritischen Pfad zu identifizieren.
    3.  Berechnen Sie die Gesamtpufferzeit (GP) und identifizieren Sie
        den/die kritischen Pfad(e).
    4.  Wie lange dauert das Projekt minimal ohne Kapazitätsengpässe?
2.  Kapazitätsorientierte Planung (mit Nietanlage Kapazität = 1):
    1.  Identifizieren Sie die Arbeitsgänge, die die Nietanlage
        benötigen.
    2.  Erstellen Sie einen neuen Zeitplan (Start- und Endtermine für
        alle Arbeitsgänge), der die Kapazitätsbeschränkung der
        Nietanlage (maximal ein Arbeitsgang gleichzeitig)
        berücksichtigt. Versuchen Sie, die Arbeitsgänge so auf der
        Nietanlage einzuplanen, dass die neue Gesamtprojektdauer
        minimiert wird. Verwenden Sie die FAZ-Werte aus der
        unbeschränkten Planung als eine mögliche Priorität (frühester
        Start zuerst). Bei Gleichheit kann die Dauer oder eine andere
        logische Überlegung entscheiden.
    3.  Stellen Sie den Belegungsplan der Nietanlage und den
        resultierenden Projektplan skizzenhaft dar (z.B. als einfache
        Zeitachse oder Tabelle).
    4.  Wie lange dauert das Projekt nun unter Berücksichtigung des
        Engpasses? Was ist der neue kritische Pfad?
