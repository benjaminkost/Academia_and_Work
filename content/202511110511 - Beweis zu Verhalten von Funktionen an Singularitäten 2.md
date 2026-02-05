---
"created date:": 30.10.2025 00:01
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301110 - Isolierte Singularität|Isolierte Singularität]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis zu Verhalten von Funktionen an Singularitäten
  - Beweis zu 2.10.9
parent:
siblings:
child:
mathematical statement:
---
# Beweis
(i): Ist $z_0$ hebbar, dann besitzt $f$ (genauer: die Funktion $\tilde{f}$) eine Taylor-Reihe um $z_0$ und ist insbesondere stetig, also lokal beschränkt um $z_0$.
Erfüllt $f$ umgekehrt ([[202511110411 - Verhalten von Funktionen an Singularitäten|Gleichung 2.22]]) mit einer Konstante $C > 0$ und $r > 0$, dann gilt für $\rho \in (0, r)$
$$|c_{-k}| \le \frac{1}{|2\pi i|} \oint_{\partial B_\rho(z_0)} |f(\zeta)| \cdot |(\zeta-z_0)^{k-1}| |d\zeta|\le \rho \cdot C \cdot \rho^{k-1} = C \cdot \rho^k \to 0 \quad \text{für } \rho \to 0.$$
Damit folgt $c_{-k}=0$ für alle $k \in \mathbb{N}$. Mit [[202511110011 - Klassifikation anhand der Laurent-Reihe|Lemma 2.10.6]] ist daher $z_0$ hebbar.
(ii): Sei $z_0$ ein Pol der Ordnung $m \in \mathbb{N}$. Dann ist $f(z) = (z-z_0)^{-m} f_1(z)$ für eine holomorphe Funktion $f_1$ auf $B_r(z_0)$ (für ein geeignetes $r>0$) mit $f_1(z_0) \neq 0$. Wegen $f_1(z) \to f_1(z_0)$ für $z \to z_0$ folgt $|f(z)| \to \infty$ für $z \to z_0$.
Gelte umgekehrt ([[202511110411 - Verhalten von Funktionen an Singularitäten|Gleichung 2.23]]). Dann kann $z_0$ nach (i) keine hebbare Singularität sein. Außerdem sagt der Satz von Casorati-Weierstraß ([[202511110211 - Casorati-Weierstraß|Theorem 2.10.8]]), dass $z_0$ auch keine wesentliche Singularität sein kann, wenn ([[202511110411 - Verhalten von Funktionen an Singularitäten|Gleichung 2.23]]) gilt. Daher ist $z_0$ ein Pol, wie behauptet.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=97]]


