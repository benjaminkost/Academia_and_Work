---
"created date:": 29.10.2025 22:35
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Cauchy Integralformel]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - satz
aliases:
  - Cauchy-Integralformel
  - Theorem 2.7.3
parent:
siblings:
child:
proof:
  - "[[202511091111 - Beweis für Cauchy-Integralformel|Beweis für Cauchy-Integralformel]]"
---
# Satz
Sei $U \subset \mathbb{C}$ offen, $r > 0$ und $z_0 \in U$, so dass $\overline{B_r(z_0)} \subset U$. Sei $f : U \to \mathbb{C}$ holomorph. Dann gilt
$$f(\zeta) = \frac{1}{2\pi i} \oint_{\partial B_r(z_0)} \frac{f(z)}{z - \zeta} dz \quad \text{für alle } \zeta \in B_r(z_0) .$$
[^1]
# Visualisierung
![[Bildschirmfoto 2025-10-29 um 22.36.43.png|400]]
Abbildung 9: Beweisidee: Wahl der Verbindungsstücke $ν_{1}$ und $ν_{2}$. Wir benutzen dasselbe Linien- segment (aber zeichnen es zur Verdeutlichung separiert).
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=83]]


