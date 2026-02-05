---
"created date:": 29.10.2025 23:58
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301110 - Isolierte Singularität|Isolierte Singularität]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - bemerkung
aliases:
  - Charakterisierung über den Hauptteil
  - Bemerkung 2.10.7
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Mit anderen Worten:
(i) $z_0$ ist hebbar $\Leftrightarrow$ der Hauptteil verschwindet, d.h. $f(z) = \sum_{k=0}^\infty c_k (z-z_0)^k$
(ii) $z_0$ ist ein Pol $m$-ter Ordnung $\Leftrightarrow$ der Hauptteil bricht ab, d.h. $f(z) = \underbrace{\frac{c_{-m}}{(z-z_0)^m} + \dots + \frac{c_{-1}}{z-z_0}}_{\text{Hauptteil}} + \underbrace{\sum_{k=0}^\infty c_k(z-z_0)^k}_{\text{Nebenteil}}$
(iii) $z_0$ ist eine wesentliche Singularität $\Leftrightarrow$ der Hauptteil bricht nicht ab: $\forall m \in \mathbb{N} \exists k > m$ so dass $c_{-k} \neq 0$.
Das Verhalten bei wesentlichen Singularitäten ist sehr komplex, wie folgender Satz zeigt: [[202511110211 - Casorati-Weierstraß]]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=96]]


