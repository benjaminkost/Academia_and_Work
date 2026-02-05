---
"created date:": 30.10.2025 00:12
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Residuentheorie]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beispiele
aliases:
  - Residuenberechnung mittels Partialbruchzerlegung
  - Beispiel 2.11.6
parent:
siblings:
child:
---
# Beispiel
Für die Funktion $f: \mathbb{C}\setminus\{i,-i\} \to \mathbb{C}$
$$f(z) = \frac{1}{z^2+1}$$
sind $z_0=i$ und $z_0=-i$ zwei isolierte Singularitäten. Wir können (mit dem Ansatz $\frac{A}{z-i} + \frac{B}{z+i}$) die Funktion als
$$f(z) = -\frac{i}{2} \cdot \frac{1}{z-i} + \frac{i}{2} \frac{1}{z+i}$$
zerlegen. Die Funktion $z \mapsto \frac{1}{z+i}$ ist holomorph bei $z_0=i$, daher folgt
$$\text{Res}_i(f) = \text{Res}_i\left(z \mapsto \left(-\frac{i}{2}\right)\frac{1}{z-i}\right) = -\frac{i}{2}.$$
Analog ist $z \mapsto \frac{1}{z-i}$ holomorph bei $-i$ und es folgt
$$\text{Res}_{-i}(f) = i/2.$$
Folgendes Lemma ist oft hilfreich zu Berechnung von Residuen.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=98]]


