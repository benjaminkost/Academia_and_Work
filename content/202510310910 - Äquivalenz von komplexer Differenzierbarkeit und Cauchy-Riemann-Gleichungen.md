---
"created date:": 22.10.2025 20:15
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[satz]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Differenzierbarkeit]]"
  - "[[202510271310 - Cauchy-Riemann Differentialgleichungen|Cauchy-Riemann Differentialgleichungen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Äquivalenz von komplexer Differenzierbarkeit und Cauchy-Riemann-Gleichungen
  - Theorem 2.2.10
parent:
siblings:
child:
proof: "[[202510311110 - Beweis zu Äquivalenz von komplexer Differenzierbarkeit und Cauchy-Riemann-Gleichungen|Beweis zu Äquivalenz von komplexer Differenzierbarkeit und Cauchy-Riemann-Gleichungen]]"
---
# Satz
Sei $U \subset \mathbb{C}$ offen und $f : U \to \mathbb{C}$. Wir schreiben den Realteil von $f$ als $u$ und den Imaginärteil als $v$, und fassen diese als Funktionen von $\text{Re}(z)$ bzw. $\text{Im}(z)$ auf, d.h. wir schreiben
$$
\begin{align*}
f(x + iy) = u(x, y) + iv(x, y) \quad \text{wobei} \quad &u(x, y) = \text{Re} f(x + iy) \\
&v(x, y) = \text{Im} f(x + iy) .
\end{align*}
$$
Dann sind äquivalent:
(i) $f$ ist bei $z_0 = x_0 + iy_0 \in U$ komplex differenzierbar.
[^1]
(ii) Die Funktion $(x, y) \mapsto \begin{pmatrix} u(x, y) \\ v(x, y) \end{pmatrix}$ ist bei $\begin{pmatrix} x_0 \\ y_0 \end{pmatrix} \in \mathbb{R}^2$ (reell) differenzierbar und
$$ \frac{\partial u}{\partial x} = \frac{\partial v}{\partial y} \quad \text{sowie} \quad \frac{\partial u}{\partial y} = -\frac{\partial v}{\partial x}. \quad \text{(Cauchy-Riemann-Gleichungen) (2.2)} $$
In diesem Fall ist die Ableitung gegeben durch
$$ f'(x + iy) = u_x(x, y) - iu_y(x, y) = v_y(x, y) + iv_x(x, y). \quad (2.3) $$

[[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=70]]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=69]]


