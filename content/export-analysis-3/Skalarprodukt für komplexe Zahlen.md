---
"created date:": 03.11.2025 10:15
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510241010 - Hilbertraum|Hilbertraum]]"
  - "[[Lineare Algebra]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - definition
aliases:
  - Definition 1.1.55
  - Linearität im 2. Argument von Hilbertraum
  - Hermitizität von Hilbertraum
  - Positive Definitheit von Hilbertraum
parent:
siblings:
child:
---
# Definition
Sei $V$ ein $\mathbb{C}$-[[Vektorraum]]. Dann heißt eine [[Abbildung]] $$\langle\cdot, \cdot\rangle : V \times V \to \mathbb{C}$$$$(v, w) \mapsto \langle v, w\rangle$$ ein [[Skalarprodukt]] auf $V$, falls gilt:
(i) (Linearität im 2. Argument) Es gilt $$\langle v, \alpha u + \beta w\rangle = \alpha\langle v, u\rangle + \beta\langle v, w\rangle$$ für alle $\alpha, \beta \in \mathbb{C}$ und $u, v, w \in V$.

(ii) (Hermitizität) $$\langle v, w\rangle = \overline{\langle w, v\rangle}$$ für alle $v, w \in V$.

(iii) (Positive Definitheit) Für alle $v \in V$ ist $\langle v, v\rangle \ge 0$ und $\langle v, v\rangle = 0$ genau dann, wenn $v = 0$.
[^1]
# Beispiele


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
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V7.pdf#page=10]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=25]]


