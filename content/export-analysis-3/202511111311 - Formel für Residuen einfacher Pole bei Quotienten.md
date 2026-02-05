---
"created date:": 30.10.2025 00:17
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
  - Formel für Residuen einfacher Pole bei Quotienten
  - Lemma 2.11.9
parent:
siblings:
child:
proof:
---
# Lemma
Seien $V \subset \mathbb{C}$ offen, $g,h : V \to \mathbb{C}$ holomorph in einer Umgebung von $z_0 \in V$, und sei weiter $z_0$ eine einfache Nullstelle von $h$, d.h.
$$h(z_0) = 0 \quad \text{und} \quad h'(z_0) \neq 0.$$
Dann hat die Funktion
$$f(z) = \frac{g(z)}{h(z)}$$
höchstens einen einfachen Pol bei $z_0$ und es gilt
$$\text{Res}_{z_0}(f) = \frac{g(z_0)}{h'(z_0)}$$
falls $z_0$ ein Pol ist.
[^1]
[[202511111411 - Beweis zu Formel für Residuen einfacher Pole bei Quotienten]]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=100]]


