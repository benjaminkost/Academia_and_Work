---
"created date:": 22.10.2025 19:22
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
  - Beispiel für Lösung eines DGL-Systems
  - Beispiel 1.3.41
parent:
siblings:
child:
---
# Beispiel
Betrachte das lineare DGL-System
$$
x'(t) = \begin{pmatrix} 2 & 1 \\ 0 & 2 \end{pmatrix} x(t) + e^{2t}\begin{pmatrix} 1 \\ 0 \end{pmatrix} \quad \text{für alle } t \in \mathbb{R} \quad \text{und} \quad x(0) = c = \begin{pmatrix} c_1 \\ c_2 \end{pmatrix}.
$$
Es sei $X(s) = \mathcal{L}[x](s)$ die Laplacetransformierte der (unbekannten) Lösung $x(t)$. Wir gehen wie folgt vor:
1.  **Schritt:** Durch (eintragsweise) Laplacetransformation der Gleichung (1.77) erhalten wir
    $$
    sX(s) - c = \begin{pmatrix} 2 & 1 \\ 0 & 2 \end{pmatrix} X(s) + \frac{1}{s-2} \begin{pmatrix} 1 \\ 0 \end{pmatrix}.
    $$
2.  **Schritt:** Wir schreiben (1.78) um als
    $$
    \begin{pmatrix} s-2 & -1 \\ 0 & s-2 \end{pmatrix} X(s) = \begin{pmatrix} c_1 + \frac{1}{s-2} \\ c_2 \end{pmatrix}
    $$
    und können damit für $s \neq 2$ nach $X(s)$ auflösen. Wir erhalten $X(s) = \begin{pmatrix} X_1(s) \\ X_2(s) \end{pmatrix}$ mit
    $$
    X_1(s) = \frac{c_1}{s-2} + \frac{1}{(s-2)^2} + \frac{c_2}{(s-2)^2} \\
    X_2(s) = \frac{c_2}{s-2}.
    $$
3.  **Schritt:** Rücktransformation von $X$ gibt $x(t) = \mathcal{L}^{-1}[X](t)$:
    $$
    x(t) = c_1 e^{2t}\begin{pmatrix} 1 \\ 0 \end{pmatrix} + c_2 e^{2t}\begin{pmatrix} t \\ 1 \end{pmatrix} + e^{2t}\begin{pmatrix} t \\ 0 \end{pmatrix}.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=63]]



