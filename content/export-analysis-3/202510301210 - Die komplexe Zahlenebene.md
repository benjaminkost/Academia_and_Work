---
"created date:": 22.10.2025 19:49
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301210 - Die komplexe Zahlenebene|Die komplexe Zahlenebene]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Die komplexe Zahlenebene
  - Definition 2.1.1
parent:
siblings:
child:
---
# Definition
Die Menge $\mathbb{R}^2$ mit $\begin{pmatrix} x \\ y \end{pmatrix} \in \mathbb{R}^2$ geschrieben $x+iy$, wird mit den Operationen
$$
\begin{align*}
(x+iy) + (u+iv) &:= (x+u) + i(y+v) \\
(x+iy) \cdot (u+iv) &:= (xu-yv) + i(xv+yu)
\end{align*}
$$
zum Körper $\mathbb{C}$ der komplexen Zahlen. Komplexkonjugation ist die Abbildung $\bar{\cdot}: \mathbb{C} \to \mathbb{C}, z \to \bar{z}$ wobei $\bar{z}=x-iy$ für $z=x+iy \in \mathbb{C}$. Der Real- und Imaginärteil von $z$ sind durch
$$
\text{Re } z := \frac{z+\bar{z}}{2} = x \quad \text{Im } z := \frac{z-\bar{z}}{2i} = y
$$
definiert und der Betrag von $z=x+iy$ ist $|z| := \sqrt{z\bar{z}} = \sqrt{x^2+y^2} \in \mathbb{R}$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=67]]



