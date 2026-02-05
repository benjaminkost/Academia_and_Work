---
"created date:": 17.10.2025 13:08
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[eigenschaften]]"
  - "[[eigenschaften von fourierreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Amplitudenmodulation von Fourierreihen
  - Verschiebung im Spektralbereich
parent:
siblings:
child:
---
# Definition
Seien ${f, g : \mathbb{R} \to \mathbb{C}}$ T-periodisch. Sei
${\{c_k\}_{k\in\mathbb{Z}}}$ das Fourierspektrum von ${f}$
${\{d_k\}_{k\in\mathbb{Z}}}$ das Fourierspektrum von ${g}$.
Seien ${\alpha, \beta \in \mathbb{C}}$ und ${a \in \mathbb{R}}$ beliebig. Dann gilt

(Verschiebung im Spektralbereich=Amplitudenmodulation) Sei ${n \in \mathbb{Z}}$ beliebig. Das Fourierspektrum der Funktion
${t \to e^{in\omega t} f(t)}$ ist ${\{c_{k-n}\}_{k\in\mathbb{Z}}}$.[^1] ^da26f5
# Beweis
Diese Eigenschaft folgt aus
$${
\frac{1}{T} \int_0^T (e^{in\omega t}f(t)) e^{-ik\omega t} dt = \frac{1}{T} \int_0^T f(t) e^{-i(k-n)\omega t} dt = c_{k-n} \quad \text{für alle } k \in \mathbb{Z}.
}$$
# Beispiele


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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=15]]



