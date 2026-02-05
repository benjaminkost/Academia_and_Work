---
"created date:": 22.10.2025 20:18
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Differenzierbarkeit]]"
  - "[[202510271310 - Cauchy-Riemann Differentialgleichungen|Cauchy-Riemann Differentialgleichungen]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Beispiel zu Differenzierbarkeit von z hoch 2
  - Beispiel 2.2.12
parent:
siblings:
child:
---
# Beispiel
Sei $f : \mathbb{C} \to \mathbb{C}$ die Funktion $f(z) = z^2$. Dann gilt
$$f(x + iy) = x^2 - y^2 + 2ixy,$$
also
$$
\begin{align*}
u(x, y) &= x^2 - y^2 \\
v(x, y) &= 2xy.
\end{align*}
$$
Die Ableitung der Funktion $\tilde{f}(x, y) = \begin{pmatrix} u(x, y) \\ v(x, y) \end{pmatrix}$ ist damit
$$ d\tilde{f}(x, y) = \begin{pmatrix} u_x & u_y \\ v_x & v_y \end{pmatrix} = \begin{pmatrix} 2x & -2y \\ 2y & 2x \end{pmatrix}. $$
Damit ist leicht zu prüfen, dass die Cauchy-Riemann-Gleichungen erfüllt sind (für alle $(x, y) \in \mathbb{R}^2$), also ist die Funktion $f$ ganz.
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

[^1]: [[tum_KoenigUlbrich-Analysis3EI-WS2526-skript.pdf#page=71



