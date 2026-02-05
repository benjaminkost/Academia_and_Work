---
"created date:": 22.10.2025 12:18
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[eigenschaften von fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Dualitätsprinzip, 2. Teil
  - Lemma 1.2.17
parent:
siblings:
child:
proof:
---
# Lemma
Seien $m \in \mathbb{N}$, $a_0, \dots, a_m \in \mathbb{C}$ und
$$ P(z) = a_m z^m + \dots + a_1 z + a_0. $$
Sei $f : \mathbb{R} \to \mathbb{C}$ derart, dass $t \to t^n f(t)$ absolut integrierbar ist für jedes $n \le m$. Dann ist $\hat{f} \in C^m(\mathbb{R})$ und
$$ (a_m i^m \hat{f}^{(m)} + a_{m-1} i^{m-1} \hat{f}^{(m-1)} \dots a_1 i \hat{f}' + a_0 \hat{f})(\omega) = \widehat{P \cdot f}(\omega) \quad \text{für alle } \omega \in \mathbb{R}, $$
wobei $(P \cdot f)(t) := P(t)f(t)$ für alle $t \in \mathbb{R}$.
[^1]

# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510260210 - Dualitätsprinzip, 1.Teil|Dualitätsprinzip, 1.Teil]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=40]]


