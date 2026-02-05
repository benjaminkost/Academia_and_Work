---
"created date:": 22.10.2025 19:08
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270710 - Anwendung von linearem AWP mit konsztanten Koeffizienten|Anwendung von linearem AWP mit konsztanten Koeffizienten]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Lineares AWP mit konstanten Koeffizienten
  - Definition 1.3.29
parent:
siblings:
child:
---
# Definition
Sei $m \in \mathbb{N}$. Seien $a_0, \ldots, a_m \in \mathbb{C}$ und $L$ der Differentialoperator
$L[y](t) := a_m y^{(m)}(t) + \ldots + a_1 y'(t) + a_0 y(t)$.
Seien weiter $f: [0,\infty) \to \mathbb{C}$ und $y_0, y_1, \ldots, y_{m-1} \in \mathbb{C}$ gegeben. Das Problem, eine Funktion $y: [0,\infty) \to \mathbb{C}$ zu finden, welche
$$
L[y](t) = f(t) \quad \text{für alle } t \in [0,\infty) \quad \text{und} \quad
\begin{cases}
y(0) = y_0 \\
y'(0) = y_1 \\
\vdots \\
y^{(m-1)}(0) = y_{m-1}
\end{cases}
$$
erfüllt, heißt lineares Anfangswertproblem (AWP) mit konstanten Koeffizienten.
[^1]

# Unterthemen
```dataview
LIST
WHERE contains(mytags, [[]])
SORT file.name ASC
```

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=60]]



