---
"created date:": 22.10.2025 15:54
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
  - Rechenregeln der Laplacetransformation
parent:
siblings:
child:
proof:
---
# Lemma
Seien $f, g : [0, \infty) \to \mathbb{C}$ in $s \in \mathbb{C}$ Laplace-transformierbar.
(i) **(Linearität):** Seien $\alpha, \beta \in \mathbb{C}$. Dann gilt
$\mathcal{L}[\alpha f + \beta g](s) = \alpha \mathcal{L}[f](s) + \beta \mathcal{L}[g](s).$
(ii) **(Verschiebungsregel):** Sei $a \in \mathbb{C}$ und sei $f$ in $s-a$ Laplace-transformierbar. Dann gilt
$\mathcal{L}[t \to e^{at}f(t)](s) = \mathcal{L}[f](s-a).$
(iii) Sei $c > 0$. Dann gilt
$\mathcal{L}[t \to f(ct)](s) = \frac{1}{c} \mathcal{L}[f](s/c).$
(iv) **(Dämpfungsregel):** Sei $u(t) := \begin{cases} 0 & t < 0 \\ 1 & t \ge 0 \end{cases}$. Dann gilt für $a > 0$
$\mathcal{L}[t \to u(t-a)f(t-a)](s) = e^{-as}\mathcal{L}[f](s).$
[^1]

# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510281410 - Beweis für Rechenregeln der Laplacetransformation]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=54]]


