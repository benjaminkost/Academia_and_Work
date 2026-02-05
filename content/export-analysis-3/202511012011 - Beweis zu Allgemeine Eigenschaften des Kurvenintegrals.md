---
"created date:": 22.10.2025 20:57
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
  - Beweis zu Allgemeine Eigenschaften des Kurvenintegrals
  - Beweis 2.5.6
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Behauptungen (i) und (ii) folgen direkt aus den Rechenregeln für Integrale über Intervalle von $\mathbb{R}$. Behauptung (iii) folgt aus
$$
\begin{align*}
\left| \int_\gamma f(z)dz \right| &\le \left| \int_a^b f(\gamma(t))\gamma'(t)dt \right| \\
&\le \int_a^b |f(\gamma(t))| \cdot |\gamma'(t)|dt \\
&\le \left( \max_{a\le t\le b} |f(\gamma(t))| \right) \cdot \int_a^b |\gamma'(t)|dt \\
&= \left( \max_{a\le t\le b} |f(\gamma(t))| \right) \cdot L(\gamma).
\end{align*}
$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=78]]


