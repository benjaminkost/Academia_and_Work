---
"created date:": 22.10.2025 16:08
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270610 - Eigenschaften der Laplacetransformation|Eigenschaften der Laplacetransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Grenzwerte der Laplace-Transformation
  - Lemma 1.3.20
parent:
siblings:
child:
proof:
---
# Lemma
Sei $f : [0, \infty) \to \mathbb{C}$ stetig und höchstens exponentiell wachsend (Konvergenzabszisse $\sigma_0$). Sei außerdem $f'$ stückweise stetig. Dann gilt für $\text{Re}(s) > \sigma_0$:
$$
f(0^+) = \lim_{\text{Re}(s) \to \infty} s\mathcal{L}[f](s).
$$
Existiert $\lim_{t\to\infty} f(t) \in \mathbb{C}$, dann gilt
$$
\lim_{t\to\infty} f(t) = \lim_{s\to 0} s\mathcal{L}[f](s).
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
- [[202510290110 - Beweisskizze für Grenzwerte der Laplace-Transformation]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=57]]


