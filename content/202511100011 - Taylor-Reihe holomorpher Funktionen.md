---
"created date:": 29.10.2025 23:02
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301010 - Weitere Anwendungen der Cauchy-Integralformel|Weitere Anwendungen der Cauchy-Integralformel]]"
  - "[[202511020311 - Taylor-Entwicklung|Taylor-Entwicklung]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - satz
aliases:
  - Taylor-Reihe holomorpher Funktionen
  - Theorem 2.8.1
  - Gleichung 2.13
parent:
siblings:
child:
proof:
  - "[[202511100111 - Beweis für Taylor-Reihe holomorpher Funktionen|Beweis für Taylor-Reihe holomorpher Funktionen]]"
---
# Satz
Sei $U \subset \mathbb{C}$ ein Gebiet und $f : U \to \mathbb{C}$ holomorph auf $U$. Weiter seien $r > 0$ und $z_0 \in U$ so, dass $\overline{B_r(z_0)} \subset U$. Dann ist $f$ für jedes $\rho \in (0, r)$ im Kreisring $B_\rho(z_0)$ als Potenzreihe (die Taylor-Reihe um $z_0$) entwickelbar und somit auf $B_\rho(z_0)$ unendlich oft komplex differenzierbar. Es gilt
$$f(z) = \sum_{k=0}^\infty a_k (z-z_0)^k = \sum_{k=0}^\infty \frac{f^{(k)}(z_0)}{k!} (z-z_0)^k \quad \text{für alle } z \in \mathbb{C} \text{ mit } |z-z_0| < \rho < r,$$
wobei der $k$-te Taylor-Reihenkoeffizient durch
$$a_k = \frac{1}{2\pi i} \oint_{|\zeta-z_0|=r} \frac{f(\zeta)}{(\zeta-z_0)^{k+1}} d\zeta \quad (2.13)$$
gegeben ist.
[^1]

# Beispiele


# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202511092311 - Holomorphie und Analytizität|Holomorphie und Analytizität]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=87]]


