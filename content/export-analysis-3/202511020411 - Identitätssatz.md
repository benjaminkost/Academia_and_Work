---
"created date:": 29.10.2025 23:12
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301010 - Weitere Anwendungen der Cauchy-Integralformel|Weitere Anwendungen der Cauchy-Integralformel]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
  - definition
  - satz
aliases:
  - Identitätssatz
  - Theorem 2.8.4
parent:
siblings:
child:
proof:
  - "[[202511100511 - Beweis für identitätssatz|Beweis für identitätssatz]]"
---
# Definition
Wir haben bereits (etwa in [[202511100211 - Taylor-Reihe für den Logarithmus|Beispiel 2.8.3]]) die Aussage benutzt, dass zwei Potenzreihendarstellungen der gleichen Funktion (mit gleichem Entwicklungspunkt) identische Koeffizienten haben müssen. Mit anderen Worten ist die Potenzreihendarstellung eindeutig: Hat eine Funktion $f$ eine Potenzreihendarstellung $f(z) = \sum_{k=0}^\infty a_k(z-z_0)^k$ auf $B_r(z_0)$, ist diese eindeutig und $a_k = \frac{f^{(k)}(z_0)}{k!}$ nach der Taylor-Reihenentwicklung. Eine ähnliche (viel allgemeinere) Aussage gilt für analytische Funktionen:
[^1]
# Satz
Sei $U \subset \mathbb{C}$ ein Gebiet und seien $f, g : U \to \mathbb{C}$ analytisch auf $U$. Dann sind äquivalent:
(i) $f(z) = g(z)$ für alle $z \in U$.
(ii) Es gibt $z_0 \in U$ mit $f^{(k)}(z_0) = g^{(k)}(z_0)$ für alle $k \in \mathbb{N}_0$.
(iii) Es gibt $z_0 \in U$ und eine Folge $\{z_n\}_{n\in\mathbb{N}} \subset U \setminus \{z_0\}$ mit $z_n \to z_0$ für $n \to \infty$, so dass $f(z_n) = g(z_n)$ für alle $n \in \mathbb{N}$.
[^2]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=88]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=89]]



