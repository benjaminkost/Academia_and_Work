---
"created date:": 22.10.2025 20:32
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[satz]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510271210 - Potenzreihen in C|Potenzreihen in C]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Holomorphie, Ableitung und Stammfunktion von Potenzreihen
  - Theorem 2.3.6
parent:
siblings:
child:
proof:
---
# Satz
Folgendes Theorem zeigt, dass Potenzreihen holomorph auf ihrem Konvergenzbereich sind, und gibt gleichzeitig die Ableitung und eine Stammfunktion als Potenzreihe.
Sei $P(z) = \sum_{k=0}^\infty a_k(z - z_0)^k$ eine Potenzreihe mit Konvergenzradius $R > 0$ um den Entwicklungspunkt $z_0 \in \mathbb{C}$. Dann gilt:
(i) $Q(z) = \sum_{k=1}^\infty k a_k(z - z_0)^{k-1}$ ist die Ableitung von $P(z)$ auf $B_R(z_0)$.
(ii) $T(z) = \sum_{k=0}^\infty \frac{a_k}{k+1} (z - z_0)^{k+1}$ ist eine Stammfunktion von $P(z)$ auf $B_R(z_0)$.
[^1]

# Beispiele


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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=74]]


