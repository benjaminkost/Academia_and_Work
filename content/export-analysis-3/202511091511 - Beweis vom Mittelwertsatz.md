---
"created date:": 29.10.2025 22:45
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Cauchy Integralformel]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis vom Mittelwertsatz
  - Beweis 2.7.6
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Die Cauchy-Integralformel gibt
$$\begin{aligned}f(z_0) &= \frac{1}{2\pi i} \oint_{|z-z_0|=r} \frac{f(z)}{z-z_0} dz \\&= \frac{1}{2\pi i} \int_0^{2\pi} \frac{f(z_0 + re^{it})}{(z_0 + re^{it}) - z_0} rie^{it} dt \\&= \frac{1}{2\pi i} \int_0^{2\pi} \frac{f(z_0 + re^{it})}{re^{it}} rie^{it} dt\end{aligned}$$
also die Behauptung.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=85]]


