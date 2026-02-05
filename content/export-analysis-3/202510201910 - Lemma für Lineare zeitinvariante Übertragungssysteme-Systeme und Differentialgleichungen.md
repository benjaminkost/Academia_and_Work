---
"created date:": 20.10.2025 09:51
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[Fourierreihe]]"
  - "[[202510201810 - Lineare zeitinvariante Übertragungssysteme]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-3
  - baby
aliases:
  - Lemma für LTI-Systeme und Differentialgleichungen
  - Lemma 1.1.50
  - Gleichung 1.23
parent:
siblings:
child:
proof: "[[202510202010 - Beweis für Lineare zeitinvariante Übertragungssysteme und Differentialgleichungen]]"
---
# Lemma
Sei $a_m \neq 0$ und $y$ die Lösung der Differentialgleichung
$$
L[y](t) = x(t) \quad \text{für alle } t \in \mathbb{R},
$$
(1.23)
wobei $L[y](t) := a_m y^{(m)}(t) + \dots + a_1 y'(t) + a_0 y(t)$ und $x$ eine T-periodische Funktion ist. Sei $P(z) = a_m z^m + \dots + a_0$ das zugehörige charakteristische Polynom. Sei weiter $P(ik\omega) \neq 0$ für alle $k \in \mathbb{Z}$, wobei $\omega = 2\pi/T$. Dann ist $x \to y$ ein T-periodisches LTI-System mit [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Frequenzgang]]
$$
d_k = 1/P(ik\omega) \quad \text{für } k \in \mathbb{Z}.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=22]]



