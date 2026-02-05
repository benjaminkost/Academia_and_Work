---
"created date:": 29.10.2025 23:41
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Laurentreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beispiele
aliases:
  - Laurent-Reihe von sin(z) durch z
  - Beispiel 2.9.6
parent:
siblings:
child:
---
# Beispiel
Wegen
$$\sin(z) := \sum_{k=0}^\infty \frac{(-1)^k}{(2k+1)!} z^{2k+1}$$
ist die Laurent-Reihe von
$$f(z) = \frac{\sin(z)}{z}$$
um $z_0 = 0$ gegeben durch
$$f(z) := \sum_{k=0}^\infty \frac{(-1)^k}{(2k+1)!} z^{2k} \quad \text{für } z \in \mathbb{C}^\times.$$
(Hier ist $A_{0,\infty}(0) = \mathbb{C}^\times$.)
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=94]]


