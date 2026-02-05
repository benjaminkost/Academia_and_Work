---
"created date:": 22.10.2025 15:47
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Beziehung zur Fouriertransformation
  - Beweis 1.3.7
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Es gilt
$$
\mathcal{L}[f](\sigma+i\omega) = \int_0^\infty f(t)e^{-(\sigma+i\omega)t} dt = \int_0^\infty f(t)e^{-\sigma t}e^{-i\omega t} dt = \int_{-\infty}^\infty g(t)e^{-i\omega t} dt = \mathcal{F}[g](\omega),
$$
wie behauptet.
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


