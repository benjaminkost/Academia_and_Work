---
"created date:": 20.10.2025 09:39
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
  - "[[202510201010 - Periodisches Faltungsprodukt|Das periodische Faltungsprodukt oder die Faltung]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-3
  - baby
aliases:
  - Definition 1.1.43
  - Faltung
  - Periodisches Faltungsprodukt
parent:
siblings:
child:
in own words: "[[202511151311 - in eigenen Worten periodisches Faltungsprodukt]]"
---
# Definition
Seien $f, g : \mathbb{R} \to \mathbb{C}$ $T$-[[Periodische Funktion|periodisch]] und [[202511080211 - Stückweise Stetigkeit|stückweise stetig]]. Dann ist die **Faltung** von $f$ und $g$ die Funktion $f * g : \mathbb{R} \to \mathbb{C}$ definiert durch:
$$
(f * g)(t) := \frac{1}{T} \int_{0}^{T} f(t - s)g(s)ds
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
- [[202510201110 - Bemerkung Nicht-periodische Faltung]]
- [[202510201210 - Beispiel zur Faltung mit konstanten und harmonischen Funktionen]]
- [[202510201310 - Beispiel für Faltung als gleitender Mittelwert]]
- [[202510201410 - Lemma für Rechenregeln für die Faltung]]
- [[202510201610 - Lemma für Glättungseigenschaft der Faltung]]
## Quellen
- https://www.youtube.com/watch?v=AgKQQtEc9dk
- https://www.youtube.com/watch?v=QmcoPYUfbJ8&t
- https://www.youtube.com/watch?v=IaSGqQa5O-M
- https://www.youtube.com/watch?v=PZpwT7TCLpA

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=20]]



