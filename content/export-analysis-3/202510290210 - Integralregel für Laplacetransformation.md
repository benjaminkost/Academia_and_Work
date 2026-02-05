---
"created date:": 22.10.2025 16:09
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270610 - Eigenschaften der Laplacetransformation|Eigenschaften der Laplacetransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Integralregel für Laplacetransformation
  - Lemma 1.3.21
parent:
siblings:
child:
proof:
---
# Lemma
Sei $f : [0, \infty) \to \mathbb{C}$ stückweise stetig und die Funktion $g : [0, \infty) \to \mathbb{C}$ definiert durch
$$
g(t) := \int_0^t f(\tau) d\tau
$$
sei höchstens exponentiell wachsend (Konvergenzabszisse $\sigma_0$). Dann gilt für alle $s \neq 0$, $\text{Re}(s) > \sigma_0$:
$$
\mathcal{L}[g](s) = \frac{1}{s}\mathcal{L}[f](s).
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
- [[202510290310 - Beweis für Integralregel für Laplacetransformation]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=57]]


