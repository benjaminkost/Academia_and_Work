---
"created date:": 22.10.2025 19:23
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[satz]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270910 - Anwendung lineare Differentialgleichungssysteme 1. Ordung mit konstanten Koeffizienten|Anwendung lineare Differentialgleichungssysteme 1.Ordung mit konstanten Koeffizienten]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Allgemeine Lösungsformel für DGL-Systeme
  - Theorem 1.3.42
parent:
siblings:
child:
proof: "[[202510300610 - Beweis für allgemeine Lösungsformel für DGL-Systeme|Beweis für allgemeine Lösungsformel für DGL-Systeme]]"
---
# Satz
Seien $A \in \mathbb{C}^{n \times n}$ und $x_0 \in \mathbb{C}^n$ gegeben.
(i) Das homogene Anfangswertproblem
$$ x'(t) = Ax(t) \quad \text{für alle } t \in \mathbb{R} \quad \text{und} \quad x(0)=x_0 $$
hat die Lösung $x(t) = \exp(tA)x_0$.
(ii) Sei jetzt zusätzlich $b: \mathbb{R} \to \mathbb{C}^n$. Das inhomogene Anfangswertproblem
$$ x'(t) = Ax(t) + b(t) \quad \text{für alle } t \in \mathbb{R} \quad \text{und} \quad x(0) = x_0 $$
hat die Lösung
$$ x(t) = \exp(tA)x_0 + \int_0^t e^{(t-\tau)A}b(\tau)d\tau. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=64]]


