---
"created date:": 22.10.2025 15:58
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270610 - Eigenschaften der Laplacetransformation|Eigenschaften der Laplacetransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Laplace-Transformierte von e hoch at
  - Beispiel 1.3.13
parent:
siblings:
child:
---
# Beispiel 
Aus
$$
\mathcal{L}[t\to e^{at}](s) = \frac{1}{s-a} \quad \text{für } s \in \mathbb{C} \text{ und Re}(s) > \text{Re}(a)
$$
(siehe Beispiel 1.3.4) folgt mit $a = i\omega, \omega \in \mathbb{R}$ bzw. $a=-i\omega$
$$
\mathcal{L}[t\to e^{i\omega t}](s) = \frac{1}{s-i\omega} \quad \text{für Re}(s) > 0
$$
$$
\mathcal{L}[t\to e^{-i\omega t}](s) = \frac{1}{s+i\omega} \quad \text{für Re}(s) > 0.
$$
Mit den Identitäten
$$
\cos(\omega t) = \frac{1}{2}(e^{i\omega t} + e^{-i\omega t}) \quad \sin(\omega t) = \frac{1}{2i}(e^{i\omega t} - e^{-i\omega t})
$$
und der Linearität der Laplacetransformation folgt
$$
\mathcal{L}[t\to \cos(\omega t)](s) = \frac{1}{2} \left( \frac{1}{s-i\omega} + \frac{1}{s+i\omega} \right) = \frac{s}{s^2+\omega^2} \quad \text{für Re}(s) > 0
$$
und analog
$$
\mathcal{L}[t\to \sin(\omega t)](s) = \frac{\omega}{s^2+\omega^2} \quad \text{für Re}(s) > 0.
$$
[^1]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=54]]



