---
"created date:": 22.10.2025 15:48
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Laplace und Fourier der 1-Funktion
  - Beispiel 1.3.8
parent:
siblings:
child:
---
# Beispiel
Sei $1 : [0, \infty) \to \mathbb{C}$ die konstante Funktion (siehe Beispiel 1.3.3). Dann ist für $\sigma > 0$
$$
g(t) = \begin{cases} e^{-\sigma t} & \text{für } t \ge 0 \\ 0 & \text{sonst} \end{cases}
$$
und daher für $s = \sigma + i\omega$, $\omega \in \mathbb{R}$
$$
\mathcal{F}[g](\omega) = \int_0^\infty e^{-\sigma t}e^{-i\omega t} dt = \left[ \frac{e^{-(\sigma+i\omega)t}}{-(\sigma+i\omega)} \right]^\infty_{t=0} = \frac{1}{\sigma+i\omega} = \frac{1}{s}.
$$
Dies stimmt mit $\mathcal{L}[1](s)$ überein (siehe Beispiel 1.3.3).
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=53]]



