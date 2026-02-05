---
"created date:": 30.10.2025 00:31
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
  - beweise
aliases:
  - Beweis zu Berechnung von Integral über die reelle Achse mittels Residuen
parent:
siblings:
child:
mathematical statement: "[[202511111911 - Berechnung von Integral über die reelle Achse mittels Residuen|Berechnung von Integral über die reelle Achse mittels Residuen]]"
---
# Beweis
Das Interval $[-r, r]$ (d.h. die gerade Kurve) zusammen mit der Kurve (Halbkreis)
$$ \eta_r(t) = re^{i\pi t} \quad t \in [0, 1] $$
definieren einen geschlossenen Weg $\gamma$, der für $r$ groß genug alle Punkte in $S$ im Gegenuhrzeigersinn umrundet (d.h. $S$ ist im Inneren von $\gamma$ enthalten). Nach dem Residuensatz ist daher
$$ \int_{[-r,r]} f(z)dz + \int_{\eta_r} f(z)dz = 2\pi i \sum_{j=1}^n \text{Res}_{z_j}(f) . $$
Die Behauptung folgt daraus, dass einerseits $\int_{[-r,r]} f(z)dz = \int_{-r}^r f(x)dx$, und andererseits mit der Standardabschätzung und der Annahme ([[202511111911 - Berechnung von Integral über die reelle Achse mittels Residuen|Gleichung 2.27]]) gilt
$$ \left| \int_{\eta_r} f(z)dz \right| \le \pi r \left( \sup_{z\in\text{im}(\eta_r)} |f(z)| \right) = \pi \left( \sup_{z\in\text{im}(\eta_r)} |z| \cdot |f(z)| \right) \to 0 \quad \text{für } r \to \infty $$
gilt.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=102]]


