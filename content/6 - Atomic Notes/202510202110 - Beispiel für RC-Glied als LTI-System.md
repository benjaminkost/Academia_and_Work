---
"created date:": 20.10.2025 09:54
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[202510201810 - Lineare zeitinvariante Übertragungssysteme]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - vl-3
  - baby
aliases:
  - Beispiel für RC-Glied als LTI-System
  - Beispiel 1.1.51
parent:
siblings:
child:
---
# Beispiel
Die Ausgangsspannung $y(t)$ am Kondensator eines RC-Gliedes mit Eingangsspannung $x(t)$ erfüllt die DGL $$RCy'(t) + y(t) = x(t)$$
Betrachten wir den Fall $RC = 1/4$ und $2\pi$-periodischer Signale. Dann ist $$P(z) = \frac{z}{4} + 1$$ und damit der [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Frequenzgang]] (mit $\omega = 1$):
$$
d_k = \frac{1}{P(ik)} = \frac{4}{4 + ik} \quad \text{mit } k \in \mathbb{Z}.
$$
Die entsprechende [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Impulsantwort]] ist
$$
h_T(t) = \sum_{k \in \mathbb{Z}} \frac{4}{4+ik} e^{ikt}.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=23]]




