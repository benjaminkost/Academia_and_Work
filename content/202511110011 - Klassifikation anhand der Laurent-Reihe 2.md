---
"created date:": 29.10.2025 23:56
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301110 - Isolierte Singularität|Isolierte Singularität]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - Lemma
aliases:
  - Klassifikation anhand der Laurent-Reihe
  - Lemma 2.10.6
parent:
siblings:
child:
proof:
---
# Lemma
Sei $U \subset \mathbb{C}$ offen und $f: U \to \mathbb{C}$ holomorph. Sei $z_0 \notin U$ eine isolierte Singularität von $f$ und (für ein geeignetes $r > 0$)
$$f(z) = \sum_{k=-\infty}^\infty c_k(z-z_0)^k$$
die Laurent-Reihe von $f$ auf $A_{0,r}(z_0)$. Dann gilt: Die isolierte Singularität $z_0$ ist
(i) hebbar, falls $c_{-k} = 0$ für alle $k \in \mathbb{N}$.
(ii) ein Pol der Ordnung $m \ge 1$, falls $c_{-m} \neq 0$ und $c_{-k} = 0$ für alle $k > m$.
(iii) wesentlich, wenn es unendlich viele $k \in \mathbb{N}$ gibt mit $c_{-k} \neq 0$.
[^1]
# Beweis
Dies folgt unmittelbar aus den Definitionen.
[^2]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=96]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=96]]


