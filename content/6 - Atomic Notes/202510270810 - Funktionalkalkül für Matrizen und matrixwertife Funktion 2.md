---
"created date:": "22.10.2025 14:38"
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - "Funktionalkalkül für Matrizen und matrixwertife Funktion"
parent: 
siblings: 
child: 
---
# Definition
Identitäten für Skalare, wie z.B. die Formel für die geometrische Reihe:
$$ \sum_{k=0}^{\infty} q^k = \frac{1}{1-q} = (1-q)^{-1} \quad \text{für } |q| < 1 $$
lassen sich auf Matrizen verallgemeinern.

Konkret sei $A = (A_{j,k})_{j,k=1}^n \in \mathbb{C}^{n \times n}$ eine $n \times n$-Matrix mit komplexen Einträgen. Dazu betrachten wir statt $q^k$ das $k$-fache Matrixprodukt $A^k = \underbrace{A \cdot \ldots \cdot A}_{k \text{ Faktoren}}$, ersetzen die $1$ durch die $n \times n$-Identitätsmatrix $I$ und betrachten den Ausdruck $(I-A)^{-1}$ als die Matrixinverse von $(I-A)$.

Die Einschränkung $|q| < 1$ übersetzt sich in die Schranke $\|A\| < 1$ mit der (Matrix-)Norm:
$$ \|A\| = \sup_{x \in \mathbb{C}^n, \|x\|=1} \|Ax\| $$
wobei hier $\|x\| = \sqrt{\sum_{j=1}^n |x_j|^2}$ die Euklidische Norm eines Vektors $x \in \mathbb{C}^n$ ist.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=61]]



