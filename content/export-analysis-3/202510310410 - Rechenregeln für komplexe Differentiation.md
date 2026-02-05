---
"created date:": 22.10.2025 20:07
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Differenzierbarkeit]]"
tags:
  - 3-Semester
  - 1-Semester
  - bemerkung
  - baby
aliases:
  - Rechenregeln für komplexe Differentiation
  - Bemerkung 2.2.5
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Die Rechenregeln für komplexe Differentiation sind analog wie für reelle Funktionen: Für zwei (differenzierbare) Funktionen $f, g : U \to \mathbb{C}$ und $\alpha, \beta \in \mathbb{C}$ gilt (hier lassen wir die Argumente weg)
$$
\begin{align*}
(\alpha f + \beta g)' &= \alpha f' + \beta g' & \text{(Linearität)} \\
(fg)' &= f'g + fg' & \text{(Leibniz-Regel)} \\
\left(\frac{f}{g}\right)' &= \frac{f'g - fg'}{g^2} & \text{(Quotientenregel)} \\
(g \circ f)' &= (g' \circ f) f' & \text{(Kettenregel)}
\end{align*}
$$
Bei der Quotientenregel wird vorausgesetzt, dass $g$ keine Nullstellen besitzt.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=69]]



