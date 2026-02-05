---
"created date:": 17.10.2025 15:17
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[eigenschaften von fourierreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Beweis für Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen
parent:
siblings:
child:
---
# Beweis
Wir integrieren über Teilintervalle ${(t_j, t_{j+1})}$, d.h. (mit der Konvention ${t_{N+1} = t_1 + T}$)
${d_k = \frac{1}{T}\int_0^T f'(t)e^{-ik\omega t}dt = \sum_{j=1}^N \frac{1}{T}\int_{t_j}^{t_{j+1}} f'(t)e^{-ik\omega t}dt, \quad (1.17)}$
siehe Bemerkung 1.1.11. Jeden Summanden in diesem Ausdruck behandeln wir durch partielle Integration: wir haben
${\frac{1}{T} \int_{t_j}^{t_{j+1}} f'(t)e^{-ik\omega t}dt = \frac{1}{T} \left[ f(t)e^{-ik\omega t} \right]_{t=t_j^+}^{t_{j+1}^-} + \frac{ik\omega}{T} \int_{t_j}^{t_{j+1}} f(t)e^{-ik\omega t}dt}$
für jedes ${j=1, \ldots, N}$. Einsetzen in (1.17) liefert
$${
\begin{aligned}
d_k &= \frac{1}{T} \sum_{j=1}^N \left[ f(t)e^{-ik\omega t} \right]_{t=t_j^+}^{t_{j+1}^-} + \frac{ik\omega}{T} \sum_{j=1}^N \int_{t_j}^{t_{j+1}} f(t)e^{-ik\omega t}dt \\
&= \frac{1}{T} \sum_{j=1}^N \left[ f(t)e^{-ik\omega t} \right]_{t=t_j^+}^{t_{j+1}^-} + ik\omega c_k
\end{aligned}
}$$
für jedes ${k \in \mathbb{Z}}$. Die Behauptung folgt aus
$${
\begin{aligned}
\frac{1}{T} \sum_{j=1}^N \left[ f(t)e^{-ik\omega t} \right]_{t=t_j^+}^{t_{j+1}^-} &= \frac{1}{T} \sum_{j=1}^N \left( f(t_{j+1}^-)e^{-ik\omega t_{j+1}} - f(t_j^+)e^{-ik\omega t_j} \right) \\
&= \frac{1}{T} \left( f(t_{N+1}^-)e^{-ik\omega t_{N+1}} - f(t_1^-)e^{-ik\omega t_1} \right) + \frac{1}{T}\sum_{j=1}^N \left(f(t_j^-) - f(t_j^+)\right)e^{-ik\omega t_j} \\
&= -\frac{1}{T} \sum_{j=1}^N \Delta_j e^{-ik\omega t_j}.
\end{aligned}
}$$
Hier haben wir ${t_{N+1} = t_1 + T}$ und die Periodizität von ${f}$ verwendet.[^1]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=18]]



