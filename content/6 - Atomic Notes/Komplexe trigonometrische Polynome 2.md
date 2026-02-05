---
"created date:": 03.02.2025 14:16
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[komplexe fourieranalyse]]"
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
  - grundlagen
  - vl-1
  - baby
aliases:
parent:
siblings:
child:
---
# Definition
Sei $T > 0$ und $\omega = \frac{2\pi}{T}$.

Die komplexwertigen Funktionen der Form
$\sum_{k=-n}^{n} c_k e^{ik\omega t}$, mit $c_k \in \mathbb{C}$,

heißen **komplexe trigonometrische Polynome** vom Grad $n$ oder von der Ordnung $n$. Diese sind $T$-periodisch.
# Herleitung
Wir haben schon gesehen, dass sich Sinus- und Cosinusfunktionen oft bequemer mittels der Euler-Formel durch $e^{i\phi} = \cos(\phi) + i \sin(\phi)$ ersetzen lassen.

Es ist also:
$\cos(\phi) = \text{Re}(e^{i\phi}) = \frac{e^{i\phi} + e^{-i\phi}}{2}$
$\sin(\phi) = \text{Im}(e^{i\phi}) = \frac{e^{i\phi} - e^{-i\phi}}{2i}$

Damit lassen sich trigonometrische Polynome sehr einfach komplex schreiben:

$\phi(t) = \frac{a_0}{2} + \sum_{k=1}^{n} (a_k \cos(k\omega t) + b_k \sin(k\omega t))$
$= \frac{a_0}{2} + \sum_{k=1}^{n} \left( a_k \frac{e^{ik\omega t} + e^{-ik\omega t}}{2} + b_k \frac{e^{ik\omega t} - e^{-ik\omega t}}{2i} \right)$
$= \frac{a_0}{2} + \sum_{k=1}^{n} \left( \frac{a_k}{2} e^{ik\omega t} + \frac{a_k}{2} e^{-ik\omega t} + \frac{b_k}{2i} e^{ik\omega t} - \frac{b_k}{2i} e^{-ik\omega t} \right)$
$= \underbrace{\frac{a_0}{2}}_{=:c_0} + \sum_{k=1}^{n} \left( \underbrace{\left( \frac{a_k}{2} - i \frac{b_k}{2} \right)}_{=:c_k} e^{ik\omega t} + \underbrace{\left( \frac{a_k}{2} + i \frac{b_k}{2} \right)}_{=:c_{-k}} e^{-ik\omega t} \right)$
$= \sum_{k=-n}^{n} c_k e^{ik\omega t}$


![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=5]]
# Beispiele


# Referenz
## Verknüpfung
- [[Orthonormalbasis]]
## Quellen
- [[VL-39-Folien-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=2]]
- [[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf]]
- [[tub_Analysis_I_und_Lineare_Algebra.pdf#page=299]]
## Übungsaufgaben



