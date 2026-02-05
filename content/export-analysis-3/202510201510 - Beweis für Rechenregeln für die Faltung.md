---
"created date:": 20.10.2025 09:44
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-3
  - baby
aliases:
  - Beweis für Rechenregeln für die Faltung
  - Beweis 1.1.47
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Diese [[202510201410 - Lemma für Rechenregeln für die Faltung|Lemma für Rechenregeln für die Faltung]] folgen aus elementaren Rechenregeln der Integration. Exemplarisch zeigen wir (iii): für jedes $t \in \mathbb{R}$ gilt mit der Substitution $\tau = t - s$ und Bemerkung 1.1.11
$$
\begin{align*}
(f * g)(t) &= \frac{1}{T} \int_{0}^{T} f(t - s)g(s)ds \\
&= -\frac{1}{T} \int_{t}^{t-T} f(\tau)g(t - \tau)d\tau \\
&= \frac{1}{T} \int_{t-T}^{t} f(\tau)g(t - \tau)d\tau \\
&= \frac{1}{T} \int_{0}^{T} f(\tau)g(t - \tau)d\tau = (g * f)(t).
\end{align*}
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=21]]



