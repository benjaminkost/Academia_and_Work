---
"created date:": 29.10.2025 22:37
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Cauchy Integralformel]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis für Cauchy-Integralformel
  - Beweis 2.7.3
  - Gleichung 2.12
parent:
siblings:
child:
mathematical statement: "[[Cauchy Integralformel|Cauchy-Integralformel]]"
---
# Beweis
Sei $\zeta \in B_r(z_0)$ gegeben. Für $\epsilon \in (0, r - |z_0 - \zeta|)$ beliebig sind die Voraussetzungen von [[202511090711 - Deformierbarkeit des Integrationsweges|Lemma 2.7.1]] mit der Funktion
$$g(z) = \frac{f(z)}{z - \zeta}$$
erfüllt, denn $g$ ist holomorph auf $U \setminus \{\zeta\}$. Damit erhalten wir
$$\begin{aligned}\oint_{\partial B_r(z_0)} \frac{f(z)}{z - \zeta} dz &= \oint_{\partial B_\epsilon(\zeta)} \frac{f(z)}{z - \zeta} dz \\&= \oint_{\partial B_\epsilon(\zeta)} \frac{f(\zeta)}{z - \zeta} dz + \oint_{\partial B_\epsilon(\zeta)} \frac{f(z) - f(\zeta)}{z - \zeta} dz \\&= 2\pi i f(\zeta) + \oint_{\partial B_\epsilon(\zeta)} \frac{f(z) - f(\zeta)}{z - \zeta} dz . \quad (2.12)\end{aligned}$$
Hier haben wir im ersten Schritt [[202511090711 - Deformierbarkeit des Integrationsweges|Lemma 2.7.1]] verwendet und im letzten Schritt den Wert des Fundamentalintegrals ([[202511011511 - Das Fundamentalintegral|Lemma 2.5.4]]) eingesetzt.
Mit der Definition der komplexen Ableitung folgt
$$f(z) = f(\zeta) + f'(\zeta)(z - \zeta) + (z - \zeta)r(z) \quad \text{wobei } r(z) \to 0 \quad \text{für } z \to \zeta$$
also mit der Standardabschätzung
$$\left| \oint_{\partial B_\epsilon(\zeta)} \frac{f(z) - f(\zeta)}{z - \zeta} dz \right| = \left| \oint_{\partial B_\epsilon(\zeta)} (f'(\zeta) + r(z))dz \right| \\\leq 2\pi\epsilon \sup_{z\in\partial B_\epsilon(\zeta)} |f'(\zeta) + r(z)| \to 0 \quad \text{für } \epsilon \to 0 .$$
Die Behauptung folgt daher aus ([[202511091111 - Beweis für Cauchy-Integralformel|Gleichung 2.12]]) indem wir den Grenzwert $\epsilon \to 0$ nehmen.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=84]]


