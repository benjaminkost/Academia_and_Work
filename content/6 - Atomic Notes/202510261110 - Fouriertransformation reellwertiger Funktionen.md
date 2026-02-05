---
"created date:": 22.10.2025 12:31
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[fouriertransformation reellwertiger, gerader und ungerader Funktionen]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Fouriertransformation reellwertiger Funktionen
  - Lemma 1.2.22
parent:
siblings:
child:
proof:
---
# Lemma
Sei $f \in L^1(\mathbb{R})$ und $f: \mathbb{R} \to \mathbb{R}$ dann gilt
$$ \hat{f}(-\omega) = \overline{\hat{f}(\omega)} \quad \text{für alle } \omega \in \mathbb{R}. \quad (1.48) $$
Außerdem gilt für alle $\omega \in \mathbb{R}$
$$ \hat{f}(\omega) \text{ ist } \begin{cases} \text{reell} & \text{falls f gerade ist} \\ \text{imaginär} & \text{falls f ungerade ist.} \end{cases} \quad (1.49) $$
Für die Zerlegung $f = f_g + f_u$ in geraden und ungeraden Anteil gilt
$$ \widehat{f_g}(\omega) = \text{Re}(\hat{f}(\omega)) \quad \text{für alle } \omega \in \mathbb{R} $$
$$ \widehat{f_u}(\omega) = i\text{Im}(\hat{f}(\omega)) \quad \text{für alle } \omega \in \mathbb{R}. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=41]]


