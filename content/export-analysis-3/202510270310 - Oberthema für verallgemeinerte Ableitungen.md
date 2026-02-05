---
"created date:": 22.10.2025 14:33
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270310 - Oberthema für verallgemeinerte Ableitungen|Verallgemeinerte Ableitungen]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Oberthema für verallgemeinerte Ableitungen
parent:
siblings:
child:
---
# Definition
Die Heaviside-Funktion $\theta$ ist in $0$ nicht differenzierbar (nicht einmal stetig). Mittels der Theorie der Distributionen lässt sich trotzdem eine verallgemeinerte Ableitung $D\theta$ von $\theta$ definieren. Wir skizzieren dies kurz.

Die (verallgemeinerte) Ableitung $Dg$ einer Distribution $g$ wird definiert durch die Forderung:
$Dg[\phi] := -g[\phi']$
für alle unendlich oft stetig differenzierbaren Funktionen $\phi : \mathbb{R} \to \mathbb{C}$, die, ebenso wie ihre Ableitungen, für $|t| \to \infty$ hinreichend schnell gegen $0$ streben (wir gehen nicht ins Detail; wenn es $M > 0$ gibt, so dass $\phi$ außerhalb von $[-M, M]$ gleich Null ist, dann gilt letzteres jedenfalls).

In Integralschreibweise:
$$
\int_{-\infty}^{\infty} \phi(t)Dg(t) dt := - \int_{-\infty}^{\infty} \phi'(t)g(t) dt \quad (1.58)
$$
für alle "Testfunktionen" $\phi$ wie oben angegeben.

Diese Definition von $Dg$ ergibt sich aus der partiellen Integration: Ist $f \in C^1(\mathbb{R})$, dann gilt wegen $\lim_{|t|\to\infty} \phi(t) = 0$:
$$
\int_{-\infty}^{\infty} \phi(t)f'(t) dt = - \int_{-\infty}^{\infty} \phi'(t)f(t) dt
$$
d.h. für $Dg$ wird der gleiche Zusammenhang mit $g$ gefordert, wie er sich für $f'$ zu $f$ mittels partieller Integration ergibt.

Wir wenden dies nun auf $\theta$ an, indem wir $\theta[\phi] = \int_{-\infty}^{\infty} \phi(t)\theta(t) dt$ als Distribution auffassen (das geht für jede Funktion, für die das rechtsstehende Integral für alle $\phi$ wohldefiniert ist) und die Distributionsableitung berechnen:
$$
D\theta[\phi] = \int_{-\infty}^{\infty} \phi(t)D\theta(t) dt := - \int_{-\infty}^{\infty} \phi'(t)\theta(t) dt = - \int_{0}^{\infty} \phi'(t) dt = -[\phi(t)]_{0}^{\infty} = \phi(0) = \delta[\phi]
$$
für alle Testfunktionen $\phi$ wie oben angegeben.

Damit folgt:
$$
D\theta = \delta
$$
Dieses Ergebnis für die Sprungfunktion verallgemeinernd und konsistent mit (1.58) können wir folgendes Konzept definieren.
[^1]

# Oberthema
```dataview
LIST
WHERE contains(mytags, [[]])
SORT file.name ASC
```

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=48]]



