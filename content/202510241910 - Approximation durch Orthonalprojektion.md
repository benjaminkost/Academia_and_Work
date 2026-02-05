---
"created date:": 22.10.2025 11:05
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510241010 - Hilbertraum|Hilbertraum]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Approximation durch Orthonalprojektion
  - Lemma 1.1.64
parent:
siblings:
child:
proof: "[[202510242010 - Beweis für Approximation durch Orthogonalprojektion]]"
---
# Lemma
Sei $\{e_n\}_{n \in \mathbb{Z}}$ ein [[202510241310 - Orthonormalsystem|Orthonormalsystem]] in einem [[202510241010 - Hilbertraum|Hilbertraum]] $\mathcal{H}$ und $f \in \mathcal{H}$. Dann ist $S_f^n$ die beste Approximation an $f$ im [[Spann|Unterraum]] $\text{span}\{e_j\}_{j=-n}^n$, d.h.
$$ \|f - S_f^n\| \le \left\| f - \sum_{j=-n}^n \gamma_j e_j \right\| \quad \text{für alle } \{\gamma_j\}_{j=-n}^n \subset \mathbb{C}. $$
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
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V8.pdf]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=29]]


