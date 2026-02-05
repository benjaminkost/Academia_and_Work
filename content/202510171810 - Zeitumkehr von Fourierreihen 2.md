---
"created date:": 17.10.2025 13:06
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[eigenschaften von fourierreihen]]"
  - "[[Lemma]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Zeitumkehr von Fourierreihen
  - Lemma 1.1.32(iii)
parent:
  - "[[202510171710 - Rechenregeln für das Fourierspektrum]]"
siblings:
child:
---
# Definition
Seien ${f, g : \mathbb{R} \to \mathbb{C}}$ T-periodisch. Sei
${\{c_k\}_{k\in\mathbb{Z}}}$ das Fourierspektrum von ${f}$
${\{d_k\}_{k\in\mathbb{Z}}}$ das Fourierspektrum von ${g}$.
Seien ${\alpha, \beta \in \mathbb{C}}$ und ${a \in \mathbb{R}}$ beliebig. Dann gilt

(Zeitumkehr) Das Fourierspektrum der Funktion
${t \to f(-t)}$ ist ${\{c_{-k}\}_{k\in\mathbb{Z}}}$.[^1] ^fb0038
# Beweis
Analog folgt aus [[202510171810 - Komplexkonjugation von Fourierreihen|Komplexkonjugation von Fourierreihen]] mittels der Variablensubstitution ${\tau = -t}$: wir haben
$${
\begin{aligned}
\frac{1}{T} \int_0^T f(-t)e^{-ik\omega t} dt &= -\frac{1}{T}\int_0^{-T} f(\tau)e^{ik\omega\tau} d\tau = \frac{1}{T}\int_{-T}^0 f(\tau)e^{ik\omega\tau} d\tau \\
&= \frac{1}{T} \int_0^T f(\tau)e^{ik\omega\tau} d\tau = c_{-k} \quad \text{für alle } k \in \mathbb{Z},
\end{aligned}
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
- [[202510171710 - Rechenregeln für das Fourierspektrum|Eigenschaften von Fourierreihen]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=14]]



