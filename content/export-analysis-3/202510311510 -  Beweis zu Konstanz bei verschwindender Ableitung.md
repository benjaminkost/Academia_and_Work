---
"created date:": 22.10.2025 20:19
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Differenzierbarkeit]]"
  - "[[202510271310 - Cauchy-Riemann Differentialgleichungen|Cauchy-Riemann Differentialgleichungen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - " Beweis zu Konstanz bei verschwindender Ableitung"
  - Beweis 2.2.14
parent:
siblings:
child:
mathematical statement: "[[202510311410 - Konstanz bei verschwindender Ableitung|Konstanz bei verschwindender Ableitung]]"
---
# Beweis
Die Aussage $f' = 0$ (d.h. (2.5)) ist äquivalent zu (siehe (2.3))
$$ \begin{pmatrix} u_x & u_y \\ v_x & v_y \end{pmatrix} = 0 $$
für die reellwertigen Funktionen $u$ und $v$ auf $U$, d.h. auf der Menge der Paare $(x, y)$ mit $x+iy \in U$. Damit folgt, dass diese Funktionen konstant sind, also existieren $c_1, c_2 \in \mathbb{R}$ so dass
$$
\begin{align*}
u(x, y) &= c_1 \\
v(x, y) &= c_2
\end{align*}
$$
für alle $x + iy \in U$.
Insbesondere folgt
$$ f(z) = u(x, y) + iv(x, y) = c_1 + ic_2 \quad \text{für alle } z = x + iy \in U. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=72]]


