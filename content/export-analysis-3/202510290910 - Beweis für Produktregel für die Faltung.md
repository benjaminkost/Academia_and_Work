---
"created date:": 22.10.2025 19:03
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510271610 - Faltung und Laplacetransformation|Faltung und Laplacetransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Produktregel für die Faltung
  - Beweis 1.3.25
parent:
siblings:
child:
mathematical statement: "[[202510290810 - Produktregel für die Faltung|Produktregel für die Faltung]]"
---
# Beweis
Dies folgt aus
$$
\begin{align*}
(\mathcal{L}[f] \cdot \mathcal{L}[g])(s) &= \mathcal{L}[f](s) \cdot \mathcal{L}[g](s) \\
&= \int_0^\infty \mathcal{L}[f](s)g(t)e^{-st}dt \\
&= \int_0^\infty \left( \int_0^\infty f(\tau)e^{-s\tau}e^{-st}d\tau \right) g(t)dt \\
&= \int_0^\infty \left( \int_t^\infty f(\theta-t)e^{-s\theta}d\theta \right) g(t)dt.
\end{align*}
$$
Hier haben wir die Substitution $\theta = t+\tau$ verwendet. Der Integrationsbereich ist ein halber Quadrant und lässt sich schreiben als
$$
\{(t,\theta) \in \mathbb{R}^2 | t \ge 0 \text{ und } \theta \ge t\} = \{(t,\theta) \in \mathbb{R}^2 | \theta \ge 0 \text{ und } 0 \le t \le \theta\}.
$$
Durch Vertauschen der Integrationsreihenfolge (erlaubt, weil $\int_0^\infty \int_0^\infty |g(t)f(\tau)e^{-s(t+\tau)}|d\tau dt$ konvergiert) erhalten wir daher
$$
(\mathcal{L}[f] \cdot \mathcal{L}[g])(s) = \int_0^\infty \left( \int_0^\theta f(\theta-t)g(t)dt \right) e^{-s\theta}d\theta = \int_0^\infty (f*g)(\theta)e^{-s\theta}d\theta = \mathcal{L}[f*g](s).
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

[^1]: [[tum_KoenigUlbrich-Analysis3EI-WS2526-skript.pdf#page=59


