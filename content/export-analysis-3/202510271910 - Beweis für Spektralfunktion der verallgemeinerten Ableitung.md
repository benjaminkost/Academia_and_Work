---
"created date:": 22.10.2025 15:16
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270310 - Oberthema für verallgemeinerte Ableitungen|Oberthema für verallgemeinerte Ableitungen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Spektralfunktion der verallgemeinerten Ableitung
  - Beweis für 1.2.35
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Nach [[202510252210 - Fouriertransformierte der Ableitung|Lemma 1.2.13]] gilt
$$
\widehat{f'}(\omega) = i\omega \hat{f}(\omega) - \sum_{k=1}^{N} (f(t_k^+) - f(t_k^-))e^{-i\omega t_k} \quad \text{für alle } \omega \in \mathbb{R}.
$$
Andererseits hat die (verallgemeinerte Funktion) $t \to \delta(t-t_j)$ die Spektraldichte $\omega \to e^{-i\omega t_j}$, siehe [[202510251910 - Eigenschaften der Fouriertransformation|Lemma 1.2.11]] (iv) und [[202510262310 - Distribution der konstanten Funktion|Gleichung 1.55]]. Die Behauptung folgt daraus mittels der Linearität der Fouriertransformation.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=49]]


