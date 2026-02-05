---
"created date:": 22.10.2025 19:35
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[satz]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
  - "[[202511020011 - Komplexe Kurvenintegrale und Kurvenintegrale im R|Komplexe Kurvenintegrale und Kurvenintegrale im R]]"
  - "[[202511021711 - Integralsatz von Cauchy|Integralsatz von Cauchy]]"
  - "[[Komplexe Funktionen]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Integralsatz von Cauchy
  - Theorem 2.6.1
parent:
siblings:
child:
proof:
  - "[[202511021811 - Beweis von Integralsatz von Cauchy|Beweis von Integralsatz von Cauchy]]"
---
# Satz
Eine Menge $U \subset \mathbb{C}$ heißt **wegzusammenhängend**, falls für alle Paare von Punkten $z_0, z_1 \in U$ eine Kurve $\gamma$ mit Endpunkten $\{z_0, z_1\}$ existiert.

Ein **Gebiet** ist eine offene, wegzusammenhängende Menge.

Eine Menge $U \subset \mathbb{C}$ heißt **einfach zusammenhängend**, falls jede geschlossene Kurve in $U$ sich in $U$ stetig zu einem Punkt zusammenziehen lässt (der in $U$ liegt), also nullhomotop ist.
[^1]

Sei $U \subset \mathbb{C}$ ein einfach zusammenhängendes Gebiet und $f: U \rightarrow \mathbb{C}$ in U komplex differenzierbar . Sei weiter $\gamma: [a, b] \rightarrow U$ eine in U verlaufende einfach geschlossene Kurve . Dann gilt

$$\oint_{\gamma} f(z) dz = 0$$

Diese Aussage gilt auch für geschlossene Kurven mit endlich vielen Überschneidungen .
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=80]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=80]]



