---
"created date:": 22.10.2025 14:16
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
  - Delta-Funktion als Grenzwert
  - Beispiel 1.2.29
  - Gleichung 1.51
  - Gleichung 1.52
parent:
siblings:
child:
---
# Beispiel
Für $n \in \mathbb{N}$ sei
$$ \delta_n(t) := \begin{cases} n & t \in [-1/(2n), 1/(2n)] \\ 0 & \text{sonst.} \end{cases} $$
Dann gilt
$$ \int_{-\infty}^{\infty} \delta_n(t)dt = 1 \quad \text{für alle } n \in \mathbb{N} \quad (1.51) $$
und
$$ \lim_{n\to\infty} \int_{-\infty}^{\infty} f(t)\delta_n(t)dt = f(0) \quad \text{für jede in 0 stetige Funktion } f:\mathbb{R}\to\mathbb{C}. \quad (1.52) $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=44]]



