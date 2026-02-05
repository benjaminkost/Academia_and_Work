---
"created date:": 22.10.2025 19:10
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
  - beispiele
  - baby
aliases:
  - Beispiel zu Lösung eines AWPs
  - Beispiel 1.3.32
parent:
siblings:
child:
---
# Beispiel
Betrachte das AWP
$$
y''(t) = t \quad \text{für alle } t \in [0,\infty) \quad \text{und} \quad \begin{cases} y(0) = 0 \\ y'(0) = 1 \end{cases}.
$$
Dann ist (1.72) gegeben durch
$$
s^2 Y(s) - sy(0) - y'(0) = s^2 Y(s) - 1 = \frac{1}{s^2}
$$
denn $\mathcal{L}[t \to t](s) = \frac{1}{s^2}$ (siehe Beispiel 1.3.19). Auflösen nach $Y(s)$ liefert
$$
Y(s) = \frac{1}{s^4} + \frac{1}{s^2}.
$$
Berechnung der inversen Laplacetransformierten (wieder mit Beispiel 1.3.19) liefert die Lösung
$$
y(t) = \frac{1}{6}t^3 + t.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=60]]



