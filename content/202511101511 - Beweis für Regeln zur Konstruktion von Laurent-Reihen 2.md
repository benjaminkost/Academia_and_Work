---
"created date:": 29.10.2025 23:38
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Laurentreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis für Regeln zur Konstruktion von Laurent-Reihen
  - Beweis 2.9.5
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Für (i) betrachten wir die Taylor-Reihe
$$g(z) = \sum_{l=0}^\infty \frac{g^{(l)}(z_0)}{l!} (z-z_0)^l$$
ein und erhalten für jedes $z \in A_{0,R}(z_0)$
$$f(z) = \frac{g(z)}{(z-z_0)^m} = \frac{1}{(z-z_0)^m} \sum_{l=0}^\infty \frac{g^{(l)}(z_0)}{l!} (z-z_0)^l = \sum_{k=-m}^\infty \frac{g^{(k+m)}(z_0)}{(k+m)!} (z-z_0)^k .$$
Wegen Eindeutigkeit der Laurent-Reihe ist dies die Laurent-Reihe von $f$ auf $A_{0,R}(z_0)$.
Für (ii) verwenden wir die Taylor-Reihendarstellung
$$g(z) = \sum_{k=0}^\infty \frac{g^{(k)}(0)}{k!} z^k \quad \text{für } z \in B_R(0)$$
von $g$ auf $B_R(0)$. Wir beobachten, dass $z \in A_{1/R,\infty}(z_0)$ genau dann, wenn $|1/(z-z_0)| < R$. Damit folgt für $z \in A_{1/R,\infty}(z_0)$
$$f(z) = g\left(\frac{1}{z-z_0}\right) = \sum_{k=0}^\infty \frac{g^{(k)}(0)}{k!} \left( \frac{1}{z-z_0} \right)^k ,$$
wie behauptet.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=94]]


