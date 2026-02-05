---
"created date:": 22.10.2025 11:41
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - bemerkung
  - definition
  - baby
aliases:
  - Notation der Fouriertransformation
  - Bemerkung 1.2.3
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Wir werden auch die Notation $\hat{f} = \mathcal{F}[f]$ für die Fouriertransformierte von $f$ verwenden sowie $\check{f} = \mathcal{F}^{-1}[f]$ für die inverse Fouriertransformierte. Die Abbildung $\mathcal{F} : f \to \mathcal{F}[f]$ wird auch als Fouriertransformation bezeichnet; ebenso wird $\mathcal{F}^{-1} : f \to \mathcal{F}^{-1}[f]$ die inverse Fouriertransformation genannt. Also
$$ \mathcal{F}[f](\omega) = \int_{-\infty}^{\infty} f(t) e^{-i\omega t} dt \quad \text{für alle } \omega \in \mathbb{R} $$
$$ \mathcal{F}^{-1}[f](t) = \frac{1}{2\pi} \int_{-\infty}^{\infty} f(\omega) e^{i\omega t} d\omega \quad \text{für alle } t \in \mathbb{R}. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=33]]




