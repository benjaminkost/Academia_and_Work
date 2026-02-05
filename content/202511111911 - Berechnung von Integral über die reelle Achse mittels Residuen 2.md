---
"created date:": 30.10.2025 00:30
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
  - Lemma
aliases:
  - Berechnung von Integral über die reelle Achse mittels Residuen
  - Gleichung 2.27
  - Lemma 2.11.12
parent:
siblings:
child:
proof:
  - "[[202511112011 - Beweis zu Berechnung von Integral über die reelle Achse mittels Residuen|Beweis zu Berechnung von Integral über die reelle Achse mittels Residuen]]"
---
# Lemma
Sei $U \subset \mathbb{C}$ offen mit
$$ \{z \in \mathbb{C} \mid \text{Im}(z) \ge 0\} \subset U $$
d.h. U enthält die obere Halbebene. Sei weiter $f : U\setminus S \to \mathbb{C}$ holomorph, wobei $S$ die Menge der isolierten Singularitäten von $f$ ist. Weiter sei $S \cap \mathbb{R} = \emptyset$ (d.h. $f$ hat keine isolierten Singularitäten auf der reellen Achse), und
$$ \{z_1, \dots, z_n\} = \{z \in S \mid \text{Im}(z) > 0\} $$
die Menge der isolierten Singularitäten in der oberen Halbebene. Schließlich gelte
$$ \lim_{|z|\to\infty} |z| \cdot |f(z)| = 0 . \quad (2.27) $$
Dann ist
$$ \lim_{r\to\infty} \int_{-r}^r f(x)dx = 2\pi i \sum_{j=1}^n \text{Res}_{z_j}(f) . $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=101]]


