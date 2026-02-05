---
"created date:": 03.02.2025 14:16
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[komplexe fourieranalyse]]"
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
  - n-te komplexe Fourierpolynom
  - n-te Partialsumme der Fourierreihe
  - Definition 1.1.17
  - Partialsummen der Fourierreihe
parent:
siblings:
child:
---
# Definition
Sei $f: \mathbb{R} \to \mathbb{R}$ (oder $f: \mathbb{R} \to \mathbb{C}$) eine stückweise monotone Funktion der Periode $T > 0$, und es sei $\omega = \frac{2\pi}{T}$.

Die **komplexen Fourierkoeffizienten** von $f$ sind:
$c_k = \langle f, e^{ik\omega t} \rangle = \frac{1}{T} \int_{0}^{T} f(t)e^{-ik\omega t} dt, \quad k \in \mathbb{Z}$

Und $\varphi_n(t) = \sum_{k=-n}^{n} c_k e^{ik\omega t}$ ist das **n-te komplexe Fourierpolynom** von $f$ [^1] oder auch $n$-Partialsumme der Fouriereihe[^2].
# Bemerkungen
1.  Die Formeln sind einfacher als die für das reelle Fourierpolynom: Der Faktor vor dem Integral ist $\frac{1}{T}$ statt $\frac{2}{T}$, und die Sonderrolle von $a_0$ ist verschwunden.
2.  Analog zum reellen Fall ist das komplexe Fourierpolynom vom Grad $n$ dasjenige komplexe trigonometrische Polynom vom Grad $n$, das $f$ am besten im quadratischen Mittel approximiert (jetzt mit dem komplexen Skalarprodukt), also in der Norm $\|f\|_{L^2} = \sqrt{\langle f, f \rangle} = \sqrt{\frac{1}{T} \int_{0}^{T} |f(t)|^2 dt}$.
3.  Ist $f$ reellwertig, so sind die Fourierkoeffizienten $a_k$ und $b_k$ reell, und es gilt $c_{-k} = \overline{c_k}$, was die Berechnung der komplexen Fourierkoeffizienten vereinfachen kann.
# Herleitung
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=6]]
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=7]]
# Beispiele
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=7]]
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=8]]
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=9]]
# Referenz
## Übungsaufgaben

## Verknüpfung
- [[Komplexe trigonometrische Polynome]]
- [[Sinus]]
- [[Cosinus]]
- [[Gerade Funktion]]
- [[Ungerade Funktion]]
- [[Fourierkoeffizient]]
- [[Sägezahnkurve]]
- [[Satz für partielle Integration]]
- [[Rechenregeln für Summenzeichen]]
## Quellen
- [[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf]]

[^1]: [[VL-39-Folien-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=3]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=9]]



