---
"created date:": 22.10.2025 14:20
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510261910 - Erweiterung der Funktionenklasse|Erweiterung der Funktionenklasse]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Begründung für die Fouriertransformation von δ und 1
parent:
siblings:
child:
---
# Definition
Gleichung (1.55) folgt formal aus der [[202510262010 - Diracsche Delta-Funktion|Definition 1.2.28]] denn
$$ \hat{\delta}(\omega) = \int_{-\infty}^{\infty} \delta(t)e^{-i\omega t}dt = e^{-i\omega \cdot 0} = e^0 = 1 = 1(\omega) \quad \text{für alle } \omega \in \mathbb{R}. $$
Ebenso folgt (1.56) durch die Inverse FT
$$ (\mathcal{F}^{-1}[\delta])(t) = \frac{1}{2\pi}\int_{-\infty}^{\infty} \delta(\omega)e^{i\omega t}d\omega = \frac{1}{2\pi}e^{i0t} = \frac{1}{2\pi}1(t) \quad \text{für alle } t \in \mathbb{R}, $$
also $1 = 2\pi\mathcal{F}^{-1}[\delta]$ oder $\hat{1} = 2\pi\delta$ (wegen dem Umkehrsatz und der Linearität der Fouriertransformation).

![[Bildschirmfoto 2025-10-22 um 14.30.05.png|400]]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=45]]


