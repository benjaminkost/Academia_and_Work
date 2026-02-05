---
"created date:": 10.11.2025 08:33
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
  - "[[202510201010 - Periodisches Faltungsprodukt|Das periodische Faltungsprodukt oder die Faltung]]"
  - "[[In own Words]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-3
  - baby
aliases:
  - in eigenen Worten periodusches Faltungsprodukt
topic: "[[202510201010 - Periodisches Faltungsprodukt|Periodisches Faltungsprodukt]]"
correct: false
---
Das periodische Faltungsprodukt definiert neben den Grundrechenarten (Plus, Minus, Mal, Durch) eine weitere Operation, die man mit zwei Funktionen durchführen kann.
# Metapher
Wenn man berechnen möchte wie viel Rauch in einer bestimmten Minute an Silvester in der Luft ist und man hat das geben:
- $f(t)$ wie viele Raketen über den Abend (die Zeit ) hinweg gezündet werden -> ist eine Gerade mit einer negativen Steigung 
- $R(t)$ als Rauch den eine Rakete über eine Zeit ($t$) emittiert -> ist eine exponentiell fallende Funtkion
### Lösung
1. Dann erhält man beispielsweise für die nullte Minute:
- das 10 Raketen gezündet werden
- somit haben wir in der nullten Minute: $10 \cdot S(0)$ -> da Wert von Rauch in der nullten Minute 10 mal erzeugt wird
2. Dann in der ersten Minute:
- 5 Raketen werden gezündet
- somit haben wir in der nullten Minute: $f(0)\cdot S(1)+f(1)\cdot S(0)=10 \cdot S(1)+5 \cdot S(0)$
-> Also haben wir den Rauch der immer noch von den 10 Raketen aus Minute null emittiert wird, aber entsprechend für die Menge an Rauch nach einer Minute PLUS den Rauch den die neuen 5 Raketen in der ersten Minute produzieren.

Somit können wir aus diesen diskreten Minuten ein Formel definieren, die uns zeigt wie viel Rauch in einer entsprechenden Minute in der Luft:
$$
\begin{align}
g(n)=\sum_{k=0}^nf(k)\cdot S(n-k)
\end{align}
$$
[^1]
# Referenz
## Verknüpfung
- 
## Quellen

[^1]: https://www.youtube.com/watch?v=QmcoPYUfbJ8&t



