---
"created date:": 22.10.2025 21:03
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
  - "[[202511020011 - Komplexe Kurvenintegrale und Kurvenintegrale im R|Komplexe Kurvenintegrale und Kurvenintegrale im R]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beziehung zwischen komplexen und reellen Kurvenintegralen
  - Lemma 2.5.10
parent:
siblings:
child:
proof:
  - "[[202511011211 - Beweis zu Beziehung zwischen komplexen und reellen Kurvenintegralen|Beweis zu Beziehung zwischen komplexen und reellen Kurvenintegralen]]"
---
# Lemma
Die Beziehung zwischen dem komplexen Kurvenintegral und dem reellen Kurvenintegralen kann wie folgt ausgedrückt werden:
Sei $\gamma : [a, b] \to \mathbb{C}$ eine Kurve, die stückweise $C^1$ ist. Sei $f : \text{im}(\gamma) \to \mathbb{C}$. Wir definieren die Kurve $\tilde{\gamma} : [a, b] \to \mathbb{R}^2$ durch $\tilde{\gamma}(t) = \begin{pmatrix} \text{Re}(\gamma(t)) \\ \text{Im}(\gamma(t)) \end{pmatrix}$ und schreiben $f(x + iy) = u(x, y) + iv(x, y)$. Dann gilt
$$ \text{Re} \int_\gamma f(z)dz = \int_{\tilde{\gamma}} \begin{pmatrix} u \\ -v \end{pmatrix} \cdot d\vec{x} $$
$$ \text{Im} \int_\gamma f(z)dz = \int_{\tilde{\gamma}} \begin{pmatrix} v \\ u \end{pmatrix} \cdot d\vec{x}. $$
[^1]
Definieren wir also das Vektorfeld $w(x, y) = \begin{pmatrix} u(x, y) \\ -v(x, y) \end{pmatrix}$, dann ist der Realteil des Kurvenintegrals gleich der Zirkulation von $w$ entlang $\tilde{\gamma}$, und der Imaginärteil des Kurvenintegrals gleich dem Fluss von $w$ senkrecht zu $\tilde{\gamma}$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=79]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=80]]


