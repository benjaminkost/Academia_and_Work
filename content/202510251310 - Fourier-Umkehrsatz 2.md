---
"created date:": 22.10.2025 11:56
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[satz]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Fourier-Umkehrsatz
  - Integraltheorem
  - Theorem 1.2.7
parent:
siblings:
child:
proof: "[[202510251410 - Beweis für Fourier-Umkehrsatz]]"
---
# Satz
Sei $f \in L^1(\mathbb{R})$ stückweise stetig differenzierbar, dann gilt für jedes $t \in \mathbb{R}$
$$ \frac{1}{2}\left(f(t^+) + f(t^-)\right) = \check{\hat{f}}(t). $$
Insbesondere gilt
$$ f(t) = \frac{1}{2\pi} \int_{-\infty}^{\infty} \hat{f}(\omega)e^{i\omega t}d\omega $$
an jeder Stetigkeitsstelle $t$ von $f$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=36]]



