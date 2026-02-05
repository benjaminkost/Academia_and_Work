---
"created date:": 20.10.2025 09:42
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[202510201010 - Periodisches Faltungsprodukt|Das periodische Faltungsprodukt oder die Faltung]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - vl-3
  - baby
aliases:
  - Beispiel für Faltung als gleitender Mittelwert
  - Beispiel 1.1.46
parent:
siblings:
child:
mathematical statement: "[[202510201010 - Periodisches Faltungsprodukt|Das periodische Faltungsprodukt]]"
---
# Beispiel
Sei $f : \mathbb{R} \to \mathbb{C}$ T-periodisch. Sei $a \in (0, T)$ und $g : \mathbb{R} \to \mathbb{C}$ die T-periodisch fortgesetzte Funktion:
$$
g(t) := 
\begin{cases} 
1/a & \text{für } t \in [0, a) \\
0 & \text{für } t \in [a, T) 
\end{cases}
$$
Dann gilt:
$$
(f * g)(t) = \frac{1}{T} \int_{0}^{a} \frac{1}{a} f(t - s)ds = \frac{1}{T} \cdot \frac{1}{a} \int_{t-a}^{t} f(\tau)d\tau \quad \text{für alle } t \in \mathbb{R}
$$
Also ist (bis auf den Faktor $1/T$) der Wert $(f * g)(t)$ der Faltung bei $t$ gleich dem Mittel der Funktion $f$ im Intervall $(t - a, t)$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=20]]




