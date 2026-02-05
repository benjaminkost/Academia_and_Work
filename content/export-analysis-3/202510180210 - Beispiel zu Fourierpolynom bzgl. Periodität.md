---
"created date:": 17.10.2025 16:12
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
tags:
  - 3-Semester
  - 1-Semester
  - grundlagen
  - beispiele
  - baby
aliases:
  - Beispiel zu Fourierpolynom bzgl. Periodität
  - 1.1.2
parent:
siblings:
child:
---
# Beispiel
Die Funktionen $\cos, \sin : \mathbb{R} \to \mathbb{R}$ sind $2\pi$-periodisch.

Seien $k \in \mathbb{Z}\setminus\{0\}$ und $\omega > 0$. Mit
$$e^{ik\omega t} = \cos(k\omega t) + i \sin(k\omega t) \quad (1.1)$$
folgt, dass die Funktion $t \mapsto e^{ik\omega t}$ periodisch ist mit Periode $T_k = \frac{T}{|k|}$, wobei $T = \frac{2\pi}{\omega}$.

Die zugehörige Kreisfrequenz ist $\omega_k = |k|\omega$.

| | Periode | Kreisfrequenz $\omega_k$ | Frequenz in Hertz |
| :--- | :--- | :--- | :--- |
| $k \in \{\pm 1\}$ | $T$ | $\omega$ | $1/T$ |
| $k \in \{\pm 2\}$ | $T/2$ | $2\omega$ | $2/T$ |
| ... | ... | ... | ... |

Hier bezeichnet die Frequenz (in Hertz) die Anzahl der Schwingungen pro Sekunde.[^1]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=5]]




