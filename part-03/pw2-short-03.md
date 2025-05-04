# Produktionsprogrammplanung# Aggregierte Gesamtplanung Supply Network Planning# Aggregierte Gesamtplanung - Supply Network Planning 

Fokus auf das gesamte Produktprogramm (in ausreichend aggregierter Form) und die jeweiligen Produktionsstätten mit ihren logistischen Verflechtungen
> unternehmensweite (standort- und funktionsübergreifende) Koordination der erlös- und kostenwirksamen Entscheidungen für einen mittelfristigen Zeitraum

- Abstimmung der Vorstellungen des Absatz-, Beschaffungs- und Personalbereichs mit den Möglichkeiten und Erfordernissen der Produktion und der Logistik
- Berücksichtigung von
$\triangleright$ langfristigen Marktrends, konjunkturellen Schwankungen, mittelfristigen Absatzprognosen
$\triangleright$ internen Ersatzkapazitäten
$\triangleright$ externen Beschaffungsmöglichkeiten
$\triangleright$ Beschäftigungsschwankungen, Arbeitszeitflexibilisierung# Aggregierte Gesamtplanung - Supply Network Planning 

## Synchronisation

![img-0.jpeg](img-0.jpeg)

Nachfrage# Aggregierte Gesamtplanung - Supply Network Planning 

## Synchronisation

![img-1.jpeg](img-1.jpeg)

Nachfrage
Produktion# Aggregierte Gesamtplanung - Supply Network Planning 

## Synchronisation

![img-2.jpeg](img-2.jpeg)

Nachfrage
Produktion# Aggregierte Gesamtplanung - Supply Network Planning 

## Synchronisation

![img-3.jpeg](img-3.jpeg)

Nachfrage
Produktion# Aggregierte Gesamtplanung - Supply Network Planning 

## Synchronisation

![img-4.jpeg](img-4.jpeg)

Nachfrage
Produktion# Aggregierte Gesamtplanung - Supply Network Planning 

## Synchronisation

![img-5.jpeg](img-5.jpeg)

Nachfrage
Produktion# Bewegierte Gesamtplanung - Supply Network Planning 

## Emanzipation

![img-6.jpeg](img-6.jpeg)

Nachfrage# Bewegierte Gesamtplanung - Supply Network Planning 

## Emanzipation

![img-7.jpeg](img-7.jpeg)

Nachfrage
Produktion# Bewegierte Gesamtplanung - Supply Network Planning 

## Emanzipation

![img-8.jpeg](img-8.jpeg)

Nachfrage
Produktion# Bewegierte Gesamtplanung - Supply Network Planning 

## Emanzipation

![img-9.jpeg](img-9.jpeg)

Nachfrage
Produktion# Bewegierte Gesamtplanung - Supply Network Planning 

## Emanzipation

![img-10.jpeg](img-10.jpeg)

Nachfrage
Produktion# Bewegierte Gesamtplanung - Supply Network Planning 

## Emanzipation

![img-11.jpeg](img-11.jpeg)

Nachfrage
Produktion# Aggregierte Gesamtplanung - Supply Network Planning 

## Optmimale Lösung

![img-12.jpeg](img-12.jpeg)

Nachfrage
ProduktionPlanungsproblem bei gegebenen Nachfrageschwankungen:
Ziel:
$\triangleright$ kostenminimale Glättung der Kapazitätsnutzung im Zeitablauf (= „Beschäftigungsglättung")
$\triangleright$ Aufstellen produktionsstättenbezogener Produktionsprogramme
Entscheidungsvariablen (primär): Produktionsmengen, Transportmengen, Beschaffungsmengen
weitere Maßnahmen (sekundäre Entscheidungsvariablen):
$\triangleright$ Verteilung der Produktionsmengen auf verschiedene Standorte
$\triangleright$ saisonbedingte Überstunden, Sonderschichten, Freischichten, Betriebsferien, Kurzarbeit
$\triangleright$ Stillegung von Betriebseinheiten, Personalbestandsanpassung
$\triangleright$ Fremdvergabe von Aufträgen, Lohnfertigung
weitere Variablen: Lagerbestände, Fehlmengen# Entscheidungsrelevante Kosten 

- variable Produktionskosten
- variable Beschaffungskosten
- Transportkosten
- Produktionsniveauänderungskosten
- Lagerkosten (Kapitalbindung)
- Lagerbetriebskosten
- Fehlmengenkosten# Aggregierte Gesamtplanung - Supply Network Planning 

Planungsproblem in einer funktionsübergreifenden Perspektive:
Einsatz des absatzpolitischen Instrumentariums zur Steuerung der Nachfrage (Anheizen in schwachen Perioden, Drosselung in nachfragestarken Perioden, Verlagerung von Nachfragemengen)

- Portfoliobildung durch Produktpolitik# Modelle zur Beschäftigungsglättung Master Planning# Einstufige Ansätze# Grundmodell: Eine Fabrik![img-13.jpeg](img-13.jpeg)# Beschäftigungsglättung: Grundmodell AGGRPLAN 

Annahmen:
$>1$ Fabrik
> mehrere (End-)Produktgruppen („Produkttypen")

- Planungshorizont: T Perioden [Wochen/Monate/Quartale]
produkt- und periodenspezifische Nachfragemengen
(keine explizite Modellierung der Nachfrager; der Distributionsprozess bleibt daher außerhalb der Betrachtung)
> Zielfunktion: Lagerkosten, Überstundenkosten# Beschäftigungsglättung: Grundmodell AGGRPLAN 

## Indexmengen:

$\rightarrow \mathcal{K} \ldots$ die Menge der betrachteten Produkttypen
Variable:
$x_{k t} \ldots$ die Produktionsmenge für Produkt $k$ in Periode $t$
$L_{k t} \ldots$ der Lagerbestand für Produkt $k$ in Periode $t$
$U_{t} \ldots$ die einzuplandende Zusatzkapazität (Überstunden) in Periode $t$
Daten:
$d_{k t} \ldots$ die Nachfragemenge für Produkt $k$ in Periode $t$
$f_{k}^{\mathrm{P}} \ldots$ Produktionskoeffizient in bezug auf die personelle Kapazität
$f_{k}^{\mathrm{T}} \ldots$ Produktionskoeffizient in bezug auf die technische Kapazität
$b_{t}^{\mathrm{T}} \ldots$ die maximale technische Kapazität in Periode $t$
$b_{t}^{\mathrm{P}} \ldots$ die maximale personelle Kapazität in Periode $t$
$U_{t}^{\max } \ldots$ die maximale Zusatzkapazität in Periode $t$Zielfunktionskoeffizienten:
$h_{k} \ldots$ Lagerkostensatz für Produkt $k$ (GE pro ME und ZE)
$u_{t} \ldots$ Überstundenzuschlagssatz in Periode $t$ (GE pro Kapazitätseinheit)Minimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} h_{k} \cdot L_{k t}+\sum_{t=1}^{T} u_{t} \cdot U_{t}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

für alle $k \in \mathcal{K}$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{T}} \cdot x_{k t} \leq b_{t}^{\mathrm{T}}
$$

für alle $t=1,2, \ldots, T$
für alle $t=1,2, \ldots, T$
Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t} \leq U_{t}^{\max }
$$

für alle $t=1,2, \ldots, T$# Beispiel II 3 Produkte, 12 Perioden 

Produktspezifische Daten:

| Produkt $k$ | 1 | 2 | 3 |
| :--: | :--: | :--: | :--: |
| $h_{k}$ | 5.0 | 5.0 | 5.0 |
| $f_{k}^{\mathrm{P}}$ | 1.0 | 0.5 | 0.8 |
| $f_{k}^{\mathrm{T}}$ | 0.5 | 1.0 | 1.2 |
| $L_{k}^{(0)}$ | 36 | 20 | 10 |

Periodenspezifische Daten:

| Periode $t$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $d_{1 t}$ | 100 | 90 | 60 | 150 | 10 | 50 | 100 | 250 | 60 | 40 | 100 | 180 |
| $d_{2 t}$ | 200 | 190 | 210 | 200 | 150 | 120 | 100 | 280 | 90 | 50 | 200 | 250 |
| $d_{3 t}$ | 10 | 140 | 10 | 150 | 100 | 200 | 90 | 50 | 190 | 80 | 90 | 150 |
| $u_{t}$ | 6.0 |  |  |  |  |  |  |  |  |  |  |  |
| $b_{t}^{\mathrm{P}}$ | 260 |  |  |  |  |  |  |  |  |  |  |  |
| $U_{t}^{\max }$ | 100 |  |  |  |  |  |  |  |  |  |  |  |
| $b_{t}^{\mathrm{T}}$ | 500 |  |  |  |  |  |  |  |  |  |  |  |

[^0]
[^0]:    (c) Univ.-Prof. Dr. Michael Manitz

    Produktionswirtschaft II# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung:

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 230.5 | 500 | 191 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 295.5 | 500 | 260 | 260 | 0 | 100 |
| 4 | 411.5 | 500 | 260 | 260 | 23 | 100 |
| 5 | 280.0 | 500 | 175 | 260 | 0 | 100 |
| 6 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 7 | 293.0 | 500 | 260 | 260 | 32 | 100 |
| 8 | 430.0 | 500 | 260 | 260 | 100 | 100 |
| 9 | 348.0 | 500 | 257 | 260 | 0 | 100 |
| 10 | 204.5 | 500 | 206 | 260 | 0 | 100 |
| 11 | 352.0 | 500 | 260 | 260 | 0 | 100 |
| 12 | 487.5 | 500 | 260 | 260 | 100 | 100 |# Modellerweiterung: <br> Bestandsrestriktionen# Beschäftigungsglättung: Bestandsrestriktionen 

## MERGEAJÖR

(©) Univ.-Prof. Dr. Michael Manitz# Beschäftigungsglättung: Bestandsrestriktionen 

## Annahmen:

-     - wie Grundmodell -
produktbezogene Mindestbestände

$$
L_{k t} \geq L_{k t}^{\min }
$$

$$
(k \in \mathcal{K}, t=1,2, \ldots, T)
$$

maximaler Gesamtbestand

$$
\sum_{k \in \mathcal{K}} L_{k t} \leq L_{t}^{\max }
$$

$$
(t=1,2, \ldots, T)
$$# Beschäftigungsglättung: Grundmodell AGGRPLAN 

## Beispiel II 3 Produkte, 12 Perioden

$L_{\max }=70$# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (ohne Bestandsrestriktionen):

| Periode $t$ | $d_{1 t}$ | $x_{1 t}$ | $L_{1 t}$ | $d_{2 t}$ | $x_{2 t}$ | $L_{2 t}$ | $d_{3 t}$ | $x_{3 t}$ | $L_{3 t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  |  | 36 |  |  | 20 |  |  | 10 |
| 1 | 100 | 101 | 37 | 200 | 180 | 0 | 10 | 0 | 0 |
| 2 | 90 | 53 | 0 | 190 | 190 | 0 | 140 | 140 | 0 |
| 3 | 60 | 147 | 87 | 210 | 210 | 0 | 10 | 10 | 0 |
| 4 | 150 | 63 | 0 | 200 | 200 | 0 | 150 | 150 | 0 |
| 5 | 10 | 20 | 10 | 150 | 150 | 0 | 100 | 100 | 0 |
| 6 | 50 | 40 | 0 | 120 | 120 | 0 | 200 | 200 | 0 |
| 7 | 100 | 170 | 70 | 100 | 100 | 0 | 90 | 90 | 0 |
| 8 | 250 | 180 | 0 | 280 | 280 | 0 | 50 | 50 | 0 |
| 9 | 60 | 60 | 0 | 90 | 90 | 0 | 190 | 190 | 0 |
| 10 | 40 | 117 | 77 | 50 | 50 | 0 | 80 | 80 | 0 |
| 11 | 100 | 88 | 65 | 200 | 200 | 0 | 90 | 90 | 0 |
| 12 | 180 | 115 | 0 | 250 | 250 | 0 | 150 | 150 | 0 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (mit Bestandsrestriktionen):

| Periode $t$ | $d_{1 t}$ | $x_{1 t}$ | $L_{1 t}$ | $d_{2 t}$ | $x_{2 t}$ | $L_{2 t}$ | $d_{3 t}$ | $x_{3 t}$ | $L_{3 t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  |  | 36 |  |  | 20 |  |  | 10 |
| 1 | 100 | 101 | 37 | 200 | 180 | 0 | 10 | 0 | 0 |
| 2 | 90 | 53 | 0 | 190 | 190 | 0 | 140 | 140 | 0 |
| 3 | 60 | 130 | 70 | 210 | 210 | 0 | 10 | 10 | 0 |
| 4 | 150 | 80 | 0 | 200 | 200 | 0 | 150 | 150 | 0 |
| 5 | 10 | 20 | 10 | 150 | 150 | 0 | 100 | 100 | 0 |
| 6 | 50 | 40 | 0 | 120 | 120 | 0 | 200 | 200 | 0 |
| 7 | 100 | 170 | 70 | 100 | 100 | 0 | 90 | 90 | 0 |
| 8 | 250 | 180 | 0 | 280 | 280 | 0 | 50 | 50 | 0 |
| 9 | 60 | 60 | 0 | 90 | 90 | 0 | 190 | 190 | 0 |
| 10 | 40 | 110 | 70 | 50 | 50 | 0 | 80 | 80 | 0 |
| 11 | 100 | 95 | 65 | 200 | 200 | 0 | 90 | 90 | 0 |
| 12 | 180 | 115 | 0 | 250 | 250 | 0 | 150 | 150 | 0 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (ohne Bestandsrestriktionen):

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 230.5 | 500 | 191 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 295.5 | 500 | 260 | 260 | 0 | 100 |
| 4 | 411.5 | 500 | 260 | 260 | 23 | 100 |
| 5 | 280.0 | 500 | 175 | 260 | 0 | 100 |
| 6 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 7 | 293.0 | 500 | 260 | 260 | 32 | 100 |
| 8 | 430.0 | 500 | 260 | 260 | 100 | 100 |
| 9 | 348.0 | 500 | 257 | 260 | 0 | 100 |
| 10 | 204.5 | 500 | 206 | 260 | 0 | 100 |
| 11 | 352.0 | 500 | 260 | 260 | 0 | 100 |
| 12 | 487.5 | 500 | 260 | 260 | 100 | 100 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (mit Bestandsrestriktionen):

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 230.5 | 500 | 191 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 287.0 | 500 | 243 | 260 | 0 | 100 |
| 4 | 420.0 | 500 | 260 | 260 | 40 | 100 |
| 5 | 280.0 | 500 | 175 | 260 | 0 | 100 |
| 6 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 7 | 293.0 | 500 | 260 | 260 | 32 | 100 |
| 8 | 430.0 | 500 | 260 | 260 | 100 | 100 |
| 9 | 348.0 | 500 | 257 | 260 | 0 | 100 |
| 10 | 201.0 | 500 | 199 | 260 | 0 | 100 |
| 11 | 355.5 | 500 | 260 | 260 | 7 | 100 |
| 12 | 487.5 | 500 | 260 | 260 | 100 | 100 |# Modellerweiterung: 

## Mindestzusatzkapazität

(Diskretisierung)# Beschäftigungsglättung: Mindestzusatzkapazität 

## Annahmen:

-     - wie Grundmodell -
- $\gamma_{t}:=\left\{\begin{array}{l}1, \text { wenn in } t \text { Überstunden eingeplant werden } \\ 0 \text { sonst }\end{array} \quad(t=1,2, \ldots, T)\right.$
- Modifikation Grundmodell -
maximale Zusatzkapazität in Periode $t$
$U_{t} \leq U_{t}^{\max } \cdot \gamma_{t} \quad(t=1,2, \ldots, T)$
Wenn Zusatzkapazität, dann mindestens $U_{t}^{\min }$ :
$U_{t} \geq U_{t}^{\min } \cdot \gamma_{t} \quad(t=1,2, \ldots, T)$# Beschäftigungsglättung: Grundmodell AGGRPLAN 

## Beispiel II 3 Produkte, 12 Perioden

$L_{\max }=70$
$U_{\min }=50$# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (ohne Mindestzusatzkapazität):

| Periode $t$ | $d_{1 t}$ | $x_{1 t}$ | $L_{1 t}$ | $d_{2 t}$ | $x_{2 t}$ | $L_{2 t}$ | $d_{3 t}$ | $x_{3 t}$ | $L_{3 t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  |  | 36 |  |  | 20 |  |  | 10 |
| 1 | 100 | 101 | 37 | 200 | 180 | 0 | 10 | 0 | 0 |
| 2 | 90 | 53 | 0 | 190 | 190 | 0 | 140 | 140 | 0 |
| 3 | 60 | 130 | 70 | 210 | 210 | 0 | 10 | 10 | 0 |
| 4 | 150 | 80 | 0 | 200 | 200 | 0 | 150 | 150 | 0 |
| 5 | 10 | 20 | 10 | 150 | 150 | 0 | 100 | 100 | 0 |
| 6 | 50 | 40 | 0 | 120 | 120 | 0 | 200 | 200 | 0 |
| 7 | 100 | 170 | 70 | 100 | 100 | 0 | 90 | 90 | 0 |
| 8 | 250 | 180 | 0 | 280 | 280 | 0 | 50 | 50 | 0 |
| 9 | 60 | 60 | 0 | 90 | 90 | 0 | 190 | 190 | 0 |
| 10 | 40 | 110 | 70 | 50 | 50 | 0 | 80 | 80 | 0 |
| 11 | 100 | 95 | 65 | 200 | 200 | 0 | 90 | 90 | 0 |
| 12 | 180 | 115 | 0 | 250 | 250 | 0 | 150 | 150 | 0 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (mit Mindestzusatzkapazität):

| Periode $t$ | $d_{1 t}$ | $x_{1 t}$ | $L_{1 t}$ | $d_{2 t}$ | $x_{2 t}$ | $L_{2 t}$ | $d_{3 t}$ | $x_{3 t}$ | $L_{3 t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  |  | 36 |  |  | 20 |  |  | 10 |
| 1 | 100 | 101 | 37 | 200 | 180 | 0 | 10 | 0 | 0 |
| 2 | 90 | 53 | 0 | 190 | 190 | 0 | 140 | 140 | 0 |
| 3 | 60 | 120 | 60 | 210 | 210 | 0 | 10 | 10 | 0 |
| 4 | 150 | 90 | 0 | 200 | 200 | 0 | 150 | 150 | 0 |
| 5 | 10 | 20 | 10 | 150 | 150 | 0 | 100 | 100 | 0 |
| 6 | 50 | 40 | 0 | 120 | 120 | 0 | 200 | 200 | 0 |
| 7 | 100 | 170 | 70 | 100 | 100 | 0 | 90 | 90 | 0 |
| 8 | 250 | 180 | 0 | 280 | 280 | 0 | 50 | 50 | 0 |
| 9 | 60 | 60 | 0 | 90 | 90 | 0 | 190 | 190 | 0 |
| 10 | 40 | 67 | 27 | 50 | 50 | 0 | 80 | 80 | 0 |
| 11 | 100 | 138 | 65 | 200 | 200 | 0 | 90 | 90 | 0 |
| 12 | 180 | 115 | 0 | 250 | 250 | 0 | 150 | 150 | 0 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (ohne Mindestzusatzkapazität):

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 230.5 | 500 | 191 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 287.0 | 500 | 243 | 260 | 0 | 100 |
| 4 | 420.0 | 500 | 260 | 260 | 40 | 100 |
| 5 | 280.0 | 500 | 175 | 260 | 0 | 100 |
| 6 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 7 | 293.0 | 500 | 260 | 260 | 32 | 100 |
| 8 | 430.0 | 500 | 260 | 260 | 100 | 100 |
| 9 | 348.0 | 500 | 257 | 260 | 0 | 100 |
| 10 | 201.0 | 500 | 199 | 260 | 0 | 100 |
| 11 | 355.5 | 500 | 260 | 260 | 7 | 100 |
| 12 | 487.5 | 500 | 260 | 260 | 100 | 100 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (mit Mindestzusatzkapazität):

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 230.5 | 500 | 191 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 282.0 | 500 | 233 | 260 | 0 | 100 |
| 4 | 425.0 | 500 | 260 | 260 | 50 | 100 |
| 5 | 280.0 | 500 | 175 | 260 | 0 | 100 |
| 6 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 7 | 293.0 | 500 | 242 | 260 | 50 | 100 |
| 8 | 430.0 | 500 | 260 | 260 | 100 | 100 |
| 9 | 348.0 | 500 | 257 | 260 | 0 | 100 |
| 10 | 179.5 | 500 | 156 | 260 | 0 | 100 |
| 11 | 377.0 | 500 | 260 | 260 | 50 | 100 |
| 12 | 487.5 | 500 | 260 | 260 | 100 | 100 |# Modellerweiterung: 

## Mindestproduktionsmengen

(Diskretisierung)# Beschäftigungsglättung: Mindestproduktionsmengen 

## Annahmen:

-     - wie Grundmodell -
$X_{k t}:=\left\{\begin{array}{l}1, \text { wenn } k \text { in } t \text { produziert wird } \\ 0 \text { sonst }\end{array}\right.$
$k \in \mathcal{K}, t=1,2, \ldots, T)$
- Big- $M$-Methode

$$
x_{k t} \leq M \cdot X_{k t}
$$

$$
(k \in \mathcal{K}, t=1,2, \ldots, T)
$$

Wenn Produktion, dann mindestens $X_{k}^{\min }$ :

$$
x_{k t} \geq X_{k}^{\min } \cdot X_{k t}
$$

$$
(k \in \mathcal{K}, t=1,2, \ldots, T)
$$# Beschäftigungsglättung: Grundmodell AGGRPLAN 

## Beispiel II 3 Produkte, 12 Perioden

$L_{\max }=70$
$U_{\min }=50$
$X_{1}^{\min }=50, X_{2}^{\min }=100, X_{3}^{\min }=50$# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (ohne Mindestproduktionsmengen):

| Periode $t$ | $d_{1 t}$ | $x_{1 t}$ | $L_{1 t}$ | $d_{2 t}$ | $x_{2 t}$ | $L_{2 t}$ | $d_{3 t}$ | $x_{3 t}$ | $L_{3 t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  |  | 36 |  |  | 20 |  |  | 10 |
| 1 | 100 | 101 | 37 | 200 | 180 | 0 | 10 | 0 | 0 |
| 2 | 90 | 53 | 0 | 190 | 190 | 0 | 140 | 140 | 0 |
| 3 | 60 | 120 | 60 | 210 | 210 | 0 | 10 | 10 | 0 |
| 4 | 150 | 90 | 0 | 200 | 200 | 0 | 150 | 150 | 0 |
| 5 | 10 | 20 | 10 | 150 | 150 | 0 | 100 | 100 | 0 |
| 6 | 50 | 40 | 0 | 120 | 120 | 0 | 200 | 200 | 0 |
| 7 | 100 | 170 | 70 | 100 | 100 | 0 | 90 | 90 | 0 |
| 8 | 250 | 180 | 0 | 280 | 280 | 0 | 50 | 50 | 0 |
| 9 | 60 | 60 | 0 | 90 | 90 | 0 | 190 | 190 | 0 |
| 10 | 40 | 67 | 27 | 50 | 50 | 0 | 80 | 80 | 0 |
| 11 | 100 | 138 | 65 | 200 | 200 | 0 | 90 | 90 | 0 |
| 12 | 180 | 115 | 0 | 250 | 250 | 0 | 150 | 150 | 0 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (mit Mindestproduktionsmengen):

| Periode $t$ | $d_{1 t}$ | $x_{1 t}$ | $L_{1 t}$ | $d_{2 t}$ | $x_{2 t}$ | $L_{2 t}$ | $d_{3 t}$ | $x_{3 t}$ | $L_{3 t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  |  | 36 |  |  | 20 |  |  | 10 |
| 1 | 100 | 101 | 37 | 200 | 180 | 0 | 10 | 0 | 0 |
| 2 | 90 | 53 | 0 | 190 | 190 | 0 | 140 | 140 | 0 |
| 3 | 60 | 88 | 28 | 210 | 210 | 0 | 10 | 50 | 40 |
| 4 | 150 | 122 | 0 | 200 | 200 | 0 | 150 | 110 | 0 |
| 5 | 10 | 60 | 50 | 150 | 150 | 0 | 100 | 100 | 0 |
| 6 | 50 | 0 | 0 | 120 | 120 | 0 | 200 | 240 | 40 |
| 7 | 100 | 170 | 70 | 100 | 100 | 0 | 90 | 50 | 0 |
| 8 | 250 | 180 | 0 | 280 | 280 | 0 | 50 | 50 | 0 |
| 9 | 60 | 60 | 0 | 90 | 140 | 50 | 190 | 190 | 0 |
| 10 | 40 | 67 | 27 | 50 | 0 | 0 | 80 | 80 | 0 |
| 11 | 100 | 138 | 65 | 200 | 200 | 0 | 90 | 90 | 0 |
| 12 | 180 | 115 | 0 | 250 | 250 | 0 | 150 | 150 | 0 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (ohne Mindestproduktionsmengen):

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 230.5 | 500 | 191 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 282.0 | 500 | 233 | 260 | 0 | 100 |
| 4 | 425.0 | 500 | 260 | 260 | 50 | 100 |
| 5 | 280.0 | 500 | 175 | 260 | 0 | 100 |
| 6 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 7 | 293.0 | 500 | 242 | 260 | 50 | 100 |
| 8 | 430.0 | 500 | 260 | 260 | 100 | 100 |
| 9 | 348.0 | 500 | 257 | 260 | 0 | 100 |
| 10 | 179.5 | 500 | 156 | 260 | 0 | 100 |
| 11 | 377.0 | 500 | 260 | 260 | 50 | 100 |
| 12 | 487.5 | 500 | 260 | 260 | 100 | 100 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (mit Mindestproduktionsmengen):

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 230.5 | 500 | 191 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 314.0 | 500 | 233 | 260 | 0 | 100 |
| 4 | 393.0 | 500 | 260 | 260 | 50 | 100 |
| 5 | 300.0 | 500 | 215 | 260 | 0 | 100 |
| 6 | 408.0 | 500 | 252 | 260 | 0 | 100 |
| 7 | 245.0 | 500 | 260 | 260 | 0 | 100 |
| 8 | 430.0 | 500 | 260 | 260 | 100 | 100 |
| 9 | 398.0 | 500 | 232 | 260 | 50 | 100 |
| 10 | 129.5 | 500 | 131 | 260 | 0 | 100 |
| 11 | 377.0 | 500 | 260 | 260 | 50 | 100 |
| 12 | 487.5 | 500 | 260 | 260 | 100 | 100 |# Erweitertes Modell: Eine Fabrik, Fremdlieferanten <br> (Make-or-Buy-Entscheidung)![img-14.jpeg](img-14.jpeg)# Beschäftigungsglättung: Erweitertes Modell 

Annahmen:

-     - wie Grundmodell -
- Erweiterung der Zielfunktion: Beschaffungskosten, variable Produktionskosten
$c_{k}^{\mathrm{B}} \ldots$ Fremdbezugskosten pro Mengeneinheit von Produkt $k$
$c_{k}^{\mathrm{P}} \ldots$ variable Produktionskosten (Materialkosten) von Produkt $k$
produktspezifische Fremdlieferanten
(keine explizite Modellierung der Lieferanten; der Beschaffungsprozess bleibt daher außerhalb der Betrachtung)
$B_{k t} \ldots$ Beschaffungsmenge von Produkt $k$ in Periode $t$Minimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} h_{k} \cdot L_{k t}+\sum_{t=1}^{T} u_{t} \cdot U_{t}+\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} c_{k}^{\mathrm{B}} \cdot B_{k t}+\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} c_{k}^{\mathrm{P}} \cdot x_{k t}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

für alle $k \in \mathcal{K}$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}+B_{k t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{T}} \cdot x_{k t} \leq b_{t}^{\mathrm{T}}
$$

für alle $t=1,2, \ldots, T$
für alle $t=1,2, \ldots, T$

Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{P}} \cdot x_{k t}-U_{t} \leq b_{t}^{\mathrm{P}}
$$

für alle $t=1,2, \ldots, T$
Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t} \leq U_{t}^{\max }
$$

für alle $t=1,2, \ldots, T$Minimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} h_{k} \cdot L_{k t}+\sum_{t=1}^{T} u_{t} \cdot U_{t}+\sum_{k \in \mathcal{K}} \sum_{t=1}^{T}\left(c_{k}^{\mathrm{B}}-c_{k}^{\mathrm{P}}\right) \cdot B_{k t}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

$$
\text { für alle } k \in \mathcal{K}
$$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}+B_{k t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{T}} \cdot x_{k t} \leq b_{t}^{\mathrm{T}}
$$

für alle $t=1,2, \ldots, T$
für alle $t=1,2, \ldots, T$
Die
Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{P}} \cdot x_{k t}-U_{t} \leq b_{t}^{\mathrm{P}}
$$

für alle $t=1,2, \ldots, T$
Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t} \leq U_{t}^{\max }
$$

für alle $t=1,2, \ldots, T$Minimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} h_{k} \cdot L_{k t}+\sum_{t=1}^{T} u_{t} \cdot U_{t}+\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} c_{k}^{\mathrm{B}^{\prime}} \cdot B_{k t}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

für alle $k \in \mathcal{K}$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}+B_{k t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{T}} \cdot x_{k t} \leq b_{t}^{\mathrm{T}}
$$

für alle $t=1,2, \ldots, T$
für alle $t=1,2, \ldots, T$

Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{p}} \cdot x_{k t}-U_{t} \leq b_{t}^{\mathrm{p}}
$$

für alle $t=1,2, \ldots, T$
Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t} \leq U_{t}^{\max }
$$

für alle $t=1,2, \ldots, T$Minimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T}\left(h_{k} \cdot L_{k t}+c_{k}^{\mathrm{B}^{\prime}} \cdot B_{k t}\right)+\sum_{t=1}^{T} u_{t} \cdot U_{t}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

für alle $k \in \mathcal{K}$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}+B_{k t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{T}} \cdot x_{k t} \leq b_{t}^{\mathrm{T}}
$$

für alle $t=1,2, \ldots, T$
für alle $t=1,2, \ldots, T$
für alle $t=1,2, \ldots, T$

# Verfügbare personelle Kapazität in Periode $t$ : 

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{P}} \cdot x_{k t}-U_{t} \leq b_{t}^{\mathrm{P}}
$$

für alle $t=1,2, \ldots, T$
Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t} \leq U_{t}^{\max }
$$

für alle $t=1,2, \ldots, T$# Beispiel II 3 Produkte, 12 Perioden 

$c_{1}^{\mathrm{B}^{\prime}}=5, c_{2}^{\mathrm{B}^{\prime}}=10, c_{3}^{\mathrm{B}^{\prime}}=5$# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (ohne Fremdbeschaffung):

| Periode $t$ | $d_{1 t}$ | $x_{1 t}$ | $B_{1 t}$ | $L_{1 t}$ | $d_{2 t}$ | $x_{2 t}$ | $B_{2 t}$ | $L_{2 t}$ | $d_{3 t}$ | $x_{3 t}$ | $B_{3 t}$ | $L_{3 t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  |  |  | 36 |  |  |  | 20 |  |  |  | 10 |
| 1 | 100 | 101 | 0 | 37 | 200 | 180 | 0 | 0 | 10 | 0 | 0 | 0 |
| 2 | 90 | 53 | 0 | 0 | 190 | 190 | 0 | 0 | 140 | 140 | 0 | 0 |
| 3 | 60 | 147 | 0 | 87 | 210 | 210 | 0 | 0 | 10 | 10 | 0 | 0 |
| 4 | 150 | 63 | 0 | 0 | 200 | 200 | 0 | 0 | 150 | 150 | 0 | 0 |
| 5 | 10 | 20 | 0 | 10 | 150 | 150 | 0 | 0 | 100 | 100 | 0 | 0 |
| 6 | 50 | 40 | 0 | 0 | 120 | 120 | 0 | 0 | 200 | 200 | 0 | 0 |
| 7 | 100 | 170 | 0 | 70 | 100 | 100 | 0 | 0 | 90 | 90 | 0 | 0 |
| 8 | 250 | 180 | 0 | 0 | 280 | 280 | 0 | 0 | 50 | 50 | 0 | 0 |
| 9 | 60 | 60 | 0 | 0 | 90 | 90 | 0 | 0 | 190 | 190 | 0 | 0 |
| 10 | 40 | 117 | 0 | 77 | 50 | 50 | 0 | 0 | 80 | 80 | 0 | 0 |
| 11 | 100 | 88 | 0 | 65 | 200 | 200 | 0 | 0 | 90 | 90 | 0 | 0 |
| 12 | 180 | 115 | 0 | 0 | 250 | 250 | 0 | 0 | 150 | 150 | 0 | 0 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (mit Fremdbeschaffung):

| Periode $t$ | $d_{1 t}$ | $x_{1 t}$ | $B_{1 t}$ | $L_{1 t}$ | $d_{2 t}$ | $x_{2 t}$ | $B_{2 t}$ | $L_{2 t}$ | $d_{3 t}$ | $x_{3 t}$ | $B_{3 t}$ | $L_{3 t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  |  |  | 36 |  |  |  | 20 |  |  |  | 10 |
| 1 | 100 | 64 | 0 | 0 | 200 | 180 | 0 | 0 | 10 | 0 | 0 | 0 |
| 2 | 90 | 53 | 37 | 0 | 190 | 190 | 0 | 0 | 140 | 140 | 0 | 0 |
| 3 | 60 | 147 | 0 | 87 | 210 | 210 | 0 | 0 | 10 | 10 | 0 | 0 |
| 4 | 150 | 40 | 23 | 0 | 200 | 200 | 0 | 0 | 150 | 150 | 0 | 0 |
| 5 | 10 | 20 | 0 | 10 | 150 | 150 | 0 | 0 | 100 | 100 | 0 | 0 |
| 6 | 50 | 40 | 0 | 0 | 120 | 120 | 0 | 0 | 200 | 200 | 0 | 0 |
| 7 | 100 | 138 | 0 | 38 | 100 | 100 | 0 | 0 | 90 | 90 | 0 | 0 |
| 8 | 250 | 80 | 132 | 0 | 280 | 280 | 0 | 0 | 50 | 50 | 0 | 0 |
| 9 | 60 | 60 | 0 | 0 | 90 | 90 | 0 | 0 | 190 | 190 | 0 | 0 |
| 10 | 40 | 52 | 0 | 12 | 50 | 50 | 0 | 0 | 80 | 80 | 0 | 0 |
| 11 | 100 | 88 | 0 | 0 | 200 | 200 | 0 | 0 | 90 | 90 | 0 | 0 |
| 12 | 180 | 15 | 165 | 0 | 250 | 250 | 0 | 0 | 150 | 150 | 0 | 0 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (ohne Fremdbeschaffung):

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 230.5 | 500 | 191 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 295.5 | 500 | 260 | 260 | 0 | 100 |
| 4 | 411.5 | 500 | 260 | 260 | 23 | 100 |
| 5 | 280.0 | 500 | 175 | 260 | 0 | 100 |
| 6 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 7 | 293.0 | 500 | 260 | 260 | 32 | 100 |
| 8 | 430.0 | 500 | 260 | 260 | 100 | 100 |
| 9 | 348.0 | 500 | 257 | 260 | 0 | 100 |
| 10 | 204.5 | 500 | 206 | 260 | 0 | 100 |
| 11 | 352.0 | 500 | 260 | 260 | 0 | 100 |
| 12 | 487.5 | 500 | 260 | 260 | 100 | 100 |# Beispiel II 3 Produkte, 12 Perioden 

Optimale Lösung (mit Fremdbeschaffung):

| Periode $t$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{T}} \cdot x_{k t}$ | $b_{t}^{\mathrm{T}}$ | $\sum_{k=1}^{3} f_{k}^{\mathrm{P}} \cdot x_{k t}$ | $b_{t}^{\mathrm{P}}$ | $U_{t}$ | $U_{t}^{\max }$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 212.0 | 500 | 154 | 260 | 0 | 100 |
| 2 | 384.5 | 500 | 260 | 260 | 0 | 100 |
| 3 | 295.5 | 500 | 260 | 260 | 0 | 100 |
| 4 | 400.0 | 500 | 260 | 260 | 0 | 100 |
| 5 | 280.0 | 500 | 175 | 260 | 0 | 100 |
| 6 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 7 | 277.0 | 500 | 260 | 260 | 0 | 100 |
| 8 | 380.0 | 500 | 260 | 260 | 0 | 100 |
| 9 | 348.0 | 500 | 257 | 260 | 0 | 100 |
| 10 | 172.0 | 500 | 141 | 260 | 0 | 100 |
| 11 | 352.0 | 500 | 260 | 260 | 0 | 100 |
| 12 | 437.5 | 500 | 260 | 260 | 0 | 100 |# Erweitertes Modell (II): Mehrere Fabriken![img-15.jpeg](img-15.jpeg)# Beschäftigungsglättung: Mehrere Fabriken 

Annahmen:

- wie Grundmodell -
$\rightarrow$ mehrere Fabriken $s \in \mathcal{S}$
$\rightarrow$ fabrikspezifische Produktionsprogramme und Nachfrage
$\mathcal{K}_{s} \ldots$ Menge der in Fabrik $s$ gefertigten Produkte
$\rightarrow$ Erweiterung der Zielfunktion: Transportkosten
$c_{k}^{\mathrm{T}^{(s i)}} \ldots$ Transportkostensatz von Produkt $k$ von Fabrik $s$ nach $i$
$T_{k t}^{(s i)} \ldots$ Transportmenge von Produkt $k$ von $s$ nach $i$ in Periode $t$Minimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} h_{k} \cdot L_{k t}+\sum_{t=1}^{T} u_{t} \cdot U_{t}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

für alle $k \in \mathcal{K}$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{T}} \cdot x_{k t} \leq b_{t}^{\mathrm{T}}
$$

für alle $t=1,2, \ldots, T$
für alle $t=1,2, \ldots, T$

Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} f_{k}^{\mathrm{P}} \cdot x_{k t}-U_{t} \leq b_{t}^{\mathrm{P}}
$$

für alle $t=1,2, \ldots, T$
Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t} \leq U_{t}^{\max }
$$

für alle $t=1,2, \ldots, T$Minimiere $Z=\sum_{s \in \mathcal{S}}\left(\sum_{k \in \mathcal{K}_{s}} \sum_{t=1}^{T} h_{k}^{(s)} \cdot L_{k t}^{(s)}+\sum_{t=1}^{T} u_{t}^{(s)} \cdot U_{t}^{(s)}\right)+\sum_{s \in \mathcal{S}} \sum_{i \in \mathcal{S}} \sum_{k \in \mathcal{K}_{s}} \sum_{t=1}^{T} c_{k}^{\mathrm{T}^{(s i)}} \cdot T_{k t}^{(s i)}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}^{(s)}=L_{k s}^{(0)} \quad \text { für alle } s \in \mathcal{S}, k \in \mathcal{K}_{s}
$$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}^{(s)}+x_{k t}^{(s)}+\sum_{j \in \mathcal{S}} T_{k t}^{(j s)}-\sum_{i \in \mathcal{S}} T_{k t}^{(s i)}-L_{k t}^{(s)}=d_{k t}^{(s)} \quad \forall s \in \mathcal{S}, k \in \mathcal{K}_{s}, t=1, \ldots, T
$$

Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{T}^{(s)}} \cdot x_{k t}^{(s)} \leq b_{t}^{\mathrm{T}^{(s)}} \quad \text { für alle } s \in \mathcal{S} \text { und } t=1,2, \ldots, T
$$

Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{P}^{(s)}} \cdot x_{k t}^{(s)}-U_{t}^{(s)} \leq b_{t}^{\mathrm{P}^{(s)}} \quad \text { für alle } s \in \mathcal{S} \text { und } t=1,2, \ldots, T
$$

Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t}^{(s)} \leq U_{t}^{\max (s)}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Erweitertes Modell (II): Mehrere Fabriken, Fremdlieferanten# Beschäftigungsglättung: Mehrere Fabriken, Lieferanten 

![img-16.jpeg](img-16.jpeg)Minimiere $Z=\sum_{s \in \mathcal{S}}\left(\sum_{k \in \mathcal{K}_{s}} \sum_{t=1}^{T} h_{k}^{(s)} \cdot L_{k t}^{(s)}+\sum_{t=1}^{T} u_{t}^{(s)} \cdot U_{t}^{(s)}\right)+\sum_{s \in \mathcal{S}} \sum_{i \in \mathcal{S}} \sum_{k \in \mathcal{K}_{s}} \sum_{t=1}^{T} c_{k}^{\mathrm{T}^{(s i)}} \cdot T_{k t}^{(s i)}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}^{(s)}=L_{k s}^{(0)} \quad \text { für alle } s \in \mathcal{S}, k \in \mathcal{K}_{s}
$$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}^{(s)}+x_{k t}^{(s)}+\sum_{j \in \mathcal{S}} T_{k t}^{(j s)}-\sum_{i \in \mathcal{S}} T_{k t}^{(s i)}-L_{k t}^{(s)}=d_{k t}^{(s)} \quad \forall s \in \mathcal{S}, k \in \mathcal{K}_{s}, t=1, \ldots, T
$$

Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{T}^{(s)}} \cdot x_{k t}^{(s)} \leq b_{t}^{\mathrm{T}^{(s)}} \quad \text { für alle } s \in \mathcal{S} \text { und } t=1,2, \ldots, T
$$

Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{P}^{(s)}} \cdot x_{k t}^{(s)}-U_{t}^{(s)} \leq b_{t}^{\mathrm{P}^{(s)}} \quad \text { für alle } s \in \mathcal{S} \text { und } t=1,2, \ldots, T
$$

Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t}^{(s)} \leq U_{t}^{\max (s)}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Beschäftigungsglättung: Mehrere Fabriken, Lieferanten 

$Z=\sum_{s \in \mathcal{S}}\left(\sum_{k \in \mathcal{K}_{s}} \sum_{t=1}^{T}\left(h_{k}^{(s)} L_{k t}^{(s)}+c_{k s}^{\mathrm{P}} x_{k t}^{(s)}+c_{k s}^{\mathrm{B}} B_{k t}^{(s)}\right)+\sum_{t=1}^{T} u_{t}^{(s)} U_{t}^{(s)}+\sum_{i \in \mathcal{S}} \sum_{k \in \mathcal{K}_{s}} \sum_{t=1}^{T} c_{k}^{\mathrm{T}^{(s i)}} T_{k t}^{(s i)}\right)$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}^{(s)}=L_{k s}^{(0)} \quad \text { für alle } s \in \mathcal{S}, k \in \mathcal{K}_{s}
$$

Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}^{(s)}+x_{k t}^{(s)}+B_{k t}^{(s)}+\sum_{j \in \mathcal{S}} T_{k t}^{(j s)}-\sum_{i \in \mathcal{S}} T_{k t}^{(s i)}-L_{k t}^{(s)}=d_{k t}^{(s)}
$$

Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{T}^{(s)}} \cdot x_{k t}^{(s)} \leq b_{t}^{\mathrm{T}^{(s)}} \quad \text { für alle } s \in \mathcal{S} \text { und } t=1,2, \ldots, T
$$

Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{P}^{(s)}} \cdot x_{k t}^{(s)}-U_{t}^{(s)} \leq b_{t}^{\mathrm{P}^{(s)}} \quad \text { für alle } s \in \mathcal{S} \text { und } t=1,2, \ldots, T
$$

Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t}^{(s)} \leq U_{t}^{\max (s)}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$# Mehrstufige Ansätze![img-17.jpeg](img-17.jpeg)
zusätzliche Annahme (zur Komplexitätsreduktion):
feststehende eindeutige Zuordnung von (Vor-)Produkten zu Fabriken $\Longrightarrow$ keine Nutzung von internen Ersatzkapazitäten# Beschäftigungsglättung: Mehrstufiger Ansatz 

Annahmen:

-     - wie bisher -
Direktbedarfskoeffizienten
$a_{k j} \ldots$ Anzahl Mengeneinheiten von Produkt $k$, die in eine Mengeneinheit von Produkt $j$ eingehen
- Erweiterung Lagerbilanzgleichung -
$L_{k, t-1}+x_{k t}-L_{k t}=d_{k t}+\sum_{j \in \mathcal{K}} a_{k j} \cdot x_{j t}$
für alle $k \in \mathcal{K}, t \in\{1, \ldots, T\}$Minimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} h_{k} \cdot L_{k t}+\sum_{s \in \mathcal{S}} \sum_{t=1}^{T} u_{t}^{(s)} \cdot U_{t}^{(s)}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

für alle $k \in \mathcal{K}$
Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{T}} \cdot x_{k t} \leq b_{t}^{\mathrm{T}^{(s)}}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$
Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{P}} \cdot x_{k t}-U_{t}^{(s)} \leq b_{t}^{\mathrm{P}(s)}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$
Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t}^{(s)} \leq U_{t}^{\max (s)}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft IIMinimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} h_{k} \cdot L_{k t}+\sum_{s \in \mathcal{S}} \sum_{t=1}^{T} u_{t}^{(s)} \cdot U_{t}^{(s)}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

für alle $k \in \mathcal{K}$
Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}-\sum_{j \in \mathcal{K}} a_{k j} \cdot x_{j t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare technische Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{T}} \cdot x_{k t} \leq b_{t}^{\mathrm{T}^{(s)}}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$
Verfügbare personelle Kapazität in Periode $t$ :

$$
\sum_{k \in \mathcal{K}_{s}} f_{k}^{\mathrm{P}} \cdot x_{k t}-U_{t}^{(s)} \leq b_{t}^{\mathrm{P}(s)}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$
Maximale Zusatzkapazität in Periode $t$ :

$$
U_{t}^{(s)} \leq U_{t}^{\max (s)}
$$

für alle $s \in \mathcal{S}$ und $t=1,2, \ldots, T$
(c) Univ.-Prof. Dr. Michael Manitz

Produktionswirtschaft II# Hauptproduktions- 

programmplanung# Hauptproduktionsprogrammplanung 

Ziele
$\triangleright$ kostenminimale Glättung der Kapazitätsnutzung im Zeitablauf
$\triangleright$ Festlegung und Koordinierung der dezentralen, mengen- und terminmäßig spezifizierten Produktionsprogramme für einen mittelfristigen Zeitraum
(= „Hauptproduktionsprogrammplanung")
$\rightarrow$ Entscheidungsvariablen
$\triangleright$ Produktionsmengen
$\triangleright$ Zusatzkapazität (Überstunden, Fremdvergabe von Aufträgen, ...)
$\triangleright$ Lagerbestände
Daten
$\triangleright$ Nachfragemengen (Absatzprognosen, Kundenaufträge)
$\triangleright$ Kapazitäten# Hauptproduktionsprogrammplanung 

## Aggregiert:

Markt-/Nachfrageprognosen
werksbezogene Kapazitätsdaten
mittelfristiges Produktionsprogramm in bezug auf Produkttypen
![img-18.jpeg](img-18.jpeg)
(vgl. Günther/Tempelmeier (2016))# Kapazitierte Hauptproduktionsprogrammplanung# Modell HPPPLANJ 

Indexmengen:
$\mathcal{J} \ldots$ die Menge der zu betrachtenden Produktionssegmente
$\mathcal{K} \ldots$ die Menge der betrachteten Produkte
Variablen:
$x_{k t} \ldots$ die Produktionsmenge für Produkt $k$ in Periode $t$
$L_{k t} \ldots$ der Lagerbestand für Produkt $k$ in Periode $t$
$U_{j t} \ldots$ die Zusatzkapazität (Überstunden) in Segment $j$ in Periode $t$
Daten:
$d_{k t} \ldots$ die Nachfragemenge für Produkt $k$ in Periode $t$
$b_{j t} \ldots$ die maximale Kapazität in Segment $j$ in Periode $t$![img-19.jpeg](img-19.jpeg)# Kapazitätsbelastungsprofil 

| Vorlaufperiode | 0 | 1 | 2 |
| :--: | :--: | :--: | :--: |
| Endprodukt A |  |  |  |
| Produktionssegment 1 | 1 (A) | - | — |
| Produktionssegment 2 | — | $1+3=4$ (C und D) | — |
| Produktionssegment 3 | — | — | — |
| Endprodukt B |  |  |  |
| Produktionssegment 1 | 2 (B) | — | — |
| Produktionssegment 2 | — | 3 (D) | — |
| Produktionssegment 3 | — | 4 (E) | $2+1=3$ (F und G) |

(Beispiel aus Günther/Tempelmeier (2007))
$f_{j k z}$... durch Produkt $k$ verursachte Kapazitätsbelastung von Produktionssegment $j$ in der Vorlaufperiode $z$ ( $=$,,Kapazitätsbelastungsfaktor")
Kapazitätsbeschränkung durch die knappe Kapzität in Periode $t$ :
$1 \cdot x_{\mathrm{A} t}+2 \cdot x_{\mathrm{B} t} \leq b_{1 t}+U_{1 t}$
$4 \cdot x_{\mathrm{A}, t+1}+3 \cdot x_{\mathrm{B}, t+1} \leq b_{2 t}+U_{2 t}$
$4 \cdot x_{\mathrm{B}, t+1}+3 \cdot x_{\mathrm{B}, t+2} \leq b_{3 t}+U_{3 t}$# Modell HPPPLANJ 

Indexmengen:
$\mathcal{J} \ldots$ die Menge der zu betrachtenden Produktionssegmente
$\mathcal{K} \ldots$ die Menge der betrachteten Produkte
Variablen:
$x_{k t} \ldots$ die Produktionsmenge für Produkt $k$ in Periode $t$
$L_{k t} \ldots$ der Lagerbestand für Produkt $k$ in Periode $t$
$U_{j t} \ldots$ die Zusatzkapazität (Überstunden) in Segment $j$ in Periode $t$
Daten:
$d_{k t} \ldots$ die Nachfragemenge für Produkt $k$ in Periode $t$
$b_{j t} \ldots$ die maximale Kapazität in Segment $j$ in Periode $t$
$f_{j k z} \ldots$ die Kapazitätsbelastungsfaktoren
$U_{j t}^{\max } \ldots$ die maximale Zusatzkapazität in Segment $j$ in Periode $t$# Modell HPPPLANJ 

Daten - Fortsetzung -:
$Z_{k} \ldots$ die für Produkt $k$ zu berücksichtigende maximale Vorlaufzeit
$L_{k}^{(0)} \ldots$ der Anfangslagerbestand für Produkt $k$
$h_{k} \ldots$ der Lagerkostensatz für Produkt $k$
$u_{t} \ldots$ der Kostensatz für Zusatzkapazität in Periode $t$# Modell HPPPLANJ 

Minimiere $Z=\sum_{k \in \mathcal{K}} \sum_{t=1}^{T} h_{k} \cdot L_{k t}+\sum_{t=1}^{T} \sum_{j \in \mathcal{J}} u_{t} \cdot U_{j t}$
u. B. d. R.:

Anfangslagerbestand für Produkt $k$ :

$$
L_{k 0}=L_{k}^{(0)}
$$

für alle $k \in \mathcal{K}$
Nachfrage für Produkt $k$ in Periode $t$ :

$$
L_{k, t-1}+x_{k t}-L_{k t}=d_{k t}
$$

für alle $k \in \mathcal{K}$ und $t=1,2, \ldots, T$
Verfügbare Kapazität in Segment $j$ in Periode $t$ :

$$
\sum_{k \in \mathcal{K}} \sum_{z=0}^{Z_{k}} f_{j k z} \cdot x_{k, t+z}-U_{j t} \leq b_{j t}
$$

für alle $j \in \mathcal{J}, t=1,2, \ldots, T$
Maximale Zusatzkapazität im Segment $j$ in Periode $t$ :

$$
U_{j t} \leq U_{j t}^{\max }
$$

für alle $j \in \mathcal{J}, t=1,2, \ldots, T$# Beispiel 2 Produkte, 8 Perioden 

## Nachfragemengen

| Periode <br> Produkt | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| A | - | 45.00 | 30.00 | 10.00 | 0.00 | 50.00 | 10.00 | 0.00 |
| B | - | - | 25.00 | 30.00 | 25.00 | 30.00 | 20.00 | 0.00 |

## weitere Daten

- Normalkapazität: $b_{j t}=100$
- maximale Zusatzkapazität: $U_{j t}^{\max }=100$
- Lagerkostensatz: $h_{k}=40$
- Überstundenzuschlag: $u_{t}=5$
$(j=1,2,3 ; t=1,2, \ldots, 8)$
$(j=1,2,3 ; t=1,2, \ldots, 8)$
$(k \in\{A, B\})$
$(t=1,2, \ldots, 8)$# Beispiel 2 Produkte, 8 Perioden 

## Nachfragemengen

| Periode <br> Produkt | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| A | - | 45.00 | 30.00 | 10.00 | 0.00 | 50.00 | 10.00 | 0.00 |
| B | - | - | 25.00 | 30.00 | 25.00 | 30.00 | 20.00 | 0.00 |

## optimale Produktionsmengen

| Periode <br> Produkt | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| A | - | 47.50 | 27.50 | 31.25 | 31.25 | 27.50 | 10.00 | 20.00 |
| B | - | - | 30.00 | 25.00 | 25.00 | 30.00 | 20.00 | 10.00 |# Operative Produktionsplanung und -steuerung 

![img-20.jpeg](img-20.jpeg)
(vgl. Drexl/Fleischmann/Günther/Stadtler/Tempelmeier (1993), Tempelmeier (2008))# Operative Produktionsplanung und -steuerung 

![img-21.jpeg](img-21.jpeg)
(vgl. Drexl/Fleischmann/Günther/Stadtler/Tempelmeier (1993), Tempelmeier (2008))# Operative Produktionsplanung und -steuerung 

![img-22.jpeg](img-22.jpeg)
(vgl. Drexl/Fleischmann/Günther/Stadtler/Tempelmeier (1993), Tempelmeier (2008))