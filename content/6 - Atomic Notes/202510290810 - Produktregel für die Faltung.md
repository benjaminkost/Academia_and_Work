---
"created date:": 22.10.2025 19:02
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510271610 - Faltung und Laplacetransformation|Faltung und Laplacetransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Produktregel für die Faltung
  - Lemma 1.3.25
parent:
siblings:
child:
proof: "[[202510290910 - Beweis für Produktregel für die Faltung|Beweis für Produktregel für die Faltung]]"
---
# Lemma
Seien $f, g : [0,\infty) \to \mathbb{C}$ Laplace-transformierbar in $s \in \mathbb{C}$, und $\int_0^\infty \int_0^\infty |g(t)f(\tau)e^{-s(t+\tau)}|d\tau dt < \infty$. Dann gilt
$$
(\mathcal{L}[f] \cdot \mathcal{L}[g])(s) = \mathcal{L}[f * g](s).
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=58]]


