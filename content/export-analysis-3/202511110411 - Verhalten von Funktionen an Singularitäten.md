---
"created date:": 30.10.2025 00:01
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
  - satz
aliases:
  - Verhalten von Funktionen an Singularitäten
  - Gleichung 2.22
  - Gleichung 2.23
parent:
siblings:
child:
proof:
---
# Satz
Sei $U \subset \mathbb{C}$ offen und $f: U \to \mathbb{C}$ holomorph. Sei $z_0 \notin U$ eine isolierte Singularität von $f$. Dann gilt:
(i) $z_0$ ist hebbar genau dann, wenn $f$ um $z_0$ beschränkt ist, d.h. wenn $r > 0$ und $C>0$ existieren, so dass
$$|f(z)| \le C \quad \text{für alle } z \in A_{0,r}(z_0). \quad (2.22)$$
(ii) $z_0$ ist ein Pol genau dann, wenn gilt
$$|f(z)| \to \infty \quad \text{für } z \to z_0, \quad(2.23)$$
d.h. wenn für jede Folge $\{z_n\} \subset U$ mit $\lim_{n\to\infty} z_n = z_0$ folgt, dass $\lim_{n\to\infty} |f(z_n)| = \infty$.
[^1]
[[202511110511 - Beweis zu Verhalten von Funktionen an Singularitäten]]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=97]]


