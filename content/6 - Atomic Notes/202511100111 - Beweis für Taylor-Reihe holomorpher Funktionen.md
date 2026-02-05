---
"created date:": 29.10.2025 23:05
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
  - baby
  - beweise
aliases:
  - Beweis für Taylor-Reihe holomorpher Funktionen
  - Gleichung 2.14
parent:
siblings:
child:
mathematical statement: "[[202511100011 - Taylor-Reihe holomorpher Funktionen|Taylor-Reihe holomorpher Funktionen]]"
---
# Beweis
Wir wenden die Cauchy-Integralformel in der Form
$$f(z) = \frac{1}{2\pi i} \oint_{|\zeta-z_0|=r} \frac{f(\zeta)}{\zeta-z} d\zeta \quad (2.14)$$
an, wobei hier $B_r(z_0) \subset U$. Die grundlegende Idee ist, die Funktion $1/(\zeta - z)$ durch eine Potenzreihe zu ersetzen: Wir haben unter Benutzung der geometrischen Reihe
$$\begin{aligned}\frac{1}{\zeta-z} &= \frac{1}{(\zeta - z_0) - (z - z_0)} = \frac{1}{\zeta - z_0} \frac{1}{1 - \frac{z-z_0}{\zeta-z_0}} \\&= \frac{1}{\zeta - z_0} \sum_{k=0}^\infty \left( \frac{z-z_0}{\zeta-z_0} \right)^k = \sum_{k=0}^\infty \frac{(z-z_0)^k}{(\zeta-z_0)^{k+1}} \quad \text{für alle } z_0, z, \zeta \in \mathbb{C} \text{ mit } |z-z_0| < |\zeta-z_0|.\end{aligned}$$
Einsetzen in (2.14) liefert den Ausdruck
$$\begin{aligned}f(z) &= \frac{1}{2\pi i} \oint_{|\zeta-z_0|=r} \frac{f(\zeta)}{\zeta-z} d\zeta = \frac{1}{2\pi i} \oint_{|\zeta-z_0|=r} f(\zeta) \sum_{k=0}^\infty \frac{(z-z_0)^k}{(\zeta-z_0)^{k+1}} d\zeta \\&= \sum_{k=0}^\infty \left( \frac{1}{2\pi i} \oint_{|\zeta-z_0|=r} \frac{f(\zeta)}{(\zeta-z_0)^{k+1}} d\zeta \right) (z-z_0)^k .\end{aligned}$$
Im letzten Schritt haben wir Summe und Integral vertauscht: dies ist wegen der gleichmäßigen Konvergenz der Reihe (siehe Theorem 2.3.2) gerechtfertigt. Also erhalten wir
$$f(z) = \sum_{k=0}^\infty a_k(z-z_0)^k \quad \text{mit} \quad a_k = \frac{1}{2\pi i} \oint_{|\zeta-z_0|=r} \frac{f(\zeta)}{(\zeta-z_0)^{k+1}} d\zeta .$$
Insbesondere stimmt $f$ für jedes $\rho \in (0, r)$ auf $B_\rho(z_0)$ mit einer Potenzreihe überein. Also ist dort $f$ beliebig oft differenzierbar (siehe [[202510312310 - Holomorphie, Ableitung und Stammfunktion von Potenzreihen|Theorem 2.3.6]]) und wir haben (wegen der Standard-Taylor-Reihenentwicklung, oder alternativ wegen [[202511091611 - Cauchy-Integralformel für Ableitungen|Theorem 2.7.7]])
$$\sum_{k=0}^\infty a_k(z-z_0)^k = \sum_{k=0}^\infty \frac{f^{(k)}(z_0)}{k!} (z-z_0)^k .$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=87]]


