---
"created date:": 22.10.2025 22:19
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
  - "[[202511020011 - Komplexe Kurvenintegrale und Kurvenintegrale im R|Komplexe Kurvenintegrale und Kurvenintegrale im R]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis zu Beziehung zwischen komplexen und reellen Kurvenintegralen
parent:
siblings:
child:
mathematical statement: "[[202511020111 - Beziehung zwischen komplexen und reellen Kurvenintegralen|Beziehung zwischen komplexen und reellen Kurvenintegralen]]"
---
# Beweis
Wir schreiben $\gamma(t) = \gamma_1(t) + i\gamma_2(t)$, d.h. $\gamma_1(t) = \text{Re}(\gamma(t))$ und $\gamma_2(t) = \text{Im}(\gamma(t))$. Nach Definition des Kurvenintegrals gilt dann:
$$
\int_{\gamma} f(z)dz = \int_{a}^{b} f(\gamma(t))\gamma'(t)dt
$$
$$
= \int_{a}^{b} [u(\tilde{\gamma}(t))\gamma'_1(t) - v(\tilde{\gamma}(t))\gamma'_2(t)] dt + i \int_{a}^{b} [u(\tilde{\gamma}(t))\gamma'_2(t) + v(\tilde{\gamma}(t))\gamma'_1(t)] dt
$$
$$
= \int_{\tilde{\gamma}} \begin{pmatrix} u \\ -v \end{pmatrix} \cdot d\vec{x} + i \int_{\tilde{\gamma}} \begin{pmatrix} v \\ u \end{pmatrix} \cdot d\vec{x}
$$
Daraus folgt die Behauptung.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=80]]


