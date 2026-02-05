---
"created date:": 22.10.2025 20:43
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510290410 - Die Exponentialfunktion und ihre Verwandten|Die Exponentialfunktion und ihre Verwandten]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis zu Euler-Darstellung von sin und cos
parent:
siblings:
child:
mathematical statement: "[[202511010611 - Identität zu Euler-Darstellung von sin und cos|Identität zu Euler-Darstellung von sin und cos]]"
---
# Beweis
Exemplarisch zeigen wir dies für cos z. Es gilt für $k \in \mathbb{N}_0$
$$ i^{2k} + (-i)^{2k} = (-1)^k + (-1)^k = 2 \cdot (-1)^k $$
$$ i^{2k+1} + (-i)^{2k+1} = i[(-1)^k - (-1)^k] = 0. $$
Daher folgt die Behauptung mit
$$ e^{iz} + e^{-iz} = \sum_{k=0}^{\infty} \frac{i^k + (-i)^k}{k!} z^k. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=75]]


