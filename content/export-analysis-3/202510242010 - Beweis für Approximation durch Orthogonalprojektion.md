---
"created date:": 22.10.2025 11:06
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510241010 - Hilbertraum|Hilbertraum]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Approximation durch Orthogonalprojektion
  - Beweis 1.1.64
parent:
siblings:
child:
mathematical statement: "[[202510241910 - Approximation durch Orthonalprojektion|Approximation durch Orthonalprojektion]]"
---
# Beweis
Seien $\{\gamma_j\}_{j=-n}^n \subset \mathbb{C}$ beliebig und $g = \sum_{j=-n}^n \gamma_j e_j$. Definiere
$$ u := f - S_f^n $$
$$ v := S_f^n - g. $$
Ähnlich wie im Beweis von [[202510241610 - Satz des Pythagoras und Besselsche Ungleichung|Lemma 1.1.62]] lässt sich leicht prüfen, dass $u$ und $v$ [[202509241009 - Orthogonalität|orthogonal]] sind, d.h. $\langle u, v \rangle = 0$. Daher gilt
$$ \|f - g\|^2 = \|u + v\|^2 = \|u\|^2 + \|v\|^2 = \|f - S_f^n\|^2 + \|S_f^n - g\|^2, $$
also
$$ \|f - S_f^n\| \le \|f - g\| $$
mit Gleichheit genau dann wenn $\|S_f^n - g\| = 0$, d.h. $S_f^n = g$.
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
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V9.pdf]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=29]]


