---
"created date:": 22.10.2025 12:34
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[202510261710 - Produktregel für die Faltung]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Faltungssatz
  - Beweis 1.2.26
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Beweis. Durch Vertauschen der Integrationsreihenfolge und mit der Variablensubstitution $\theta = t-s$ folgt
$$ \widehat{f*g}(\omega) = \int_{-\infty}^{\infty} \left(\int_{-\infty}^{\infty} f(t-s)g(s)ds\right) e^{-i\omega t} dt $$
$$ = \int_{-\infty}^{\infty} g(s) \left(\int_{-\infty}^{\infty} f(t-s)e^{-i\omega t}dt\right) ds $$
$$ = \int_{-\infty}^{\infty} g(s) \left(\int_{-\infty}^{\infty} f(\theta)e^{-i\omega(s+\theta)}d\theta\right) ds $$
$$ = \left(\int_{-\infty}^{\infty} f(\theta)e^{-i\omega\theta}d\theta\right) \left(\int_{-\infty}^{\infty} g(s)e^{-i\omega s}ds\right) $$
$$ = \hat{f}(\omega)\hat{g}(\omega) \quad \text{für alle } \omega \in \mathbb{R}. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=42]]
	


