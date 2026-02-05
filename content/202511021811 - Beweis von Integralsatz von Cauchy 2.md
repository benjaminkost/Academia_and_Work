---
"created date:": 22.10.2025 22:24
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
  - "[[202511021711 - Integralsatz von Cauchy|Der Integralsatz von Cauchy]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis von Integralsatz von Cauchy
  - Beweis 2.6.1
parent:
siblings:
child:
mathematical statement: "[[202511021711 - Integralsatz von Cauchy|Integralsatz von Cauchy]]"
---
# Beweis
Wir geben vereinfachend nur den Beweis für den Fall, wo die Ableitung $f'$ stetig ist ; der allgemeine Fall wird durch den Satz von Goursat behandelt und ist etwas trickreich . Die Kurve $\gamma$ berandet einen Bereich $B \subset U$ (bzw. berandet die entsprechende Kurve $\tilde{\gamma}$ einen Bereich $\tilde{B} \subset \mathbb{R}^2$) . Nach Lemma 2.5.10 gilt

$$Re(\oint_{\gamma} f(z) dz) = \oint_{\tilde{\gamma}} \begin{pmatrix} u \\ -v \end{pmatrix} \cdot d\vec{x}$$

$$= \int_{\tilde{B}} (-v_x - u_y) dx dy$$

mit Satz von Green

$$= 0$$

wegen den Cauchy-Riemann-Gleichungen . Analog gilt (wieder mit dem Satz von Green und den Cauchy-Riemann-Gleichungen)

$$Im(\oint_{\gamma} f(z) dz) = \oint_{\gamma} \begin{pmatrix} v \\ u \end{pmatrix} \cdot d\vec{x} = \int_{B} (u_x - v_y) dx dy = 0$$

.

Hat $\gamma$ endlich viele Überschneidungen, so lässt sich die Kurve in endlich viele einfache Schleifen zerlegen . Das Kurvenintegral über jede dieser Kurven ist aber gleich 0 .
[^1]
Hat $\gamma$ endlich viele Überschneidungen, so lässt sich die Kurve in endlich viele einfache Schleifen zerlegen. Das Kurvenintegral über jede dieser Kurven ist aber gleich 0.
[^2]

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

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=81]]


