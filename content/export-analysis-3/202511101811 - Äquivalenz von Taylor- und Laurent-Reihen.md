---
"created date:": 29.10.2025 23:43
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
  - bemerkung
aliases:
  - Äquivalenz von Taylor- und Laurent-Reihen
  - Bemerkung 2.9.8
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Aus (i) folgt auch (mit $m=0$ und der Eindeutigkeit der Laurent-Reihe), dass für eine holomorphe Funktion $f : B_R(z_0) \to \mathbb{C}$ die Taylor-Reihe von $f$ mit der Laurent-Reihe von $f$ auf $A_{0,R}(z_0)$ übereinstimmt. Alternativ können wir das auch anhand der Formel
$$c_{-k} = \frac{1}{2\pi i} \oint_{|z-z_0|=\rho} f(z)(z-z_0)^{k-1} d\zeta = 0 \quad \text{für alle } k \in \mathbb{N}$$
und $\rho \in (0,R)$ sehen. Das Integral verschwindet, weil der Integrand auf $B_R(z_0)$ analytisch ist (siehe [[202511090311 - Stammfunktion und Wegunabhängigkeit des Integrals|Lemma 2.6.5]] und [[202511090511 - Existenz von Stammfunktionen in einfach zusammenhängenden Gebieten|Lemma 2.6.6]]).
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


