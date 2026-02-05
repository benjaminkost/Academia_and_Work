---
"created date:": 22.10.2025 19:04
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510271610 - Faltung und Laplacetransformation|Faltung und Laplacetransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Beispiel für Faltung t und cos(t)
  - Beispiel 1.3.26
parent:
siblings:
child:
---
# Beispiel
Sei $f(t) = t$ und $g(t) = \cos(t)$. Dann gilt
$$
(f*g)(t) = \int_0^t (t-\tau)\cos(\tau)d\tau = [t\sin(\tau)]_{\tau=0}^t - [(\cos(\tau) + \tau\sin(\tau))]_{\tau=0}^t = t\sin(t) - \cos(t) + 1 - t\sin(t) = 1-\cos(t).
$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=59]]



