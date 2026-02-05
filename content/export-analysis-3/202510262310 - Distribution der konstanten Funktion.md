---
"created date:": 22.10.2025 14:19
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510261910 - Erweiterung der Funktionenklasse|Erweiterung der Funktionenklasse]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Distribution der konstanten Funktion
  - Beispiel 1.2.31
  - Gleichung 1.55
  - Gleichung 1.56
parent:
siblings:
child:
---
# Beispiel
Die konstante 1-Funktion $1: \mathbb{R} \to \mathbb{R}$,
$$ 1(t) = 1 \quad \text{für alle } t \in \mathbb{R}, $$
definiert eine Distribution durch
$$ 1[f] = \int_{-\infty}^{\infty} f(t)1(t)dt = \int_{-\infty}^{\infty} f(t)dt \quad \text{für alle } f \in L^1(\mathbb{R}). $$
Offenbar ist $1[f]=\hat{f}(0)$ für jedes $f \in L^1(\mathbb{R})$. Mit der Linearität der Fouriertransformation folgt dass 1 linear ist.
Die Diracsche $\delta$-Funktion hat die Fouriertransformierte
$$ \hat{\delta} = 1 \quad (1.55) $$
Ebenso gilt
$$ \hat{1} = 2\pi\delta. \quad (1.56) $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=45]]



