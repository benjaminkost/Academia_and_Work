---
"created date:": 22.10.2025 15:43
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Existenzsatz für die Laplacetransformation
  - Beweis 1.3.6
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Sei $s \in \mathbb{C}$ mit $\text{Re}(s) > \sigma_0$ gegeben und $\sigma \in \mathbb{R}$ zwischen diesen Werten, d.h. $\text{Re}(s) > \sigma > \sigma_0$. Dann gilt
$$
|\mathcal{L}[f](s)| \le \int_0^\infty |f(t)| \cdot |e^{-st}| dt \le C \int_0^\infty e^{(\sigma-\text{Re}(s))t} dt = \left[ \frac{C}{\sigma - \text{Re}(s)} e^{(\sigma-\text{Re}(s))t} \right]_{t=0}^\infty = \frac{C}{\text{Re}(s)-\sigma}.
$$
Daraus folgt die Existenz des uneigentlichen Integrals (also (i)) sowie (ii).
Für (iii) sei $T > 0$. Wir schreiben
$$
\mathcal{L}[f](s) = \int_0^\infty f(t)e^{-st} dt =: I_1(T) + I_2(T) \quad \text{wobei}
$$
$$
I_1(T) = \int_0^T f(t)e^{-st} dt \quad \text{und} \quad I_2(T) = \int_T^\infty f(t)e^{-st} dt.
$$
Es gilt für $\text{Re}(s) \ge \sigma_1 > \sigma_0$
$$
|I_2(T)| \le \int_T^\infty |f(t)|e^{-\text{Re}(s)t} dt \le C \int_T^\infty e^{(\sigma_0-\text{Re}(s))t} dt \le C \int_T^\infty e^{(\sigma_0-\sigma_1)t} dt = \left[ \frac{C}{\sigma_0-\sigma_1}e^{(\sigma_0-\sigma_1)t} \right]^\infty_{t=T} = \frac{C}{\sigma_0-\sigma_1}e^{(\sigma_0-\sigma_1)T} \to 0 \quad \text{für } T \to \infty.
$$
Daraus folgt die gleichmäßige Konvergenz des uneigentlichen Integrals.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=52]]


