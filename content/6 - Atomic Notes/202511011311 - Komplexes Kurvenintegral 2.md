---
"created date:": 22.10.2025 20:51
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Komplexes Kurvenintegral
  - Definition 2.5.2
  - Komplexes Wegintegral
parent:
siblings:
child:
---
# Definition
Sei jetzt $\gamma : [a, b] \to \mathbb{C}$ und $f : \text{im}(\gamma) \to \mathbb{C}$ stetig.
Das Kurvenintegral (oder Wegintegral) von $f$ entlang $\gamma$ ist als
$$ \int_\gamma f(z)dz := \int_a^b f(\gamma(t))\gamma'(t)dt $$
definiert, falls $\gamma$ stetig differenzierbar auf $[a, b]$ ist. Ist $\gamma$ stückweise $C^1$, dann setzen wir (siehe Definition 2.5.1)
$$ \int_\gamma f(z)dz := \sum_{j=0}^m \int_{\gamma_j} f(z)dz. $$
[^1]

# Unterthemen
```dataview
LIST
WHERE contains(mytags, [[]])
SORT file.name ASC
```

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=76]]



