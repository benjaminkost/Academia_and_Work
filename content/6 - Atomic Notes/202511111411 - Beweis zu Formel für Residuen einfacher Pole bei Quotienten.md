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
  - beweise
aliases:
  - Beweis zu Formel für Residuen einfacher Pole bei Quotienten
  - Beweis 2.11.9
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Dies folgt aus [[202511111011 - Formel zur Residuenberechnung an Polen m-ter Ordnung|Lemma 2.11.7]] denn
$$\text{Res}_{z_0}(f) = \lim_{z\to z_0} (z-z_0)f(z) = g(z_0) \lim_{z\to z_0} \frac{z-z_0}{h(z)} = g(z_0) \lim_{z\to z_0} \frac{z-z_0}{h(z)-h(z_0)} = \frac{g(z_0)}{h'(z_0)}.$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=100]]


