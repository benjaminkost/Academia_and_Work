---
"created date:": 22.10.2025 21:00
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
  - "[[202511020011 - Komplexe Kurvenintegrale und Kurvenintegrale im R|Komplexe Kurvenintegrale und Kurvenintegrale im R]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Komplexe Kurvenintegrale und Kurvenintegrale im R
parent:
siblings:
child:
---
# Definition
Analog wie komplexe Differenzierbarkeit kann das Konzept des komplexen Kurvenintegrals auch in Verbindung mit Kurvenintegralen im $\mathbb{R}^2$ gebracht werden.
Zur Erinnerung: Ist
$$ \vec{w}(x, y) = \begin{pmatrix} P(x, y) \\ Q(x, y) \end{pmatrix} $$
ein Vektorfeld definiert auf einer offenen Teilmenge $\Omega \subset \mathbb{R}^2$ und
$$ \tilde{\gamma} : [a, b] \to \Omega $$
eine stetig differenzierbare Funktion $\tilde{\gamma}(t) = \begin{pmatrix} \tilde{\gamma}_1(t) \\ \tilde{\gamma}_2(t) \end{pmatrix}$, dann heißt
$$ \int_{\tilde{\gamma}} \vec{w} \cdot d\vec{x} := \int_a^b [P(\tilde{\gamma}(t))\tilde{\gamma}'_1(t) + Q(\tilde{\gamma}(t))\tilde{\gamma}'_2(t)] dt $$
die Zirkulation von $\vec{w}$ entlang $\tilde{\gamma}$. (Hier schreiben wir $\vec{x} = \begin{pmatrix} x \\ y \end{pmatrix}$ für die Komponenten von $\vec{x}$.)
Weiter ist
$$ \int_{\tilde{\gamma}} \begin{pmatrix} -Q \\ P \end{pmatrix} \cdot d\vec{x} := \int_a^b [-Q(\tilde{\gamma}(t))\tilde{\gamma}'_1(t) + P(\tilde{\gamma}(t))\tilde{\gamma}'_2(t)] dt $$
der Fluss von $\vec{w}$ senkrecht zu $\tilde{\gamma}$. Ist $B$ ein Bereich mit (stückweise) glattem Rand $\partial B$, dann besagt der Satz von Green, dass
$$ \iint_B (Q_x - P_y) dxdy = \oint_{\partial B} \begin{pmatrix} P \\ Q \end{pmatrix} \cdot d\vec{x} $$
wobei $\partial B$ so zu parametrisieren ist, dass $B$ links von $\partial B$ (in Umlaufrichtung) liegt.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=79]]



