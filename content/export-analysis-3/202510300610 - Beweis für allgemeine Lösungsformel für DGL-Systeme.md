---
"created date:": 22.10.2025 19:24
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270910 - Anwendung lineare Differentialgleichungssysteme 1. Ordung mit konstanten Koeffizienten|Anwendung lineare Differentialgleichungssysteme 1.Ordung mit konstanten Koeffizienten]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für allgemeine Lösungsformel für DGL-Systeme
  - Beweis 1.3.42
parent:
siblings:
child:
mathematical statement: "[[202510300510 - Allgemeine Lösungsformel für DGL-Systeme|Allgemeine Lösungsformel für DGL-Systeme]]"
---
# Beweis
Sei wieder $X(s) = \mathcal{L}[x](s)$ die Laplacetransfomierte der Lösung. Dann erhalten wir aus (1.80)
$$
sX(s) - x_0 = AX(s) + B(s),
$$
wobei $B(s) = \mathcal{L}[b](s)$. Umformen führt auf
$$
(sI - A)X(s) = x_0 + B(s).
$$
Sei jetzt $s \in \mathbb{C}$ so dass Re$(s) > \max_j \text{Re}(\lambda_j(A))$. Dann existiert die Resolvente $(sI-A)^{-1}$ und wir können nach $X(s)$ auflösen:
$$
X(s) = (sI - A)^{-1}x_0 + (sI - A)^{-1}B(s).
$$
Rücktransformation liefert mit [[202510300010 - Beispiel zu Laplace-Transformierte von e hoch tA|Beispiel 1.3.38]]
$$
\begin{align*}
x(t) &= \mathcal{L}^{-1}[X](t) = \mathcal{L}^{-1}[s \to (sI - A)^{-1}x_0](t) + \mathcal{L}^{-1}[s \to (sI - A)^{-1}B(s)](t) \\
&= \mathcal{L}^{-1}[s \to (sI - A)^{-1}](t)x_0 + \mathcal{L}^{-1}[s \to (sI - A)^{-1}B(s)](t) \\
&= \exp(tA)x_0 + ((t \to \exp(tA)) * b)(t) \\
&= \exp(tA)x_0 + \int_0^t e^{(t-\tau)A}b(\tau)d\tau.
\end{align*}
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=64]]


