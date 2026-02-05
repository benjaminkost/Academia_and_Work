---
"created date:": 29.10.2025 23:36
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Laurentreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - Lemma
aliases:
  - Regeln zur Konstruktion von Laurent-Reihen
  - Lemma 2.9.5
parent:
siblings:
child:
proof:
---
# Lemma
Es gelten folgende Regeln:
(i) Sei $g : B_R(z_0) \to \mathbb{C}$ holomorph auf $B_R(z_0)$ und $m \in \mathbb{N}_0$. Dann ist die Laurent-Reihe der Funktion
$$f(z) := \frac{g(z)}{(z-z_0)^m}$$
auf $A_{0,R}(z_0) = \{z \in \mathbb{C} \setminus \{z_0\} \mid |z-z_0|<R\}$ gegeben durch
$$f(z) = \sum_{k=-m}^{\infty} \frac{g^{(k+m)}(z_0)}{(k+m)!} (z-z_0)^k .$$
(ii) Angenommen, $g : B_R(0) \to \mathbb{C}$ sei holomorph auf $B_R(0)$. Dann ist die Laurent-Reihe der Funktion
$$f(z) := g\left(\frac{1}{z-z_0}\right)$$
auf $\{ z \in \mathbb{C} \mid |z-z_0| > 1/R \} = A_{1/R,\infty}(z_0)$ gegeben durch
$$f(z) = \sum_{k=0}^{\infty} \frac{g^{(k)}(0)}{k!} (z-z_0)^{-k} .$$
[^1]
[[202511101511 - Beweis für Regeln zur Konstruktion von Laurent-Reihen]]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=93]]


