---
"created date:": 29.10.2025 22:23
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202511021711 - Integralsatz von Cauchy|Integralsatz von Cauchy]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis von Stammfunktion und Wegunabhängigkeit des Integrals
  - Beweis 2.6.5
parent:
siblings:
child:
mathematical statement: "[[202511090311 - Stammfunktion und Wegunabhängigkeit des Integrals]]"
---
# Beweis
Die Behauptung ([[202511090311 - Stammfunktion und Wegunabhängigkeit des Integrals|Gleichung 2.10]]) folgt aus
$$\int_a^b f(\gamma(t)) \cdot \gamma'(t)dt = \int_a^b F'(\gamma(t)) \cdot \gamma'(t)dt = \int_a^b \frac{d}{dt} F(\gamma(t))dt = F(\gamma(b)) - F(\gamma(a)) .$$
Behauptung (i) folgt unmittelbar. Behauptung (ii) folgt durch Zerlegung eines geschlossenen Weges $\gamma$ in zwei Teilwege $\gamma_1, \gamma_2$ (durch beliebige Wahl von Anfangs/Endpunkten $z_0, z_1 \in \text{im}(\gamma)$) und Anwendung von (2.10). Man beachte, dass hier (nach geeigneter Umparametrisierung) die Endpunkte dieser Kurven (im von $\gamma$ vorgegebenen Durchlaufsinn) gleich
$$\begin{aligned}\gamma_1(a) = z_0 = \gamma_2(b) \\\gamma_1(b) = z_1 = \gamma_2(a)\end{aligned}$$
sind. Daher gilt $\int_{\gamma_1} f(z)dz = - \int_{\gamma_2} f(z)dz$ und damit $\oint_\gamma f(z)dz = 0$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=81]]


