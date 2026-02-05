---
"created date:": 30.10.2025 00:10
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
  - Beispiel zu Residuum und Cauchy-Integralformel
  - Beispiel 2.11.5
parent:
siblings:
child:
---
# Beispiel
Sei $V \subset \mathbb{C}$ offen und $f: V \to \mathbb{C}$. Sei weiter $z_0 \in V$ und $f$ holomorph bei $z_0$. Dann hat die Funktion $z \mapsto \frac{f(z)}{z-z_0}$ eine isolierte Singularität bei $z_0$ und
$$\text{Res}_{z_0}\left(z \mapsto \frac{f(z)}{z-z_0}\right) = f(z_0).$$
Dies folgt aus der Cauchy-Integralformel (Theorem 2.7.3) oder [[202511101411 - Regeln zur Konstruktion von Laurent-Reihen|Lemma 2.9.5]] (i). Ist weiter $g: V \to \mathbb{C}$ auch holomorph, dann gilt
$$\text{Res}_{z_0}\left(z \mapsto g(z) + \frac{f(z)}{z-z_0}\right) = f(z_0).$$
Hier haben wir verwendet, dass $g$ als Taylorreihe dargestellt werden kann bzw. dass das geschlossene Kurvenintegral einer holomorphen Funktion verschwindet.
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


