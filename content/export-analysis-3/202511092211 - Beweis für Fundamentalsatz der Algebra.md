---
"created date:": 29.10.2025 22:57
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Cauchy Integralformel]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis für Fundamentalsatz der Algebra
parent:
siblings:
child:
mathematical statement: "[[202511091911 - Satz von Liouville|Satz von Liouville]]"
---
# Beweis
Sei
$$p(z) = a_0 + a_1z + \dots + a_nz^n, \quad a_i \in \mathbb{C} \quad \text{mit } a_n \neq 0$$
ein Polynom vom Grad $n \in \mathbb{N}$ (also nicht konstant). Angenommen, $p$ hätte keine Nullstelle in $\mathbb{C}$. Dann wäre die Funktion $f(z) = 1/p(z)$ eine ganze Funktion. Außerdem gilt
$$\lim_{|z|\to\infty} |f(z)| = \lim_{|z|\to\infty} 1/|p(z)| = \lim_{|z|\to\infty} \frac{1}{|z|^n} \cdot \lim_{|z|\to\infty} \frac{1}{|a_n + \frac{a_{n-1}}{z} + \dots + \frac{a_0}{z^n}|} = 0,$$
und damit würde ein $r > 0$ existieren, so dass
$$|f(z)| \le 1 \quad \text{für alle } z \in \mathbb{C} \setminus B_r(0) .$$
Weil $z \mapsto f(z)$ stetig ist, folgt dass $\sup_{z\in\overline{B_r(0)}} |f(z)| < \infty$, also wäre $f$ eine beschränkte ganze Funktion, also nach dem Satz von Liouville ([[202511091911 - Satz von Liouville|Theorem 2.7.9]]) konstant. Dies ist ein Widerspruch dazu, dass $p$ nicht konstant ist.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=86]]


