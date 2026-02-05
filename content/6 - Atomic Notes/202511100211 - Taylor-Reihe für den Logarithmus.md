---
"created date:": 29.10.2025 23:08
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301010 - Weitere Anwendungen der Cauchy-Integralformel|Weitere Anwendungen der Cauchy-Integralformel]]"
  - "[[202511020311 - Taylor-Entwicklung|Taylor-Entwicklung]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Taylor-Reihe für den Logarithmus
  - Beispiel 2.8.3
  - Gleichung 2.15
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Betrachte die Funktion $f(z) = \text{Log}(1+z)$ auf $U = B_1(0)$. Ihre Ableitungen sind
$$f^{(k)}(z) = \frac{(-1)^{k+1}(k-1)!}{(1+z)^k} \quad \text{für } k \in \mathbb{N},$$
also
$$\begin{aligned}f(0) &= 0 \\f^{(k)}(0) &= (-1)^{k+1}(k-1)! \quad \text{für } k \in \mathbb{N}.\end{aligned}$$
Mit $z_0=0$ erhalten wir die Potenzreihenentwicklung
$$\text{Log}(1+z) = \sum_{k=0}^\infty \frac{f^{(k)}(0)}{k!} z^k = \sum_{k=1}^\infty \frac{(-1)^{k+1}}{k} z^k = \sum_{k=1}^\infty a_k z^k \quad \text{für alle } z \in B_1(0).$$
(2.15)
Die alternative Formel ([[202511100011 - Taylor-Reihe holomorpher Funktionen|Gleichung 2.13]]), d.h.
$$a_k = \frac{1}{2\pi i} \oint_{|\zeta|=r} \frac{\text{Log}(1+\zeta)}{\zeta^{k+1}} d\zeta \quad \text{für } r \in (0, 1)$$
führt auf Integrale, die schwer zu berechnen sind.
[^1]
### Alternative Herleitung für Beispiel 2.8.3
Wir geben eine alternative Herleitung der Taylor-Reihe (2.15). Es gilt (mit der geometrischen Reihe)
$$f'(z) = \frac{1}{1+z} = \sum_{k=0}^\infty (-z)^k \quad \text{für } z \in B_1(0).$$
Andererseits ist nach Definition und Theorem 2.3.6
$$f'(z) = \sum_{k=1}^\infty k a_k z^{k-1} = \sum_{k=0}^\infty (k+1)a_{k+1} z^k.$$
Koeffizientenvergleich (d.h. die Eindeutigkeit von Potenzreihen) gibt daher
$$a_k = \frac{(-1)^{k-1}}{k} = \frac{(-1)^{k+1}}{k}$$
wie behauptet.
[^2]
# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- 
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=88]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=88]]


