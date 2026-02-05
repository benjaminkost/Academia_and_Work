---
"created date:": 29.10.2025 23:48
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
  - Bemerkung zu Laurent-Reihen in verschiedenen Kreisringen
  - Bemerkung 2.9.9
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Der Konvergenzbereich der Laurent-Reihe wird jeweils durch Punkte beschränkt, in denen die Funktion nicht analytisch ist. Betrachte z.B.
$$f(z) = \frac{1}{2-z}.$$
Der Nenner hat eine Nullstelle bei $z_1=2$. Ist der Entwicklungspunkt $z_0=1$, dann sind $A_{0,1}(1)$ und $A_{1,\infty}(1)$ die maximalen Kreisringe, die $z_1$ nicht enthalten.
Auf der Kreisscheibe $B_1(1)$ ist $f$ analytisch und besitzt daher eine Taylor-Entwicklung. Wir erhalten diese mit Hilfe der geometrischen Reihe:
$$\frac{1}{2-z} = \frac{1}{1-(z-1)} = \sum_{k=0}^\infty (z-1)^k \quad \text{für alle } z \in B_1(1).$$
Auf $A_{1,\infty}(1)$ ist $f$ analytisch, und wir erhalten folgende Laurent-Reihe (wiederum mit der geometrischen Reihe):
$$\frac{1}{2-z} = -\frac{1}{(z-1)-1} = -\frac{1}{z-1} \frac{1}{1-\frac{1}{z-1}} = -\frac{1}{z-1} \sum_{k=0}^\infty (z-1)^{-k} = \sum_{k=1}^\infty -(z-1)^{-k} \quad \text{für alle } z \in A_{1,\infty}(1).$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=95]]


