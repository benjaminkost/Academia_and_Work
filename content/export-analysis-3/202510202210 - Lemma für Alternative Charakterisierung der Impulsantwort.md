---
"created date:": 20.10.2025 09:55
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
  - Lemma für Alternative Charakterisierung der Impulsantwort
  - Lemma 1.1.52
  - Gleichung 1.25
  - Gleichung 1.26
  - Gleichung 1.24
parent:
siblings:
child:
proof: "[[202510202310 - Beweis für Alternative Charakterisierung der Impulsantwort]]"
---
# Lemma
Betrachte das LTI-System aus [[202510201910 - Lemma für Lineare zeitinvariante Übertragungssysteme-Systeme und Differentialgleichungen|Gleichung 1.23]]. 
und sei 
$$P (ikω̸) \not= 0 \space \text{für alle} \space k ∈ Z. \quad(1.24)$$

Angenommen, $h : \mathbb{R} \to \mathbb{C}$ ist T-periodisch und auf $(0, T)$ glatt und es gilt:

(i) $L[h](t) = 0$ für alle $t \in (0, T)$ (1.25)

(ii) Sprungbedingungen bei $t=0$:
$h^{(s)}(0^+) = h^{(s)}(T^−)$ für $s = 0, \dots, m-2$ und
$h^{(m-1)}(0^+) = h^{(m-1)}(T^−) + T/a_m$.
(1.26)

Dann ist $h = h_T$ die [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Impulsantwort]] des LTI-Systems.[^1]


# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510210110 - Resonanz für Alternative Charakterisierung der Impulsantwort]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=23]]



