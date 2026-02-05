---
"created date:": 30.10.2025 00:33
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
  - Beispiel zu Berechnung eines reellen Integrals mit dem Residuensatz
  - Beispiel 2.11.13
parent:
siblings:
child:
---
# Beispiel
Sei $f : \mathbb{C}\setminus\{i, -i\} \to \mathbb{C}$ definiert durch
$$ f(z) = \frac{1}{z^2 + 1} . $$
Dann ist $f$ auf $\mathbb{C}\setminus\{i, -i\}$ holomorph und $i, -i$ sind isolierte Singularitäten von $f$. Zusätzlich gilt
$$ |z| \cdot |f(z)| = \frac{|z|}{|z|^2 + 1} \to 0 \quad \text{für } |z| \to \infty . $$
Wir schränken $f$ auf
$$ U := \{z \in \mathbb{C} \mid \text{Im}(z) > -1/2\} $$
ein, so dass mit $S = \{i\}$ die Voraussetzungen von [[202511111911 - Berechnung von Integral über die reelle Achse mittels Residuen|Lemma 2.11.12]] erfüllt sind. Damit folgt
$$ \lim_{x\to\infty} \int_{-r}^r \frac{1}{x^2 + 1} dx = 2\pi i \cdot \text{Res}_i(f) = 2\pi i \cdot (-i/2) = \pi , $$
siehe [[202511091011 - Beispiel zu Residuenberechnung mittels Partialbruchzerlegung|Beispiel 2.11.6]].
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


