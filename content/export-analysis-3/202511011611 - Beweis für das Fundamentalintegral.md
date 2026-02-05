---
"created date:": 22.10.2025 20:55
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für das Fundamentalintegral
  - Beweis 2.5.4
parent:
siblings:
child:
mathematical statement: "[[202511011511 - Das Fundamentalintegral|Das Fundamentalintegral]]"
---
# Beweis
Mit dem Weg
$$ \gamma(t) = z_0 + re^{it} \quad t \in [0, 2\pi] $$
gilt
$$ \oint_{|z-z_0|=r} (z - z_0)^m dz = \int_\gamma (z - z_0)^m dz = \int_0^{2\pi} (re^{it})^m i r e^{it} dt = i r^{m+1} \int_0^{2\pi} e^{i(m+1)t} dt. $$
Falls $m \ne -1$ erhalten wir mit $e^{i(m+1)2\pi} = 1 = e^0$
$$ \int_{|z-z_0|=r} (z - z_0)^m dz = i r^{m+1} \left[ \frac{e^{i(m+1)t}}{i(m+1)} \right]_0^{2\pi} = 0. $$
Im Fall $m = -1$ erhalten wir
$$ \oint_{|z-z_0|=r} (z - z_0)^{-1} dz = i r^0 \int_0^{2\pi} e^0 dt = 2\pi i. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=77]]


