---
"created date:": 22.10.2025 19:18
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270810 - Funktionalkalkül für Matrizen und matrixwertife Funktion|Funktionalkalkül für Matrizen und matrixwertife Funktion]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis zu Laplace-Transformierte von e hoch tA
parent:
siblings:
child:
mathematical statement: "[[202510300010 - Beispiel zu Laplace-Transformierte von e hoch tA]]"
---
# Beweis
Für $k \in \mathbb{N}_0$ gilt wegen Beispiel 1.3.19 und der Linearität der Laplace-Transformation
$$
\mathcal{L}[t \to t^k A^k](s) = \mathcal{L}[t \to t^k](s)A^k = \frac{k!}{s^{k+1}}A^k
$$
falls Re$(s) > 0$, also $\mathcal{L}[t \to \frac{t^k}{k!} A^k](s) = \frac{1}{s^{k+1}}A^k$. Setzen wir in $\exp(tA) = \sum_{k=0}^\infty \frac{t^k}{k!}A^k$ für die Summanden ein, so liefert Lemma 1.3.33, wobei wir $|s| > \|A\|$ fordern:
$$
\mathcal{L}[t \to e^{tA}](s) = \sum_{k=0}^\infty \frac{A^k}{s^{k+1}} = \frac{1}{s}\sum_{k=0}^\infty \left(\frac{A}{s}\right)^k = \frac{1}{s}\left(I - \frac{1}{s}A\right)^{-1} = (sI - A)^{-1}.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=62]]


