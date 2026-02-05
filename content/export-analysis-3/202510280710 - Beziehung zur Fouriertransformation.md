---
"created date:": 22.10.2025 15:46
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
  - bemerkung
  - baby
aliases:
  - Beziehung zur Fouriertransformation
  - Bemerkung 1.3.7
parent:
siblings:
child:
mathematical statement:
proof: "[[202510280810 - Beweis für Beziehung zur Fouriertransformation]]"
---
# Bemerkungen
Es besteht folgende Beziehung zur Fouriertransformation: Sei $f : [0, \infty) \to \mathbb{C}$ und $s = \sigma + i\omega$ mit $\sigma, \omega \in \mathbb{R}$. Sei $g : \mathbb{R} \to \mathbb{C}$ definiert durch
$$
g(t) = \begin{cases} e^{-\sigma t}f(t) & \text{für } t \ge 0 \\ 0 & \text{sonst} \end{cases}.
$$
Dann gilt $\mathcal{L}[f](s) = \mathcal{F}[g](\omega)$.
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



