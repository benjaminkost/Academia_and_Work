---
"created date:": 20.10.2025 09:53
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
  - "[[202510201810 - Lineare zeitinvariante Übertragungssysteme|Lineare zeitinvariante Übertragungssysteme]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-3
  - baby
aliases:
  - Beweis für Lineare zeitinvariante Übertragungssysteme und Differentialgleichungen
  - Beweis 1.1.50
parent:
siblings:
child:
mathematical statement: "[[202510201910 - Lemma für Lineare zeitinvariante Übertragungssysteme-Systeme und Differentialgleichungen|Lemma für LTI-Systeme und Differentialgleichungen]]"
---
# Beweis
Wir lösen das Problem zunächst für $x(t) = e^{ik\omega t}$ mit $k \in \mathbb{Z}$. Der Ansatz $y(t) = d_k e^{ik\omega t}$ in ([[202510201910 - Lemma für Lineare zeitinvariante Übertragungssysteme-Systeme und Differentialgleichungen|Gleichung 1.23]]) eingesetzt liefert 
$L[d_k e^{ik\omega t}] = d_k P(ik\omega)e^{ik\omega t} = e^{ik\omega t}$. Dies impliziert $P(ik\omega)d_k = 1$, also $d_k = 1/P(ik\omega)$.
Wegen der Linearität von $L$ ist für einen allgemeinen Input $x(t) = \sum_{k=-n}^n c_k e^{ik\omega t}$ der Output $y(t) = \sum_{k=-n}^n d_k c_k e^{ik\omega t}$.
Im Grenzwert $n \to \infty$ ist also die Funktion $y(t)$ mit Fourierspektrum $\{c_k d_k\}_{k\in\mathbb{Z}}$ der Output zugehörig zum Input $x(t)$. Nach dem Faltungstheorem ([[202510201610 - Lemma für Glättungseigenschaft der Faltung|Lemma 1.1.49]]) ist $y = h_T * x$ für die T-periodische [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Impulsantwort]] $h_T(t) = \sum_{k \in \mathbb{Z}} d_k e^{ik\omega t}$.[^1]


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



