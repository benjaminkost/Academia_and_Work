---
"created date:": 22.10.2025 16:02
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270610 - Eigenschaften der Laplacetransformation|Eigenschaften der Laplacetransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Dualitätsprinzip für Laplacetransformation
  - Beweis 1.3.16
parent:
siblings:
child:
mathematical statement: "[[202510281810 - Dualitätsprinzip für Laplacetransformation|Dualitätsprinzip für Laplacetransformation]]"
---
# Beweis
Gleichung (1.68) folgt aus partieller Integration, denn
$$
\mathcal{L}[f'](s) = \int_0^\infty f'(t)e^{-ts} dt = [f(t)e^{-st}]^\infty_{t=0} + s \int_0^\infty f(t)e^{-st} dt = -f(0^+) + s\mathcal{L}[f](s).
$$
Die Behauptung (1.67) folgt induktiv aus (1.68): z.B. gilt für $m=2$
$$
\mathcal{L}[f''](s) = s\mathcal{L}[f'](s) - f'(0^+) = s(s\mathcal{L}[f](s) - f(0^+)) - f'(0^+) = s^2\mathcal{L}[f](s) - sf(0^+) - f'(0^+).
$$
Dies zeigt (i). Der Beweis von (ii) geht analog: Sei zunächst $m=1$. Für $\text{Re}(s) > \sigma_0$ erlauben die entsprechenden Sätze für uneigentliche Parameterintegrale, Differentiation und Integration zu vertauschen. Dies führt auf
$$
\mathcal{L}[f]'(s) = \frac{d}{ds} \int_0^\infty f(t)e^{-st} dt = \int_0^\infty \frac{d}{ds}(f(t)e^{-st}) dt = - \int_0^\infty tf(t)e^{-st} dt = \mathcal{L}[t \to (-t)f(t)](s).
$$
Für allgemeine $m \in \mathbb{N}$ folgt die Behauptung (ii) durch m-fache Anwendung dieser Identität.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=56]]


