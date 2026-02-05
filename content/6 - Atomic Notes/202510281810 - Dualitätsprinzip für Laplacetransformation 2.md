---
"created date:": 22.10.2025 15:59
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
  - Dualitätsprinzip für Laplacetransformation
  - Lemma 1.3.16
parent:
siblings:
child:
proof: "[[202510282010 - Beweis für Dualitätsprinzip für Laplacetransformation|Beweis für Dualitätsprinzip für Laplacetransformation]]"
---
# Lemma
Sei $m \in \mathbb{N}$. Dann gelten folgende Aussagen:
(i) Sei $m \in \mathbb{N}$, $f$ und $f^{(n)}$, $1 \le n \le m-1$, stetig auf $[0, \infty)$ mit höchstens exponentiellem Wachstum (Konvergenzabszisse $\sigma_0 \in \mathbb{R}$) und $f^{(m)}$ sei stückweise stetig auf $[0, \infty)$. Dann gilt für alle $s \in \mathbb{C}$ mit $\text{Re}(s) > \sigma_0$:
$$
\mathcal{L}[f^{(m)}](s) = s^m \mathcal{L}[f](s) - s^{m-1}f(0^+) - \dots - sf^{(m-2)}(0^+) - f^{(m-1)}(0^+).
$$
(ii) Sei $f : [0, \infty) \to \mathbb{C}$ stückweise stetig und höchstens exponentiell wachsend (Konvergenzabszisse $\sigma_0$). Dann gilt für $\text{Re}(s) > \sigma_0$:
$$
\mathcal{L}[t \to (-1)^m t^m f(t)](s) = \mathcal{L}[f]^{(m)}(s).
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
- [[202510281910 - Spezialfall von Dualitätsprinzip für Laplacetransformation|Spezialfall von Dualitätsprinzip für Laplacetransformation]]
- [[202510282010 - Beweis für Dualitätsprinzip für Laplacetransformation]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=55]]


