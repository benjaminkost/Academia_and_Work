---
"created date:": 22.10.2025 12:08
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[eigenschaften von fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - bemerkung
  - baby
aliases:
  - Reziprozität von Zeit und Frequenz
  - Bemerkung 1.2.12
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Im Zusammenhang mit (vi) von Lemma 1.2.11 sprechen wir auch von Reziprozität von Zeit und Frequenz: Gegeben sei eine nichtnegative Funktion $f : \mathbb{R} \to \mathbb{R}$. Definieren wir
$$ f_n(t) := nf(nt) \quad \text{für alle } t \in \mathbb{R} $$
für $n \in \mathbb{N}$, dann gilt
$$ \hat{f_n}(0) = \int_{-\infty}^{\infty} f_n(t)dt = \int_{-\infty}^{\infty} f(t)dt = \hat{f}(0), $$
d.h. die Fläche unter dem Graphen von $f_n$ bleibt gleich, während
$$ \hat{f_n}(\omega) = \hat{f}(\omega/n) \quad \text{für } \omega \in \mathbb{R}. $$
Mit zunehmendem $n$ wird also
der Graph von
$$ \begin{cases} f_n & \text{zunehmend schmaler und höher} \\ \hat{f_n} & \text{zunehmend breiter.} \end{cases} \quad \text{und} $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=38]]



