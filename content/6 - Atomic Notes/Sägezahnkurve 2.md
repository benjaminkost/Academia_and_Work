---
"created date:": 29.01.2025 12:41
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[reelle fourieranalyse]]"
  - "[[Analina I - Klausur-Formelzettel]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-1
  - baby
aliases:
parent:
siblings:
child:
---
# Definition
Die Funktion $f : \mathbb{R} \to \mathbb{R}$ ist 2-periodisch (d.h. $T = 2$) mit:
$f(t) = \begin{cases} 1 - t & \text{für } 0 < t < 2 \\ 0 & \text{für } t = 0 \end{cases}$

**Berechnung der Fourierkoeffizienten:**
Da $T = 2$ ist, gilt $\omega = \frac{2\pi}{T} = \pi$.

Dann ist für $k \geq 1$:
$b_k = \frac{2}{2} \int_{0}^{2} (1 - t) \sin(k\pi t) \,dt = \int_{0}^{2} \sin(k\pi t) \,dt - \int_{0}^{2} t \sin(k\pi t) \,dt$
![[Bildschirmfoto 2025-10-13 um 10.08.41.png]]
Das zweite Integral berechnen wir mit partieller Integration: $u'(t) = \sin(k\pi t)$ und $v(t) = t$, also
$b_k = -\frac{1}{k\pi} \cos(k\pi t) \Big|_0^2 - \left( -\frac{t}{k\pi} \cos(k\pi t) \Big|_0^2 - \int_0^2 -\frac{1}{k\pi} \cos(k\pi t) dt \right)$
$= -\frac{1}{k\pi} (\cos(2k\pi) - \cos(0)) - \left( -\frac{2}{k\pi}\cos(2k\pi) - 0 - \left[ \frac{1}{k^2\pi^2} \sin(k\pi t) \right]_0^2 \right)$
$= -\frac{1}{k\pi} (1 - 1) - \left( -\frac{2}{k\pi} - (\frac{1}{k^2\pi^2} \sin(2k\pi) - \sin(0)) \right)$
$= 0 - \left( -\frac{2}{k\pi} - 0 \right) = \frac{2}{k\pi}$.

Weiter ist
$a_0 = \int_0^2 (1 - t) \underbrace{\cos(0\pi t)}_{=1} dt = \left[ t - \frac{1}{2} t^2 \right]_0^2 = (2 - \frac{4}{2}) - 0 = 0$

und für $k \geq 1$
$a_k = \int_0^2 (1 - t) \cos(k\pi t) dt = \underbrace{\int_0^2 \cos(k\pi t) dt}_{=0} - \int_0^2 t \cos(k\pi t) dt$
$= - \left( \left[ \frac{t}{k\pi} \sin(k\pi t) \right]_0^2 - \int_0^2 \frac{1}{k\pi} \sin(k\pi t) dt \right)$
$= - \left( 0 - \left[ -\frac{1}{k^2\pi^2} \cos(k\pi t) \right]_0^2 \right) = - \left( \frac{1}{k^2\pi^2}(\cos(2k\pi) - \cos(0)) \right) = 0$.

Damit ist das n-te Fourierpolynom von $f$:
$\phi_n(t) = \frac{a_0}{2} + \sum_{k=1}^n (a_k \cos(k\omega t) + b_k \sin(k\omega t)) = \sum_{k=1}^n \frac{2}{k\pi} \sin(k\pi t)$.

Die Fourierpolynome approximieren die Funktion für wachsendes $n$ immer besser:
![[Bildschirmfoto 2025-10-13 um 10.11.35.png]]
# Anmerkung
![[Bildschirmfoto 2025-10-13 um 10.12.21.png]]
Die Fourieranalyse einer periodischen Funktion $f(t)$, d.h. die Berechnung der $a_k$ und $b_k$, und die Fouriersynthese, das Zusammenfügen der Koeffizienten zu einem trigonometrischen Polynom, haben viele Anwendungen.

*   **Menschliches Gehör:** Im menschlichen Ohr sind die Haarzellen des Cortischen Organs jeweils für bestimmte Frequenzen empfindlich. Das Ohr übermittelt dem Gehirn also die Fourierkoeffizienten der von ihm aufgenommenen akustischen Signale.
*   **Signalverarbeitung:** Rauschunterdrückungs- oder Kompressionsverfahren (etwa für MP3) zerlegen Signale mit der Fourieranalyse in ihr Frequenzspektrum, filtern die unerwünschten oder überflüssigen Frequenzen heraus und setzen das Signal dann wieder zusammen.
*   **Regelungstechnik:** Die Wirkung linearer Systeme lässt sich an harmonischen Schwingungen testen und mit der Fourieranalyse für beliebigen periodischen Input vorhersagen.
*   **Synthese von Signalen:** Während Generatoren natürlicherweise harmonische Spannungen liefern, ist man bei technischen Anwendungen zum Beispiel an linearen Sägezahnspannungen interessiert (etwa für die Zeilensteuerung des Elektronenstrahls in einer Bildröhre). Die Fourieranalyse liefert Auskunft darüber, wie man durch Überlagerung harmonischer Schwingungen solche "willkürlichen" Spannungen "synthetisieren" kann.
*   **Partielle Differentialgleichungen:** Auf überraschend andere Weise dient die Fourieranalyse bei Rand-Anfangswert-Problemen partieller Differentialgleichungen und damit bei sehr vielen Problemen der Verfahrens-, Energie- oder Elektrotechnik als wichtiges Hilfsmittel.
## Wiederholung
![[VL-38-Folien-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=3]]
# Visualisierung
![[VL-37-Folien-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=8]]
![[VL-37-Folien-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=9]]
# Beispiele
![[Bildschirmfoto 2025-01-29 um 13.53.20.png]]
![[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=12]]
![[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=13]]

# Referenz
## Verknüpfung
- [[Fourierpolynom]]
- [[Definitionslücken]]
- [[6 - Atomic Notes/Monotonie|Monotonie]]
- [[Satz für partielle Integration]]
- [[Fourierpolynom]]
- [[Sinus]]
## Quellen
- [[VL-37-Folien-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf]]
- [[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf]]
- [[Vorlesung203720-20Teil20320-20Beispiel20Sgezahnkurve.mp4]]
- [[tub_Analysis_I_und_Lineare_Algebra.pdf#page=285]]
## Übungsaufgaben


