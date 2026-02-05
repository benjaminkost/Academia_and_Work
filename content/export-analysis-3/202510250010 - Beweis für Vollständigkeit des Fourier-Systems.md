---
"created date:": 22.10.2025 11:13
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510241010 - Hilbertraum|Hilbertraum]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Vollständigkeit des Fourier-Systems
  - Beweis 1.1.67
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Beweis. OEdA (Variablensubstitution) sei $T = 2\pi$. Angenommen, $f \in \mathcal{V}$ erfülle
$$ \langle e_k, f \rangle = 0 \quad \text{für alle } k \in \mathbb{Z}. \quad (1.31) $$
Sei $a \in [0, T]$ ein Punkt, in dem $f$ stetig ist. Angenommen, $f(a) \neq 0$. OEdA können wir annehmen, dass $f(a) > 0$ (der Beweis für $f(a) < 0$ geht analog). Dann existiert also ein $\delta > 0$ so dass
$$ f(t) > 0 \quad \text{für alle } t \in (a - \delta, a + \delta). \quad (1.32) $$

![[Bildschirmfoto 2025-10-22 um 11.14.13.png]]

Aus (1.31) leiten wir ab, dass $\langle p, f \rangle = 0$ für jedes 2π-periodische trigonometrische Polynom $p$, also insbesondere auch
$$ \int_0^{2\pi} p(t)^n f(t)dt = 0 \quad \text{für alle } n \in \mathbb{N} \quad \text{wobei } p(t) := 1 + \cos(t-a) - \cos(\delta). \quad (1.33) $$
Das trigonometrische Polynom $p(t)$ erfüllt für $t \in [0, 2\pi]$
$$ |p(t)| > 1 \Leftrightarrow t \in (a - \delta, a + \delta). $$
Damit ist $p(t)^n$ ein trigonometrisches Polynom, das für $n \to \infty$ die Form eines positiven Impulses auf $(a - \delta, a + \delta)$ der Höhe $p(a)^n \to \infty$ ($n \to \infty$) hat, siehe Abbildung 3. Daraus folgt mit (1.32) dass
$$ \int_0^{2\pi} p(t)^n f(t)dt > 0 $$
für genügend große $n \in \mathbb{N}$, im Widerspruch zu (1.33). Wir schließen, dass $f(a) = 0$ in jedem Stetigkeitspunkt $a$ gelten muss.
Damit folgt auch $f(t^+) = f(t^-) = 0$ für jede der maximal endlich vielen Sprungstellen $t$ von $f$, also $f \equiv 0$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=29]]


