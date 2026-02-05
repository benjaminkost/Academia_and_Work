---
"created date:": 22.10.2025 20:16
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
  - Beweis zu Äquivalenz von komplexer Differenzierbarkeit und Cauchy-Riemann-Gleichungen
  - Beweis 2.2.10
parent:
siblings:
child:
mathematical statement: "[[202510310910 - Äquivalenz von komplexer Differenzierbarkeit und Cauchy-Riemann-Gleichungen|Äquivalenz von komplexer Differenzierbarkeit und Cauchy-Riemann-Gleichungen]]"
---
# Beweis
Sei $f$ komplex differenzierbar in $z_0 = x_0 + iy_0$ und sei
$$f'(z_0) = a + ib$$
die Ableitung. Sei $\tilde{f}(x, y) := \begin{pmatrix} u(x, y) \\ v(x, y) \end{pmatrix}$. Wir behaupten, dass $\tilde{f}$ im Punkt $\begin{pmatrix} x_0 \\ y_0 \end{pmatrix}$ differenzierbar ist mit Ableitung
$$ d\tilde{f}(x_0, y_0) = \begin{pmatrix} a & -b \\ b & a \end{pmatrix}. $$
Dies ist äquivalent zur Aussage
$$ \left\| \tilde{f}(x_0 + s, y_0 + t) - \tilde{f}(x_0, y_0) - \begin{pmatrix} a & -b \\ b & a \end{pmatrix} \begin{pmatrix} s \\ t \end{pmatrix} \right\|_2 = o\left(\left\| \begin{pmatrix} s \\ t \end{pmatrix} \right\|_2\right) \quad (2.4) $$
für $\begin{pmatrix} s \\ t \end{pmatrix} \in \mathbb{R}^2$. Zum Beweis von (2.4) setzen wir $h = s + it$. Dann ist
$$ \left\| \tilde{f}(x_0 + s, y_0 + t) - \tilde{f}(x_0, y_0) - \begin{pmatrix} a & -b \\ b & a \end{pmatrix} \begin{pmatrix} s \\ t \end{pmatrix} \right\|_2 = |f(z_0 + h) - f(z_0) - f'(z_0)h| $$
weil
$$ f'(z_0)h = (a + ib)(s + it) = (as - bt) + i(at + bs) $$
also
$$ \begin{pmatrix} \text{Re} f'(z_0)h \\ \text{Im} f'(z_0)h \end{pmatrix} = \begin{pmatrix} as - bt \\ at + bs \end{pmatrix} = \begin{pmatrix} a & -b \\ b & a \end{pmatrix} \begin{pmatrix} s \\ t \end{pmatrix}. $$
Ausserdem ist nach Definition der komplexen Ableitung
$$ |f(z_0 + h) - f(z_0) - f'(z_0)h| = o(|h|) \quad \text{und} \quad |h| = \left\| \begin{pmatrix} s \\ t \end{pmatrix} \right\|_2 $$
also folgt (2.4).
Sei jetzt umgekehrt $\tilde{f}(x, y) := \begin{pmatrix} u(x, y) \\ v(x, y) \end{pmatrix}$ differenzierbar, und es gelten die CR-Gleichungen (2.2). Setzen wir dann
$$ g(x + iy) := u_x(x, y) - iu_y(x, y) = v_y(x, y) + iv_x(x, y) $$
[^1]
und $h = s + it$, dann gilt für $z = x + iy$
$$ g(z)h = (u_x s + u_y t) + i(v_x s + v_y t) $$
was dem Ausdruck $\begin{pmatrix} u_x & u_y \\ v_x & v_y \end{pmatrix} \begin{pmatrix} s \\ t \end{pmatrix}$ entspricht. Damit erhalten wir ähnlich wie oben aus der (reellen) Differenzierbarkeit
$$ \left\| \tilde{f}(x + s, y + t) - \tilde{f}(x, y) - d\tilde{f}(x, y) \begin{pmatrix} s \\ t \end{pmatrix} \right\|_2 = o\left(\left\| \begin{pmatrix} s \\ t \end{pmatrix} \right\|_2\right) $$
von $\tilde{f}$ die Aussage
$$ |f(z + h) - f(z) - g(z)h| = o(|h|). $$
Damit ist gezeigt, dass $f$ komplex differenzierbar ist mit Ableitung $f'(z) = g(z)$.
[^2]

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

[^1]: [[tum_KoenigUlbrich-Analysis3EI-WS2526-skript.pdf#page=70

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=71]]


