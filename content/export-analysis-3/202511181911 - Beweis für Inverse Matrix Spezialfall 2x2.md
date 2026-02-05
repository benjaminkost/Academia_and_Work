---
"created date:": 18.11.2025 17:27
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - beweis für Inverse Matrix Spezialfall 2x2
parent:
siblings:
child:
mathematical statement: "[[Inverse Matrix Spezialfall 2x2]]"
---
# Beweis
Um zu beweisen, dass die angegebene Formel für die inverse Matrix $A^{-1}$ korrekt ist, müssen wir zeigen, dass das Produkt der Matrix $A$ und ihrer Inversen $A^{-1}$ die Einheitsmatrix $I$ ergibt. Die Einheitsmatrix für den 2x2-Fall ist:
$$
I = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}
$$
Die Bedingung lautet also: $A \cdot A^{-1} = I$.

Wir setzen die Matrizen $A$ und die vorgeschlagene Formel für $A^{-1}$ in die Gleichung ein:
$$
A \cdot A^{-1} = \begin{pmatrix} a & b \\ c & d \end{pmatrix} \cdot \frac{1}{ad - bc} \begin{pmatrix} d & -b \\ -c & a \end{pmatrix}
$$
Den Skalar $\frac{1}{ad - bc}$ können wir vor die Matrizenmultiplikation ziehen:
$$
= \frac{1}{ad - bc} \begin{pmatrix} a & b \\ c & d \end{pmatrix} \begin{pmatrix} d & -b \\ -c & a \end{pmatrix}
$$
Nun führen wir die Matrizenmultiplikation durch:
$$
= \frac{1}{ad - bc} \begin{pmatrix} (a \cdot d + b \cdot (-c)) & (a \cdot (-b) + b \cdot a) \\ (c \cdot d + d \cdot (-c)) & (c \cdot (-b) + d \cdot a) \end{pmatrix}
$$
Jetzt vereinfachen wir die einzelnen Elemente der resultierenden Matrix:
$$
= \frac{1}{ad - bc} \begin{pmatrix} ad - bc & -ab + ab \\ cd - cd & -cb + da \end{pmatrix}
$$
$$
= \frac{1}{ad - bc} \begin{pmatrix} ad - bc & 0 \\ 0 & ad - bc \end{pmatrix}
$$
Zuletzt multiplizieren wir den Skalar $\frac{1}{ad - bc}$ mit jedem Element der Matrix:
$$
= \begin{pmatrix} \frac{ad - bc}{ad - bc} & \frac{0}{ad - bc} \\ \frac{0}{ad - bc} & \frac{ad - bc}{ad - bc} \end{pmatrix}
$$
$$
= \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} = I
$$
Da $A \cdot A^{-1} = I$ gilt, ist die Formel für die Inverse korrekt.

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


