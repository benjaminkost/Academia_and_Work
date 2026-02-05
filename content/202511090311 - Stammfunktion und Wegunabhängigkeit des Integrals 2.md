---
"created date:": 29.10.2025 22:22
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202511021711 - Integralsatz von Cauchy|Integralsatz von Cauchy]]"
  - "[[202511090211 - Stammfunktionen und Wegintegrale|Stammfunktionen und Wegintegrale]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - Lemma
aliases:
  - Stammfunktion und Wegunabhängigkeit des Integrals
  - Gleichung 2.10
  - Lemma 2.6.5
parent:
siblings:
child:
proof:
  - "[[202511090411 - Beweis von Stammfunktion und Wegunabhängigkeit des Integrals|Beweis von Stammfunktion und Wegunabhängigkeit des Integrals]]"
---
# Lemma
Sei $U \subset \mathbb{C}$ offen, $\gamma : [a, b] \to U$ eine Kurve in $U$ und $f : U \to \mathbb{C}$ stetig. Angenommen, $F$ sei eine Stammfunktion von $f$ auf $U$. Dann gilt
$$\int_\gamma f(z)dz = F(\gamma(b)) - F(\gamma(a)) . \quad (2.10)$$
Insbesondere ist
(i) das Integral $\int_\gamma f(z)dz$ unabhängig von $\gamma$ für alle Kurven $\gamma$ mit fixen Anfangs- und Endpunkten $\gamma(a) = z_0$ und $\gamma(b) = z_1$, d.h. $f$ ist wegunabhängig integrierbar auf $U$, und
(ii) $\oint_\gamma f(z)dz = 0$ für jede geschlossene Kurve $\gamma : [a, b] \to U$.
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


