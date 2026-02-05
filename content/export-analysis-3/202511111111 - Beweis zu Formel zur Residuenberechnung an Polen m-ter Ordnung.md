---
"created date:": 30.10.2025 00:14
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
  - Beweis zu Formel zur Residuenberechnung an Polen m-ter Ordnung
  - Beweis 2.11.7
parent:
siblings:
child:
proof:
---
# Lemma
Sei
$$f(z) = \sum_{k=-m}^\infty c_k(z-z_0)^k$$
die Laurent-Reihe von $f$ um $z_0$. Nach Definition hat
$$f_1(z) = (z-z_0)^m f(z)$$
bei $z=z_0$ eine hebbare Singularität. Es gilt
$$f_1(z) = \sum_{k=0}^\infty c_{k-m}(z-z_0)^k = \sum_{k=0}^\infty \frac{f_1^{(k)}(z_0)}{k!} (z-z_0)^k$$
und damit folgt
$$\text{Res}_{z_0}(f) = c_{-1} = \frac{f_1^{(m-1)}(z_0)}{(m-1)!}.$$
Dies ist die Behauptung.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=99]]


