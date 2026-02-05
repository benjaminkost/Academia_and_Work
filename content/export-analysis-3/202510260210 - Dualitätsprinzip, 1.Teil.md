---
"created date:": 22.10.2025 12:13
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
  - Dualitätsprinzip, 1.Teil
  - Lemma 1.2.15
parent:
siblings:
child:
proof: "[[202510260410 - Beweisidee für Dualitätsprinzip, 1.Teil]]"
---
# Lemma
Seien $m \in \mathbb{N}$, $a_0, \dots, a_m \in \mathbb{C}$ und $L$ der Differentialoperator
$$ L[y](t) := a_m y^{(m)}(t) + \dots + a_1 y'(t) + a_0 y(t) $$
für $y: \mathbb{R} \to \mathbb{C}$ m-mal differenzierbar. Sei $f \in C^m(\mathbb{R})$ (d.h. m-mal stetig differenzierbar) und $f^{(n)} \in L^1(\mathbb{R})$ für alle $n \le m$. Dann gilt
$$ \widehat{L[f]}(\omega) = (a_m(i\omega)^m + a_{m-1}(i\omega)^{m-1} + \dots + a_1(i\omega) + a_0)\hat{f}(\omega) \quad \text{für alle } \omega \in \mathbb{R}. $$
[^1]

# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510260510 - Dualitätsprinzip, 2. Teil]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=39]]


