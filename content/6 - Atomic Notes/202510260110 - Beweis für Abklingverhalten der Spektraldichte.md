---
"created date:": 22.10.2025 12:11
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[eigenschaften von fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Abklingverhalten der Spektraldichte
  - Beweis 1.2.14
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Beweis. Ist $f' \in L^1(\mathbb{R})$, dann ist $\widehat{f'}$ beschränkt (mit Konstante $\|f'\|_1$) und stetig (siehe Lemma 1.2.5). Mit Lemma 1.2.13 folgt
$$ |\hat{f}(\omega)| = \left| \frac{1}{i\omega} \left( \widehat{f'}(\omega) + \sum_{k=1}^N (f(t_k^+) - f(t_k^-))e^{-i\omega t_k} \right) \right| $$
$$ \le \frac{1}{|\omega|} \left( \|f'\|_1 + \sum_{k=1}^N |f(t_k^+) - f(t_k^-)| \right) \quad \text{für alle } \omega \neq 0, $$
also Behauptung (1.43).
Der Beweis von (ii) geht analog und folgt dem Muster des Beweises von Lemma 1.1.41.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=39]]


