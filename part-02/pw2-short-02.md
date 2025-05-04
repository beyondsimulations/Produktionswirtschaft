# Exponentielle Glättung bei Vorliegen eines Trends: Das Verfahren von Holt# Prognoseverfahren bei Trend: Verfahren von Holt 

Verwendung von zwei Glättungsparametern
Achsenabschnitt der Trendgeraden

$$
\widehat{a}_{t}=\alpha \cdot y_{t}+(1-\alpha) \cdot(\underbrace{\widehat{a}_{t-1}+\widehat{b}_{t-1}}_{\text {letzte Schätzung des Nachfrageniveaus }}
$$

Steigung der Trendgeraden

$$
\widehat{b}_{t}=\beta \cdot(\underbrace{\widehat{a}_{t}-\widehat{a}_{t-1}}_{\text {aktuelle Beobachtung der Steigung }})
$$

Prognosewerte ( $i$ Perioden später)

$$
p_{t+i}=\widehat{a}_{t}+\widehat{b}_{t} \cdot i
$$# Beispiel Verfahren von Holt $(\alpha=0.1, \beta=0.2)$ 

Nachfragedaten für 1997:

| $t$ | $y_{t}$ | $\widehat{a}_{t}$ | $\widehat{b}_{t}$ | $p_{t}$ | $e_{t}$ |
| --: | --: | :--: | :--: | :--: | :--: |
| 0 | 0 | 275.0000 | 10.8800 | 0 | 0 |
| 1 | 317 | 288.9920 | 11.5024 | 285.8800 | 31.1200 |
| 2 | 194 | 289.8450 | 9.3725 | 300.4944 | -106.4944 |
| 3 | 312 | 300.4957 | 9.6282 | 299.2175 | 12.7825 |
| 4 | 316 | 310.7115 | 9.7457 | 310.1239 | 5.8761 |
| 5 | 322 | 320.6115 | 9.7765 | 320.4572 | 1.5428 |
| 6 | 334 | 330.7492 | 9.8488 | 330.3880 | 3.6120 |
| 7 | 317 | 338.2382 | 9.3768 | 340.5980 | -23.5980 |
| 8 | 356 | 348.4535 | 9.5445 | 347.6150 | 8.3850 |
| 9 | 428 | 364.9982 | 10.9446 | 357.9980 | 70.0020 |
| 10 | 411 | 379.4485 | 11.6457 | 375.9428 | 35.0572 |
| 11 | 494 | 401.3848 | 13.7038 | 391.0942 | 102.9058 |
| 12 | 412 | 414.7798 | 13.6420 | 415.0886 | -3.0886 |

(s. Tempelmeier (2008))# Beispiel Verfahren von Holt $(\alpha=0.1, \beta=0.2)$ 

Nachfragedaten für 1998:

| $t$ | $y_{t}$ | $\widehat{a}_{t}$ | $\widehat{b}_{t}$ | $p_{t}$ | $e_{t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 13 | 460 | 431.5796 | 14.2736 | 428.4218 | 31.5782 |
| 14 | 395 | 440.7679 | 13.2565 | 445.8532 | -50.8532 |
| 15 | 392 | 447.8220 | 12.0161 | 454.0245 | -62.0245 |
| 16 | 447 | 458.5543 | 11.7593 | 459.8381 | -12.8381 |
| 17 | 452 | 468.4822 | 11.3930 | 470.3136 | -18.3136 |
| 18 | 571 | 488.9877 | 3.2155 | 479.8752 | 91.1248 |
| 19 | 517 | 503.6829 | 13.5115 | 502.2032 | 14.7968 |
| 20 | 397 | 505.1749 | 11.1076 | 517.1944 | -120.1944 |
| 21 | 410 | 505.6542 | 8.9819 | 516.2825 | -106.2825 |
| 22 | 579 | 521.0725 | 10.2692 | 514.6362 | 64.3638 |
| 23 | 473 | 525.5076 | 9.1024 | 531.3417 | -58.3417 |
| 24 | 558 | 536.9489 | 9.5702 | 534.6099 | 23.3901 |
| 25 |  |  |  | 546.5191 |  |

(s. Tempelmeier (2008))# Beispiel Exponentielle Glättung mit Trendkorrektur $(\alpha=0.1)$ 

Mengeneinheiten
![img-0.jpeg](img-0.jpeg)# Beispiel Exponentielle Glättung mit Trendkorrektur $(\alpha=0.1)$ 

Mengeneinheiten
![img-1.jpeg](img-1.jpeg)# Beispiel Exponentielle Glättung mit Trendkorrektur $(\alpha=0.1)$ 

Mengeneinheiten
![img-2.jpeg](img-2.jpeg)# Beispiel Verfahren von Holt $(\alpha=0.1, \beta=0.2)$ 

Mengeneinheiten
![img-3.jpeg](img-3.jpeg)Beispiel Verfahren von Holt $(\alpha=0.1, \beta=0.2)$
Mengeneinheiten
![img-4.jpeg](img-4.jpeg)Beispiel Verfahren von Holt $(\alpha=0.1, \beta=0.2)$
Mengeneinheiten
![img-5.jpeg](img-5.jpeg)# Nachfrageprognose bei saisonalen SchwankungenNachfrageprognose bei saisonalen Schwankungen# Nachfrageprognose bei saisonalen Schwankungen 

## Beispiel Saisonale Nachfrageschwankungen

| Jahr $t$ | Quartal $m$ |  |  |  | Summe |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | 1 | 2 | 3 | 4 |  |
| 1 | 289 | 410 | 301 | 213 | 1213 |
| 2 | 212 | 371 | 374 | 333 | 1290 |
| 3 | 293 | 441 | 411 | 363 | 1508 |
| 4 | 324 | 462 | 379 | 301 | 1466 |
| 5 | 347 | 520 | 540 | 521 | 1928 |
| 6 | 381 | 594 | 573 | 504 | 2052 |
| 7 | 444 | 592 | 571 | 507 | 2114 |

(vgl. Tempelmeier (2008))# Nachfrageprognose bei saisonalen Schwankungen 

## Beispiel Saisonale Nachfrageschwankungen

Nachfragemenge
![img-6.jpeg](img-6.jpeg)# Beispiel Saisonale Nachfrageschwankungen 

## Autokorrelationskoeffizient $\rho(\tau)$

![img-7.jpeg](img-7.jpeg)# Autokorrelationskoeffizient 

(bezüglich einer Zeitverschiebung von $\tau$ Perioden)

$$
\rho(\tau)=\frac{\sum_{t=1}^{T-\tau} y_{t} \cdot y_{t+\tau}-\frac{1}{T-\tau} \cdot \sum_{t=1}^{T-\tau} y_{t} \cdot \sum_{t=1+\tau}^{T} y_{t}}{\sqrt{\left(\sum_{t=1}^{T-\tau} y_{t}^{2}-\frac{1}{T-\tau} \cdot\left(\sum_{t=1}^{T-\tau} y_{t}\right)^{2}\right) \cdot\left(\sum_{t=1+\tau}^{T} y_{t}^{2}-\frac{1}{T-\tau} \cdot\left(\sum_{t=1+\tau}^{T} y_{t}\right)^{2}\right)}
$$# Nachfrageprognose bei saisonalen Schwankungen 

Autokorrelogramm für eine Zeitreihe mit saisonalem Verlauf $\rho(\tau)$
![img-8.jpeg](img-8.jpeg)

Die Autokorrelationsfunktion $\rho(\tau)$ schwankt um 0 , weicht aber in regelmäßigen Abständen systematisch davon ab.# Nachfrageprognose bei saisonalen Schwankungen 

Autokorrelogramm für eine Zeitreihe mit trendförmigem Verlauf $\rho(\tau)$
![img-9.jpeg](img-9.jpeg)

Die Autokorrelationsfunktion $\rho(\tau)$ verläuft im positiven Bereich, wenngleich fallend, d. h. mit abnehmender Korrelation.# Beispiel Saisonale Nachfrageschwankungen 

## Autokorrelationskoeffizient $\rho(\tau)$

![img-10.jpeg](img-10.jpeg)# Nachfrageprognose bei saisonalen Schwankungen: Saisonbereinigung# Nachfrageprognose bei saisonalen Schwankungen 

Saisonbereinigung im multiplikativen Modell

$$
Y_{\text {saisonbereinigt }}=\frac{Y}{S}=\frac{T \cdot C \cdot S \cdot I}{S}=T \cdot C \cdot I
$$

$\Longleftrightarrow$ Zeitreihenmodell: $Y=\underset{\uparrow}{S} \cdot Y_{\text {saisonbereinigt }}$
Saisonfaktor
glatte Komponente

$$
T \cdot C=\frac{Y}{S \cdot I}=\frac{T \cdot C \cdot S \cdot I}{S \cdot I}
$$# Bestimmung der Saisonfaktoren 

Isolierung der glatten Komponente

$$
S \cdot I=\frac{T \cdot C \cdot S \cdot I}{T \cdot C} \quad(\text {,Ratio to Moving Average") }
$$

Schätzung der glatten Komponente
(gleitende Durchschnitte (,,moving averages") der Ordnung $n$ )

$$
\operatorname{tc}_{t m}=\frac{1}{2 \cdot k+1} \cdot \sum_{j=t-k}^{t+k} y_{j} \quad(n=2 \cdot k+1)
$$

... bei gerader Gliederanzahl (d. h. Ordnung $n=2 \cdot k$ ):

$$
\operatorname{tc}_{t m}=\frac{1}{2 \cdot k} \cdot\left(0.5 \cdot y_{t-k}+\sum_{j=t-k+1}^{t+k-1} y_{j}+0.5 \cdot y_{t+k}\right) \quad(n=2 \cdot k)
$$

Schätzung der Saisonfaktoren (aus Daten über $n$ Jahre hinweg):

$$
\begin{aligned}
& \mathrm{si}_{t m}=\frac{y_{t m}}{\operatorname{tc}_{t m}} \\
& s_{m}=\frac{1}{n} \cdot \sum_{t=1}^{n} \mathrm{si}_{t m} \quad \text { (für alle Saisonperioden } m \text { eines Jahres) }
\end{aligned}
$$# Beispiel Saisonale Nachfrageschwankungen 

| Jahr $t$ | Quartal $m$ |  |  |  | Summe |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | 1 | 2 | 3 | 4 |  |
| 1 | 289 | 410 | 301 | 213 | 1213 |
| 2 | 212 | 371 | 374 | 333 | 1290 |
| 3 | 293 | 441 | 411 | 363 | 1508 |
| 4 | 324 | 462 | 379 | 301 | 1466 |
| 5 | 347 | 520 | 540 | 521 | 1928 |
| 6 | 381 | 594 | 573 | 504 | 2052 |
| 7 | 444 | 592 | 571 | 507 | 2114 |

(vgl. Tempelmeier (2008))# Bestimmung der Saisonfaktoren 

## Beispiel Saisonale Nachfrageschwankungen

$\mathrm{tC}_{13}=\frac{0.5 \cdot y_{11}+y_{12}+y_{13}+y_{14}+0.5 \cdot y_{21}}{4}=293.63$
$\mathrm{tC}_{14}=\frac{0.5 \cdot y_{12}+y_{13}+y_{14}+y_{21}+0.5 \cdot y_{22}}{4}=279.13$
$\mathrm{tC}_{21}=\frac{0.5 \cdot y_{13}+y_{14}+y_{21}+y_{22}+0.5 \cdot y_{23}}{4}=283.38$
$\mathrm{tC}_{22}=\frac{0.5 \cdot y_{14}+y_{21}+y_{22}+y_{23}+0.5 \cdot y_{24}}{4}=307.50$
USW.# Beispiel Saisonale Nachfrageschwankungen 

$\mathrm{tc}_{13}=\frac{0.5 \cdot y_{11}+y_{12}+y_{13}+y_{14}+0.5 \cdot y_{21}}{4}=293.63, \mathrm{si}_{13}=\frac{y_{13}}{\mathrm{tc}_{13}}=\frac{301}{293.63}=1.0251$
$\mathrm{tc}_{14}=\frac{0.5 \cdot y_{12}+y_{13}+y_{14}+y_{21}+0.5 \cdot y_{22}}{4}=279.13, \mathrm{si}_{14}=\frac{y_{14}}{\mathrm{tc}_{14}}=\frac{213}{279.13}=0.7631$
$\mathrm{tc}_{21}=\frac{0.5 \cdot y_{13}+y_{14}+y_{21}+y_{22}+0.5 \cdot y_{23}}{4}=283.38, \mathrm{si}_{21}=\frac{y_{21}}{\mathrm{tc}_{21}}=\frac{212}{283.38}=0.7481$
$\mathrm{tc}_{22}=\frac{0.5 \cdot y_{14}+y_{21}+y_{22}+y_{23}+0.5 \cdot y_{24}}{4}=307.50, \mathrm{si}_{22}=\frac{y_{22}}{\mathrm{tc}_{22}}=\frac{371}{307.50}=1.2065$
usw.| Jahr $t$ | Quartal $m$ | Beobachtung $y_{t m}$ | glatte Komponente $\mathrm{tc}_{t m}$ | $\mathrm{si}_{t m}$ |
| :--: | :--: | :--: | :--: | :--: |
| 1 | 1 | 289 |  |  |
| 1 | 2 | 410 |  |  |
| 1 | 3 | 301 | 293.63 | 1.025117071 |
| 1 | 4 | 213 | 279.13 | 0.763098970 |
| 2 | 1 | 212 | 283.38 | 0.748125276 |
| 2 | 2 | 371 | 307.50 | 1.206504065 |
| 2 | 3 | 374 | 332.63 | 1.124389327 |
| 2 | 4 | 333 | 351.50 | 0.947368421 |
| 3 | 1 | 293 | 364.88 | 0.803014731 |
| 3 | 2 | 441 | 373.25 | 1.181513731 |
| 3 | 3 | 411 | 380.88 | 1.079094191 |
| 3 | 4 | 363 | 387.38 | 0.937076476 |
| 4 | 1 | 324 | 386.00 | 0.839378238 |
| 4 | 2 | 462 | 374.25 | 1.234468938 |
| 4 | 3 | 379 | 369.38 | 1.026057530 |
| 4 | 4 | 301 | 379.50 | 0.793148880 |
| 5 | 1 | 347 | 406.88 | 0.852841782 |
| 5 | 2 | 520 | 454.50 | 1.144114411 |
| 5 | 3 | 540 | 486.25 | 1.110539846 |
| 5 | 4 | 521 | 499.75 | 1.042521261 |
| 6 | 1 | 381 | 513.13 | 0.742509135 |
| 6 | 2 | 594 | 515.13 | 1.153118175 |
| 6 | 3 | 573 | 520.88 | 1.100071994 |
| 6 | 4 | 504 | 528.50 | 0.953642384 |
| 7 | 1 | 444 | 528.00 | 0.840909091 |
| 7 | 2 | 592 | 528.13 | 1.120946746 |
| 7 | 3 | 571 |  |  |
| 7 | 4 | 507 |  |  |# Beispiel Saisonale Nachfrageschwankungen 

Nachfragemenge
![img-11.jpeg](img-11.jpeg)# Beispiel Saisonale Nachfrageschwankungen 

![img-12.jpeg](img-12.jpeg)# Beispiel Saisonale Nachfrageschwankungen 

Saisonfaktoren $\mathrm{si}_{t m}$ :

| Jahr $t$ | Quartal $m$ |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | 1 | 2 | 3 | 4 |  |
| 1 | - | - | 1.0251171 | 0.7630990 |  |
| 2 | 0.7481253 | 1.2065041 | 1.1243893 | 0.9473684 |  |
| 3 | 0.8030147 | 1.1815137 | 1.0790942 | 0.9370765 |  |
| 4 | 0.8393782 | 1.2344689 | 1.0260575 | 0.7931489 |  |
| 5 | 0.8528418 | 1.1441144 | 1.1105398 | 1.0425213 |  |
| 6 | 0.7425091 | 1.1531182 | 1.1000720 | 0.9536424 |  |
| 7 | 0.8409091 | 1.1209467 | - | - |  |
| Durchschnitt | 0.8044630 | 1.1734443 | 1.0775450 | 0.9061427 | 3.9615951 |Schätzung der Saisonfaktoren (aus Daten über $n$ Jahre hinweg):

$$
\begin{aligned}
& \mathrm{si}_{t m}=\frac{y_{t m}}{\mathrm{tc}_{t m}} \\
& s_{m}=\frac{1}{n} \cdot \sum_{t=1}^{n} \mathrm{si}_{t m}
\end{aligned}
$$

(für alle Saisonperioden $m$ eines Jahres)
Sei $M$ die Anzahl Saisonperioden, dann ist

$$
\hat{s}_{m}=s_{m} \cdot \frac{M}{\sum_{m=1}^{M} s_{m}}
$$

ein Schätzwert für den standardisierten Saisonfaktor der Saisonperiode $m$.# Beispiel Saisonale Nachfrageschwankungen 

Saisonfaktoren $\mathrm{si}_{t m}$ :

| Jahr $t$ | Quartal $m$ |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | 1 | 2 | 3 | 4 |  |
| 1 | - | - | 1.0251171 | 0.7630990 |  |
| 2 | 0.7481253 | 1.2065041 | 1.1243893 | 0.9473684 |  |
| 3 | 0.8030147 | 1.1815137 | 1.0790942 | 0.9370765 |  |
| 4 | 0.8393782 | 1.2344689 | 1.0260575 | 0.7931489 |  |
| 5 | 0.8528418 | 1.1441144 | 1.1105398 | 1.0425213 |  |
| 6 | 0.7425091 | 1.1531182 | 1.1000720 | 0.9536424 |  |
| 7 | 0.8409091 | 1.1209467 | - | - |  |
| Durchschnitt | 0.8044630 | 1.1734443 | 1.0775450 | 0.9061427 | 3.9615951 |
| Durchschnitt <br> (standardisiert) | 0.8122617 | 1.1848201 | 1.0879910 | 0.9149272 | 4.0000000 |# Beispiel Saisonale Nachfrageschwankungen 

![img-13.jpeg](img-13.jpeg)$\mathrm{tci}_{t}=\frac{y_{t}}{\widehat{s}_{m(t)}}$
Anpassung der Prognose bei konstantem Niveau der Nachfragemengen:

$$
p_{t+1}=y_{t}^{(1) s} \cdot \widehat{s}_{m(t+1)}=\left(\alpha \cdot \frac{y_{t}}{\widehat{s}_{m(t)}}+(1-\alpha) \cdot y_{t-1}^{(1) s}\right) \cdot \widehat{s}_{m(t+1)}
$$

Anpassung der Prognose bei trendförmigem Verlauf der Nachfragemengen:

$$
p_{t+i}=\underbrace{\left(\widehat{a}_{t}+\widehat{b}_{t} \cdot j\right)}_{\text {Schätzung }} \cdot \widehat{s}_{m(t+i)}
$$

Schätzung auf Basis der saisonbereinigten Beobachtungswerte tci ${ }_{t}$# Beispiel Saisonale Nachfrageschwankungen 

Trendgeradenschätzung für die saisonbereingte Zeitreihe (Startwerte: $\widehat{a}_{0}=348.4505, \widehat{b}_{0}=7.3461$ )
$y_{t}=304.4543+8.5885 \cdot t$# Beispiel Saisonale Nachfrageschwankungen 

Trendgeradenschätzung für die saisonbereingte Zeitreihe (Startwerte: $\widehat{a}_{0}=348.4505, \widehat{b}_{0}=7.3461$ )
$y_{t}=304.4543+8.5885 \cdot t$
Prognosewerte ohne Berücksichtigung des Saisoneinflusses
$p_{29}=304.4543+8.5885 \cdot 29=553.5208$
$p_{30}=304.4543+8.5885 \cdot 30=562.1093$
$p_{31}=304.4543+8.5885 \cdot 31=570.6978$
$p_{32}=304.4543+8.5885 \cdot 32=579.2863$# Beispiel Saisonale Nachfrageschwankungen 

Trendgeradenschätzung für die saisonbereingte Zeitreihe (Startwerte: $\widehat{a}_{0}=348.4505, \widehat{b}_{0}=7.3461$ )
$y_{t}=304.4543+8.5885 \cdot t$
Prognosewerte mit Berücksichtigung des Saisoneinflusses
$p_{29}=553.5208 \cdot 0.8123=449.6249$
$p_{30}=562.1093 \cdot 1.1848=665.9871$
$p_{31}=570.6978 \cdot 1.0880=620.9192$
$p_{32}=579.2863 \cdot 0.9149=529.9890$# Beispiel Saisonale Nachfrageschwankungen 

Nachfragemenge
![img-14.jpeg](img-14.jpeg)# Beispiel Saisonale Nachfrageschwankungen 

Nachfragemenge
![img-15.jpeg](img-15.jpeg)# Nachfrageprognose bei saisonalen Schwankungen: Verfahren von Holt/WintersVerwendung von drei Glättungsparametern
Achsenabschnitt der Trendgeraden
(aktuelles Nachfragemengenniveau zum Zeitpunkt $t$ )

$$
\widehat{a}_{t}=\alpha \cdot \frac{y_{t}}{\widehat{s}_{m(t)}}+(1-\alpha) \cdot\left(\widehat{a}_{t-1}+\widehat{b}_{t-1}\right)
$$

Steigung der Trendgeraden

$$
\widehat{b}_{t}=\beta \cdot\left(\widehat{a}_{t}-\widehat{a}_{t-1}\right)+(1-\beta) \cdot \widehat{b}_{t-1}
$$

# Saisonfaktoren 

$$
\widehat{s}_{t}=\gamma \cdot \frac{y_{t}}{\widehat{a}_{t}}+(1-\gamma) \cdot \widehat{s}_{m(t)}
$$

## Prognosewerte

$$
p_{t+i}=\left(\widehat{a}_{t}+\widehat{b}_{t} \cdot i\right) \cdot \widehat{s}_{m(t+i)}
$$

[^0]
[^0]:    (c) Univ.-Prof. Dr. Michael Manitz

    Produktionswirtschaft II# Beispiel Saisonale Nachfrageschwankungen 

Achsenabschnitt der Trendgeraden $(\alpha=0.2)$
$\widehat{a}_{1}=0.2 \cdot \frac{289}{0.8123}+(1-0.2) \cdot(304.4543+8.5885)=321.5936$
Steigung der Trendgeraden $(\beta=0.1)$
$\widehat{b}_{1}=0.1 \cdot(321.5936-304.4543)+(1-0.1) \cdot 8.5885=9.4436$
Saisonfaktoren $(\gamma=0.3)$
$\widehat{s}_{1}=0.3 \cdot \frac{289}{321.5936}+(1-0.3) \cdot 0.8123=0.8382$
Prognosewerte
$p_{2}=(321.5936+9.4436) \cdot 1.1848=392.2195$![img-16.jpeg](img-16.jpeg)# Multivariate Prognoseverfahren: 

(multiple) lineare
Regressionsmodelle# Nachfragemenge zum Zeitpunkt $t$ 

(die abhängige Größe, ,,abhängige, erklärte Variable")

$$
\begin{aligned}
& y_{t}=\underbrace{\beta_{0} \cdot x_{0 t}+\beta_{1} \cdot x_{1 t}+\beta_{2} \cdot x_{2 t}+\cdots+\beta_{m} \cdot x_{m t}}_{\text {systematische, erklärbare Komponente für den Zeitpunkt } t}+\epsilon_{t} \\
& y_{t}=\beta_{0} \cdot x_{0 t}+\beta_{1} \cdot x_{1 t}+\beta_{2} \cdot x_{2 t}+\cdots+\beta_{m} \cdot x_{m t}+\underbrace{\epsilon_{t}}_{\text {Restkomponente } I}
\end{aligned}
$$

## Einflussgröße $j$ zum Zeitpunkt $t$

(die die Nachfragemenge erklärenden Größen, ,,unabhängige, erklärende Variable")
$x_{j t}$ (gegeben: beobachtet und/oder prognostiziert)

$$
(j=0,1,2, \ldots, m ; t=1,2, \ldots, n, n+1, n+2, \ldots)
$$

Stärke des Einflusses $j$ (,,Regressionskoeffizient")
$\beta_{j}$ (noch zu bestimmen bzw. effizient zu schätzen) $(j=0,1,2, \ldots, m)$Schätzwerte für die Regressionskoeffizienten
$\widehat{\beta_{j}}$ bzw. $b_{j}$
$j=0,1,2, \ldots, m)$
geschätzte ex-post-Prognosewerte
$\widehat{y}_{t}$ bzw. $p_{t}$
$(t=1,2, \ldots, n)$
Prognosefunktion

$$
p_{t}=b_{0} \cdot x_{0 t}+b_{1} \cdot x_{1 t}+b_{2} \cdot x_{2 t}+\cdots+b_{m} \cdot x_{m t}=\sum_{j=0}^{m} b_{j} \cdot x_{j t}
$$

$$
(t=1,2, \ldots)
$$Schätzwerte für die Regressionskoeffizienten
$\widehat{\beta_{j}}$ bzw. $b_{j}$
$(j=0,1,2, \ldots, m)$
geschätzte ex-post-Prognosewerte
$\widehat{y}_{t}$ bzw. $p_{t}$
$(t=1,2, \ldots, n)$
Prognosefunktion

$$
p_{t}=b_{0} \cdot x_{0 t}+b_{1} \cdot x_{1 t}+b_{2} \cdot x_{2 t}+\cdots+b_{m} \cdot x_{m t}=\sum_{j=0}^{m} b_{j} \cdot x_{j t} \quad(t=1,2, \ldots)
$$

Spezialfall: Trendgerade

$$
\begin{aligned}
p_{t} & =b_{0} \cdot 1+b_{1} \cdot x_{1 t} \\
& =b_{0}+b_{1} \cdot k
\end{aligned}
$$

$(k=t-n+1, t-n+2, \ldots, t-1, t)$# Spezialfall: TrendgeradeDie Regressionskoeffizienten $b_{j}$ werden üblicherweise so geschätzt, dass die Summe der quadrierten Prognosefehler (SQA) minimiert wird.

$$
\begin{aligned}
& \operatorname{SQA}\left(b_{0}, b_{1}\right):=\sum_{k=t-n+1}^{t}\left(y_{t}-p_{t}\right)^{2}=\sum_{k=t-n+1}^{t}\left(y_{t}-\left(b_{0}+b_{1} \cdot k\right)\right)^{2} \\
& \frac{\mathrm{~d} \operatorname{SQA}\left(b_{0}, b_{1}\right)}{\mathrm{d} b_{1}}=-2 \cdot \sum_{k=t-n+1}^{t}\left(y_{k}-\left(b_{0}+b_{1} \cdot k\right) \cdot k \stackrel{!}{=} 0\right. \\
& \Longleftrightarrow \sum_{k=t-n+1}^{t}\left(y_{k}-b_{0}-b_{1} \cdot k\right) \cdot k=0 \\
& \Longleftrightarrow \sum_{k=t-n+1}^{t} y_{k} \cdot k-\sum_{k=t-n+1}^{t} b_{0} \cdot k-\sum_{k=t-n+1}^{t} b_{1} \cdot k^{2}=0 \\
& \Longleftrightarrow \sum_{k=t-n+1}^{t} y_{k} \cdot k=b_{0} \cdot \sum_{k=t-n+1}^{t} k+b_{1} \cdot \sum_{k=t-n+1}^{t} k^{2}
\end{aligned}
$$Lineares Gleichungssystem:
(1) $\sum_{k=t-n+1}^{t} y_{k}=n \cdot b_{0}+b_{1} \cdot \sum_{k=t-n+1}^{t} k$
(2) $\sum_{k=t-n+1}^{t} y_{k} \cdot k=b_{0} \cdot \sum_{k=t-n+1}^{t} k+b_{1} \cdot \sum_{k=t-n+1}^{t} k^{2}$Lineares Gleichungssystem:
(1) $\sum_{k=t-n+1}^{t} y_{k}=n \cdot b_{0}+b_{1} \cdot \sum_{k=t-n+1}^{t} k$
(2) $\sum_{k=t-n+1}^{t} y_{k} \cdot k=b_{0} \cdot \sum_{k=t-n+1}^{t} k+b_{1} \cdot \sum_{k=t-n+1}^{t} k^{2}$

Lösung des Gleichungssystems:
(1) $b_{0}=\frac{\sum_{k=t-n+1}^{t} k^{2} \cdot \sum_{k=t-n+1}^{t} y_{k}-\sum_{k=t-n+1}^{t} k \cdot \sum_{k=t-n+1}^{t} k \cdot y_{k}}{n \cdot \sum_{k=t-n+1}^{t} k^{2}-\left(\sum_{k=t-n+1}^{t} k\right)^{2}}$Lineares Gleichungssystem:
(1) $\sum_{k=t-n+1}^{t} y_{k}=n \cdot b_{0}+b_{1} \cdot \sum_{k=t-n+1}^{t} k$
(2) $\sum_{k=t-n+1}^{t} y_{k} \cdot k=b_{0} \cdot \sum_{k=t-n+1}^{t} k+b_{1} \cdot \sum_{k=t-n+1}^{t} k^{2}$

Lösung des Gleichungssystems:
(2) $b_{1}=\frac{n \cdot \sum_{k=t-n+1}^{t} k \cdot y_{k}-\sum_{k=t-n+1}^{t} k \cdot \sum_{k=t-n+1}^{t} y_{k}}{n \cdot \sum_{k=t-n+1}^{t} k^{2}-\left(\sum_{k=t-n+1}^{t} k\right)^{2}} \quad$Lineares Gleichungssystem (in Matrixschreibweise):
$\left[\begin{array}{cc}\sum_{k=t-n+1}^{t} & y_{k} \cdot k \\ \sum_{k=t-n+1}^{t} & y_{k} \cdot k\end{array}\right]=\left[\begin{array}{cc}n & \sum_{k=t-n+1}^{t} k \\ \sum_{k=t-n+1}^{t} & k \sum_{k=t-n+1}^{t} k^{2}\end{array}\right] \cdot\left[\begin{array}{l}b_{0} \\ b_{1}\end{array}\right]$
Es sei dann:
$\mathbf{y}:=\left[\begin{array}{l}y_{1} \\ y_{2}\end{array}\right]_{(2 \times 1-\text { Matrix })} \quad \mathbf{X}:=\left[\begin{array}{ll}1 & x_{11} \\ 1 & x_{12}\end{array}\right]_{(2 \times 2-\text { Matrix })} \quad \mathbf{b}:=\left[\begin{array}{l}b_{0} \\ b_{1}\end{array}\right]_{(2 \times 1-\text { Matrix })}$
Koeffizientenschätzung (Normalgleichungssystem in Matrixschreibweise):
$\left(\mathbf{X}^{\mathbf{T}} \mathbf{X}\right)^{-1} \mathbf{X}_{(2 \times 2)}^{\mathbf{T}} \cdot \mathbf{y}_{(2 \times 1)}=\left(\mathbf{X}^{\mathbf{T}} \mathbf{X}\right)^{-1} \mathbf{X}^{\mathbf{T}} \mathbf{X}_{(2 \times 2)} \cdot \mathbf{b}_{(2 \times 1)}=\mathbf{b}_{(2 \times 1)}$
$\mathbf{b}_{(2 \times 1)}=\left(\mathbf{X}^{\mathbf{T}} \mathbf{X}\right)^{-1} \mathbf{X}_{(2 \times 2)}^{\mathbf{T}} \cdot \mathbf{y}_{(2 \times 1)}$
$\mathbf{p}_{(2 \times 1)}=\mathbf{X}_{(2 \times 2)} \cdot \mathbf{b}_{(2 \times 1)}$# Beispiel Exponentielle Glättung mit Trendkorrektur $(\alpha=0.1)$ 

Nachfragedaten für 1997:

| $t$ | $y_{t}$ | $y_{t}^{(1)}$ | $y_{t}^{(2)}$ | $\widehat{a}_{t}$ | $\widehat{b}_{t}$ | $p_{t+1}$ | $e_{t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 |  | 177.0800 | 79.1600 | 275.0000 | 10.8800 | 285.8800 |  |
| 1 | 317 | 191.0720 | 90.3512 | 291.7928 | 11.1912 | 302.9840 | 31.1200 |
| 2 | 194 | 191.3648 | 100.4526 | 282.2770 | 10.1014 | 292.3784 | -108.9840 |
| 3 | 312 | 203.4283 | 110.7501 | 296.1065 | 10.2976 | 306.4041 | 19.6216 |
| 4 | 316 | 214.6855 | 121.1437 | 308.2273 | 10.3935 | 318.6208 | 9.5959 |
| 5 | 322 | 225.4169 | 131.5710 | 319.2629 | 10.4273 | 329.6902 | 3.3792 |
| 6 | 334 | 236.2752 | 142.0414 | 330.5091 | 10.4704 | 340.9795 | 4.3098 |
| 7 | 317 | 244.3477 | 152.2721 | 336.4234 | 10.2306 | 346.6540 | -23.9795 |
| 8 | 356 | 255.5129 | 162.5961 | 348.4298 | 10.3241 | 358.7538 | 9.3460 |
| 9 | 428 | 272.7617 | 173.6127 | 371.9106 | 11.0166 | 382.9272 | 69.2462 |
| 10 | 411 | 286.5855 | 184.9100 | 388.2610 | 11.2973 | 399.5583 | 28.0728 |
| 11 | 494 | 307.3269 | 197.1517 | 417.5022 | 12.2417 | 429.7439 | 94.4417 |
| 12 | 412 | 317.7942 | 209.2159 | 426.3726 | 12.0643 | 438.4368 | -17.7439 |

(vgl. Tempelmeier (2008))# Beispiel Exponentielle Glättung mit Trendkorrektur $(\alpha=0.1)$ 

Nachfragedaten für 1998:

| $t$ | $y_{t}$ | $y_{t}^{(1)}$ | $y_{t}^{(2)}$ | $\widehat{a}_{t}$ | $\widehat{b}_{t}$ | $p_{t+1}$ | $e_{t}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 12 | 412 | 317.7942 | 209.2159 | 426.3726 | 12.0643 | 438.4368 | -17.7439 |
| 13 | 460 | 332.0148 | 221.4958 | 442.5338 | 12.2799 | 454.8137 | 21.5632 |
| 14 | 395 | 338.3133 | 233.1776 | 443.4491 | 11.6818 | 455.1309 | -59.8137 |
| 15 | 392 | 343.6820 | 244.2280 | 443.1360 | 11.0504 | 454.1864 | -63.1309 |
| 16 | 447 | 354.0138 | 255.2066 | 452.8210 | 10.9786 | 463.7996 | -7.1864 |
| 17 | 452 | 363.8124 | 266.0672 | 461.5577 | 10.8606 | 472.4183 | -11.7996 |
| 18 | 571 | 384.5312 | 277.9136 | 491.1488 | 11.8464 | 502.9952 | 98.5817 |
| 19 | 517 | 397.7781 | 289.9000 | 505.6561 | 11.9864 | 517.6426 | 14.0048 |
| 20 | 397 | 397.7003 | 300.6800 | 494.7205 | 10.7800 | 505.5005 | -120.6426 |
| 21 | 410 | 398.9302 | 310.5051 | 487.3554 | 9.8250 | 497.1804 | -95.5005 |
| 22 | 579 | 416.9372 | 321.1483 | 512.7261 | 10.6432 | 523.3694 | 81.8196 |
| 23 | 473 | 422.5435 | 331.2878 | 513.7992 | 10.1395 | 523.9387 | -50.3694 |
| 24 | 558 | 436.0891 | 341.7679 | 530.4103 | 10.4801 | 540.8905 | 34.0613 |

(vgl. Tempelmeier (2008))# Beispiel Einfach-Regression bei Vorliegen eines linearen Trends 

Mengeneinheiten
![img-17.jpeg](img-17.jpeg)# Beispiel Einfach-Regression bei Vorliegen eines linearen Trends 

Trendgerade und ex-post- und ex-ante-Prognosewerte:

$$
p_{t}=275.00+10.88 \cdot t
$$

Bestimmtheitsmaß $R^{2}$ (= Anteil der erklärten Variation an der Gesamtvariation, der durch den Verlauf der Trendgeraden erklärt wird) :

$$
R^{2}=66.61768 \%
$$# Erweiterung der linearen Regressionsrechnung um weitere Einflussgrößen# Beispiel 2 Einfach-Regression bei Vorliegen eines linearen Trends 

| Monat $t$ | Jan | Feb | Mar | Apr | Mai | Jun | Jul | Aug | Sep | Okt | Nov | Dez |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Beobachtungen | 30 | 25 | 37 | 43 | 39 | 55 | 66 | 59 | 48 | 53 | 49 | 57 |

Trendgerade und ex-post- und ex-ante-Prognosewerte:

$$
p_{t}=30.364+2.521 \cdot t
$$

Bestimmtheitsmaß $R^{2}$ (= Anteil der erklärten Variation an der Gesamtvariation, der durch den Verlauf der Trendgeraden erklärt wird) :

$$
R^{2}=54.67366 \%
$$# Beispiel II Regression bei Trend und weiteren Einflüssen 

| Monat $t$ | Jan | Feb | Mar | Apr | Mai | Jun | Jul | Aug | Sep | Okt | Nov | Dez |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Beobachtungen | 30 | 25 | 37 | 43 | 39 | 55 | 66 | 59 | 48 | 53 | 49 | 57 |
| Anzahl Werktage | 21 | 20 | 23 | 19 | 21 | 20 | 21 | 23 | 22 | 20 | 21 | 21 |

Trendgerade und ex-post- und ex-ante-Prognosewerte:

$$
p_{t}=19.3439019+2.5024304 \cdot t+0.5304905 \cdot(\text { Anzahl Werktage })
$$

Bestimmtheitsmaß $R^{2}$ (= Anteil der erklärten Variation an der Gesamtvariation, der durch den Verlauf der Trendgeraden erklärt wird) :

$$
R^{2}=54.94158 \%
$$# Beispiel II Regression bei Trend und weiteren Einflüssen 

Nachfragemenge
![img-18.jpeg](img-18.jpeg)# Beispiel II Regression bei Trend und weiteren Einflüssen 

| Monat $t$ | Jan | Feb | Mar | Apr | Mai | Jun | Jul | Aug | Sep | Okt | Nov | Dez |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Beobachtungen | 30 | 25 | 37 | 43 | 39 | 55 | 66 | 59 | 48 | 53 | 49 | 57 |
| Werktage | 21 | 20 | 23 | 19 | 21 | 20 | 21 | 23 | 22 | 20 | 21 | 21 |
| Aktionswochen | 2 | 1 | 1 | 1 | 2 | 1 | 0 | 1 | 2 | 1 | 4 | 3 |

Trendgerade und ex-post- und ex-ante-Prognosewerte:

$$
p_{t}=21.1034446+3.3570323 \cdot t+0.6571497 \cdot \text { Werktage }-6.2995571 \cdot \text { Aktionswochen }
$$

Bestimmtheitsmaß $R^{2}$ (= Anteil der erklärten Variation an der Gesamtvariation, der durch den Verlauf der Trendgeraden erklärt wird) :

$$
R^{2}=79.41516 \%
$$# Beispiel II Regression bei Trend und weiteren Einflüssen 

Nachfragemenge
![img-19.jpeg](img-19.jpeg)![img-20.jpeg](img-20.jpeg)![img-21.jpeg](img-21.jpeg)# Ausgewählte Probleme bei der Einführung und Anwendung eines 

Verfahrens zur Nachfrageprognose# Beispiel Verfahren von Holt 

| $t$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| $y_{t}$ | 60 | 55 | 64 | 51 | 69 | 66 | 83 | 90 | 76 | 95 | 72 | 88 |# Beispiel Verfahren von Holt — MSE 

| $\alpha$ | 0.10 | 0.15 | 0.20 | 0.25 | 0.30 |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $\beta$ |  |  |  |  |  |
| 0.0050 | 112.44 | 106.87 | 103.92 | 102.76 | 102.88 |
| 0.0075 | 112.35 | 106.80 | 103.87 | 102.75 | 102.90 |
| 0.01 | 112.26 | 106.72 | 103.82 | 102.73 | 102.92 |
| 0.05 | 110.94 | 105.69 | 103.28 | 102.75 | 103.46 |
| 0.10 | 109.51 | 104.77 | 103.10 | 103.32 | 104.72 |
| 0.15 | 108.33 | 104.23 | 103.39 | 104.41 | 106.48 |
| 0.20 | 107.37 | 104.04 | 104.09 | 105.92 | 108.64 |
| 0.25 | 106.63 | 104.16 | 105.15 | 107.79 | 111.10 |
| 0.30 | 106.09 | 104.56 | 106.52 | 109.94 | 113.80 |
| 0.35 | 105.73 | 105.22 | 108.15 | 112.31 | 116.64 |
| 0.40 | 105.55 | 106.11 | 110.01 | 114.87 | 119.58 |
| 0.45 | 105.53 | 107.20 | 112.06 | 117.55 | 122.56 |
| 0.50 | 105.67 | 108.47 | 114.27 | 120.31 | 125.55 |
| 0.55 | 105.94 | 109.91 | 116.61 | 123.13 | 128.49 |
| 0.60 | 106.35 | 111.50 | 119.04 | 125.97 | 131.37 |
| 0.65 | 106.89 | 113.22 | 121.56 | 128.79 | 134.15 |
| 0.70 | 107.54 | 115.05 | 124.12 | 131.58 | 136.82 |
| 0.75 | 108.30 | 116.97 | 126.72 | 134.32 | 139.36 |
| 0.80 | 109.16 | 118.98 | 129.33 | 136.97 | 141.75 |
| 0.85 | 110.11 | 121.06 | 131.94 | 139.54 | 144.01 |
| 0.90 | 111.15 | 123.21 | 134.52 | 142.00 | 146.11 |
|  |  |  |  |  |  |

(vgl. Tempelmeier (2008))# Begrenzte Vergangenheit 

Nachfragemenge
![img-22.jpeg](img-22.jpeg)# Begrenzte Vergangenheit 

Nachfragemenge
![img-23.jpeg](img-23.jpeg)# Ausreißer 

## Projektbedarf

- Nachfragemenge auf Grund eines Großauftrags
- Nachfragemenge auf Grund von Sonderaktionen# Ausreißer 

Nachfragemenge
![img-24.jpeg](img-24.jpeg)