---
"created date:": 22.10.2025 11:02
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510241010 - Hilbertraum|Hilbertraum]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - bemerkung
  - baby
aliases:
  - Bemerkung zu Konvergenz der Koeffizienten
  - Bemerkung 1.1.63
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Sei $f \in \mathcal{H}$ beliebig und
$$ s_n := \sum_{k=-n}^n |\langle e_k, f \rangle|^2 \quad \text{für alle } n \in \mathbb{N}. $$
Dann impliziert die Besselsche Ungleichung ([[202510241610 - Satz des Pythagoras und Besselsche Ungleichung|Lemma 1.1.62]] iii), dass $s_n \le \|f\|^2$ für jedes $n \in \mathbb{N}$. Daraus folgt, dass die Folge $\{s_n\}_{n \in \mathbb{N}}$ beschränkt ist. Da sie außerdem monoton wächst, existiert der Grenzwert und erfüllt
$$ s = \lim_{n \to \infty} s_n = \lim_{n \to \infty} \sum_{k=-n}^n |\langle e_k, f \rangle|^2 \le \|f\|^2. $$
Insbesondere gilt für die Restsummen
$$ \lim_{n \to \infty} \sum_{k=n+1}^{\infty} \left( |\langle e_k, f \rangle|^2 + |\langle e_{-k}, f \rangle|^2 \right) \to 0 \quad \text{für } n \to \infty. $$
[^1]


# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510241610 - Satz des Pythagoras und Besselsche Ungleichung|Satz des Pythagoras und Besselsche Ungleichung]]
## Quellen
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V8.pdf#page=6]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=27]]



