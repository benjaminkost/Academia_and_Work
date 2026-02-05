---
"created date:": 22.10.2025 12:10
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[eigenschaften von fouriertransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Fouriertransformierte der Ableitung
  - Beweis 1.2.13
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Beweis. Wie im Beweis von Lemma 1.1.40 folgt dies durch partielle Integration. Seien $t_1 < \dots < t_N$ die Sprungstellen von $f$ und
$$ \Delta_j = f(t_j^+) - f(t_j^-). $$
Sei $f'$ die Ableitung (definiert nur außerhalb der Sprungstellen). Wir integrieren über Teilintervalle $(t_j, t_{j+1})$ mit der Konvention $t_0 = -\infty$ und $t_{N+1} = \infty$, d.h.
$$ \widehat{f'}(\omega) = \int_{-\infty}^{\infty} f'(t)e^{-i\omega t} = \sum_{j=0}^N \int_{t_j}^{t_{j+1}} f'(t)e^{-i\omega t}dt, \quad (1.42) $$
Jeden Summanden in diesem Ausdruck behandeln wir durch partielle Integration: Wir haben
$$ \int_{t_j}^{t_{j+1}} f'(t)e^{-i\omega t}dt = [f(t)e^{-i\omega t}]_{t=t_j^+}^{t_{j+1}^-} + i\omega \int_{t_j}^{t_{j+1}} f(t)e^{-i\omega t}dt $$
für jedes $j=0, \dots, N$. Einsetzen in (1.42) liefert
$$ \widehat{f'}(\omega) = \sum_{j=0}^N [f(t)e^{-i\omega t}]_{t=t_j^+}^{t_{j+1}^-} + i\omega \sum_{j=0}^N \int_{t_j}^{t_{j+1}} f(t)e^{-i\omega t}dt = \sum_{j=0}^N [f(t)e^{-i\omega t}]_{t=t_j^+}^{t_{j+1}^-} + i\omega \hat{f}(\omega) $$
für jedes $\omega \in \mathbb{R}$. Die Behauptung folgt aus diesem Ausdruck, weil
$$ \sum_{j=0}^N [f(t)e^{-i\omega t}]_{t=t_j^+}^{t_{j+1}^-} = \sum_{j=0}^N (f(t_{j+1}^-)e^{-i\omega t_{j+1}} - f(t_j^+)e^{-i\omega t_j}) $$
$$ = (f(t_{N+1}^-)e^{-i\omega t_{N+1}} - f(t_0^-)e^{-i\omega t_0}) + \sum_{j=1}^N (f(t_j^-) - f(t_j^+))e^{-i\omega t_j} = -\sum_{j=1}^N \Delta_j e^{-i\omega t_j}. $$
Hier haben wir benutzt, dass $\lim_{t\to-\infty} f(t) = \lim_{t\to\infty} f(t) = 0$ für $f \in L^1(\mathbb{R})$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=38]]


