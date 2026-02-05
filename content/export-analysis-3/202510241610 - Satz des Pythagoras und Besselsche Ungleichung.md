---
"created date:": 22.10.2025 11:01
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
  - Satz des Pythagoras und Besselsche Ungleichung
  - Lemma 1.1.62
parent:
siblings:
child:
proof: "[[202510241810 - Beweis für Satz des Pythagoras und Besselsche Ungleichung]]"
---
# Lemma
Sei $\{e_n\}_{n \in \mathbb{Z}}$ ein [[202510241310 - Orthonormalsystem|Orthonormalsystem]] in einem [[202510241010 - Hilbertraum|Hilbertraum]] $\mathcal{H}$. Dann gilt:
(i) Für jedes $n \in \mathbb{N}_0$ und alle $\{\gamma_k\}_{k=-n}^n \subset \mathbb{C}$
$$ \left\| \sum_{k=-n}^n \gamma_k e_k \right\|^2 = \sum_{k=-n}^n |\gamma_k|^2. $$
(ii) Für jedes $f \in \mathcal{H}$ und jede endliche Teilmenge $\Omega \subset \mathbb{Z}$ gilt
$$ \sum_{j \in \Omega} |\langle e_j, f \rangle|^2 \le \|f\|^2. \quad \text{(Besselsche Ungleichung)}. $$
(iii) Für $f \in \mathcal{H}$ sei
$$ S_f^n = \sum_{k=-n}^n c_k e_k \quad \text{wobei } c_k = \langle e_k, f \rangle. $$
Dann gilt
$$ \|f\|^2 = \|S_f^n\|^2 + \|f - S_f^n\|^2. $$
[^1]

# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510241710 - Bemerkung zu Konvergenz der Koeffizienten]]
- [[Satz des Pythagoras]]
- [[202510241810 - Beweis für Satz des Pythagoras und Besselsche Ungleichung]]
## Quellen
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V8.pdf]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=27]]


