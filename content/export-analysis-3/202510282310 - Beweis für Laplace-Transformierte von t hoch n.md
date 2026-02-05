---
"created date:": 22.10.2025 16:05
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
  - Beweis für Laplace-Transformaierte von t hoch n
  - Beweis 1.3.19
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Betrache die Funktion $f(t) = t^n$. Dann gilt $f^{(n)}(t) = n!$ und $\mathcal{L}[t \to 1](s) = 1/s$ für $\text{Re}(s)>0$ (nach [[202510280310 - Laplace-Transformierte der Exponentialfunktion|Beispiel 1.3.3]]), also mit [[202510281810 - Dualitätsprinzip für Laplacetransformation|Lemma 1.3.16]] (i)
$$
\frac{n!}{s} = \mathcal{L}[f^{(n)}](s) = s^n\mathcal{L}[f](s).
$$
Hier haben wir verwendet dass $f(0^+) = f'(0^+) = \dots = f^{(n-1)}(0^+) = 0$. Division durch $s^n$ gibt die Behauptung.
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


