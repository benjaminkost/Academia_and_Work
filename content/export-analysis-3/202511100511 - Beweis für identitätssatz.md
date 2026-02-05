---
"created date:": 29.10.2025 23:16
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301010 - Weitere Anwendungen der Cauchy-Integralformel|Weitere Anwendungen der Cauchy-Integralformel]]"
  - "[[202511020411 - Identitätssatz|Identitätssatz]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - satz
aliases:
  - Beweis für identitätssatz
  - Gleichung 2.19
  - Gleichung 2.16
  - Gleichung 2.17
  - Gleichung 2.18
parent:
siblings:
child:
mathematical statement: "[[202511020411 - Identitätssatz|Identitätssatz]]"
---
# Beweis
(i) $\Rightarrow$ (ii) ist klar.
(ii) $\Rightarrow$ (i): Sei $z \in U$ beliebig. Dann gibt es (weil $U$ wegzusammenhängend ist) eine stetige Kurve $\gamma: [0, 1] \to U$ mit Endpunkten $\{z_0, z\}$. Mit einem Kompaktheitsargument kann man endlich viele überlappende offene Kreisscheiben $\{B_{r_j}(z_j)\}_{j=0}^m$ finden, die eine Kette bilden und diese Kurve überdecken, d.h. so dass
$$\text{im}(\gamma) \subset B_{r_0}(z_0) \cup B_{r_1}(z_1) \cup \dots \cup B_{r_{m-1}}(z_{m-1}) \cup B_{r_m}(z) \quad (2.16)$$
und
$$z_j \in B_{r_{j-1}}(z_{j-1}) \quad \text{für alle } j=1, \dots, m, \quad (2.17)$$
wobei $z_m = z$, und so dass weiter $f$ und $g$ auf jeder Kreisscheibe eine Taylor-Entwicklung
$$f(z) = \sum_{k=0}^\infty \frac{f^{(k)}(z_j)}{k!}(z-z_j)^k$$
$$g(z) = \sum_{k=0}^\infty \frac{g^{(k)}(z_j)}{k!}(z-z_j)^k \quad \text{für alle } z \in B_{r_j}(z_j)$$
besitzen. Für $j=0$ gilt $f^{(k)}(z_0) = g^{(k)}(z_0)$ für alle $k \in \mathbb{N}_0$ nach Annahme, d.h. die Taylor-Reihen von $f$ und $g$ stimmen auf $B_{r_0}(z_0)$ überein und es folgt $f(z) = g(z)$ für alle $z \in B_{r_0}(z_0)$. Wir können jetzt induktiv vorgehen: gilt $f(z) = g(z)$ für alle $z \in B_{r_{j-1}}(z_{j-1})$, dann ist wegen (2.17) auch $f^{(k)}(z_j) = g^{(k)}(z_j)$ also stimmen die Taylor-Reihen von $f$ und $g$ auch auf $B_{r_j}(z_j)$ überein und es folgt $f(z)=g(z)$ für alle $z \in B_{r_j}(z_j)$. Induktiv haben wir so gezeigt, dass $f$ und $g$ auf allen Kreisscheiben übereinstimmen. Damit folgt mit (2.16) auch, dass sie auf der Kurve $\gamma$ übereinstimmen. Insbesondere ist $f(z) = f(\gamma(1)) = g(\gamma(1)) = g(z)$, was zu zeigen war.
(i) $\Rightarrow$ (iii) ist auch klar.
(iii) $\Rightarrow$ (ii): Seien $z_0, \{z_n\}_{n\in\mathbb{N}} \subset U \setminus \{z_0\}$ wie in (iii). Wir behaupten, dass $z_0$
$$f^{(k)}(z_0) = g^{(k)}(z_0) \quad \text{für alle } k \in \mathbb{N}_0 \quad (2.18)$$
erfüllt. Definiere $h := f-g$. Angenommen, (2.18) sei nicht erfüllt. Dann existiert ein $m \in \mathbb{N}$, so dass
$$\begin{gathered}h(z_0) = h^{(1)}(z_0) = \dots = h^{(m-1)}(z_0) = 0 \\h^{(m)}(z_0) \neq 0.\end{gathered}$$
[^1]
Daraus folgt, dass $h$ die Taylor-Reihenentwicklung
$$h(z) = \sum_{k \ge m} a_k (z-z_0)^k \quad \text{mit } a_m \neq 0$$
besitzt. Insbesondere können wir $h$ schreiben als
$$h(z) = (z-z_0)^m h_m(z) \quad \text{wobei } h_m(z) := \sum_{k=0}^\infty a_{k+m}(z-z_0)^k.$$
Offenbar ist (nach Definition) $h_m$ stetig, d.h.
$$h_m(z_n) \to h_m(z_0) \quad \text{für } n \to \infty. \quad (2.19)$$
Andererseits ist $z_n \neq z_0$ und $h(z_n) = 0$, also auch $h_m(z_n) = 0$ für jedes $n \in \mathbb{N}$. Einsetzen in (2.19) zeigt, dass
$$h_m(z_0) = 0 .$$
Dies widerspricht $h_m(z_0) = a_m \neq 0$, also war die ursprüngliche Annahme falsch.
[^2]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=89]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=90]]


