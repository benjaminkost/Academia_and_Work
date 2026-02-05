---
"created date:": 22.10.2025 19:26
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270910 - Anwendung lineare Differentialgleichungssysteme 1. Ordung mit konstanten Koeffizienten|Anwendung lineare Differentialgleichungssysteme 1.Ordung mit konstanten Koeffizienten]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Beispiel für Lösung von x``(t)-x(t)=t
  - Beispiel 1.3.44
parent:
siblings:
child:
---
# Beispiel
Gesucht sei eine Lösung $x: \mathbb{R} \to \mathbb{R}$ des Problems
$$
x''(t) - x(t) = t \quad \text{für alle } t \in \mathbb{R} \quad \text{und} \quad \begin{cases} x(0) = x_0 \\ x'(0) = v \end{cases}
$$
wobei $x_0, v \in \mathbb{R}$ gegeben sind. Wir setzen $y(t) = \begin{pmatrix} x(t) \\ x'(t) \end{pmatrix}$. Dann ist
$$
y'(t) = \begin{pmatrix} x'(t) \\ x''(t) \end{pmatrix} = \begin{pmatrix} x'(t) \\ x(t)+t \end{pmatrix} = \begin{pmatrix} y_2(t) \\ y_1(t) \end{pmatrix} + \begin{pmatrix} 0 \\ t \end{pmatrix}
$$
Also lässt sich das Differentialgleichungssystem (1.83) umschreiben als $y'(t) = Ay(t) + b(t)$ mit $y(0)=z$, wobei
$$
A = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}, \quad b(t) = \begin{pmatrix} 0 \\ t \end{pmatrix}, \quad z = \begin{pmatrix} x_0 \\ v \end{pmatrix}.
$$
Wir wenden nun die Lösungsformel (1.81) an.
$$
e^{tA} = \sum_{k=0}^\infty \frac{t^k A^k}{k!} = \sum_{l=0}^\infty \frac{t^{2l}A^{2l}}{(2l)!} + \sum_{l=0}^\infty \frac{t^{2l+1}A^{2l+1}}{(2l+1)!} = \cosh(t)I + \sinh(t)A = \begin{pmatrix} \cosh t & \sinh t \\ \sinh t & \cosh t \end{pmatrix}.
$$
Damit ist die Lösung
$$
\begin{align*}
y(t) &= e^{At}\left( z + \int_0^t e^{-\tau A} b(\tau) d\tau \right) \\
&= \begin{pmatrix} \cosh(t) & \sinh(t) \\ \sinh(t) & \cosh(t) \end{pmatrix} \left( \begin{pmatrix} x_0 \\ v \end{pmatrix} + \int_0^t \begin{pmatrix} \cosh(\tau) & -\sinh(\tau) \\ -\sinh(\tau) & \cosh(\tau) \end{pmatrix} \begin{pmatrix} 0 \\ \tau \end{pmatrix} d\tau \right) \\
&= \begin{pmatrix} \cosh(t) & \sinh(t) \\ \sinh(t) & \cosh(t) \end{pmatrix} \left( \begin{pmatrix} x_0 \\ v \end{pmatrix} + \int_0^t \begin{pmatrix} -\tau\sinh(\tau) \\ \tau\cosh(\tau) \end{pmatrix} d\tau \right) \\
&= \begin{pmatrix} \cosh(t) & \sinh(t) \\ \sinh(t) & \cosh(t) \end{pmatrix} \left( \begin{pmatrix} x_0 \\ v \end{pmatrix} + \begin{pmatrix} -t\cosh(t)+\sinh(t) \\ 1-\cosh(t)+t\sinh(t) \end{pmatrix} \right).
\end{align*}
$$

Ausmultiplizieren und Ablesen des ersten Eintrages $y_1(t) = x(t)$ gibt die Lösung

$x(t) = x_0 \cosh(t) + (v_0+1)\sinh(t) - t$,

wobei wir benutzt haben, dass $\cosh(t)^2 - \sinh(t)^2 = 1$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=65]]



