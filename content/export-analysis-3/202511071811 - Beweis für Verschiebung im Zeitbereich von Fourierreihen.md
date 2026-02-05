---
"created date:": 24.10.2025 08:04
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Verschiebung im Zeitbereich von Fourierreihen
parent:
siblings:
child:
mathematical statement: "[[202510171810 - Verschiebung im Zeitbereich von Fourierreihen|Verschiebung von Fourierreihen]]"
---
# Beweis
Für diese Eigenschaft verwenden wir ${e^{-ik\omega(\tau-a)} = e^{-ik\omega\tau}e^{ik\omega a}}$, also mit der Substitution ${\tau = t + a}$
$${
\begin{aligned}
\frac{1}{T} \int_0^T f(t+a)e^{-ik\omega t} dt &= \frac{1}{T} \int_a^{T+a} f(\tau)e^{-ik\omega(\tau-a)} d\tau \\
&= e^{ik\omega a} \frac{1}{T} \int_0^T f(\tau)e^{-ik\omega\tau} d\tau \\
&= e^{ik\omega a} c_k \quad \text{für alle } k \in \mathbb{Z}.
\end{aligned}
}$$
[^1]
# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[Komplexe Fourierkoeffizienten]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=15]]


