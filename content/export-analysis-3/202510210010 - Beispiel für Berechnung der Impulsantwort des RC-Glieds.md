---
"created date:": 20.10.2025 09:58
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[202510201810 - Lineare zeitinvariante Übertragungssysteme]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - vl-3
  - baby
aliases:
  - Beispiel für Berechnung der Impulsantwort des RC-Glieds
  - Beispiel 1.1.53
  - Gleichung 1.27
parent:
siblings:
child:
---
# Beispiel
Wir wenden [[202510202210 - Lemma für Alternative Charakterisierung der Impulsantwort|Lemma 1.1.52]] auf die in Beispiel [[202510202110 - Beispiel für RC-Glied als LTI-System|Beispiel 1.1.51]] betrachetete DGL $$\frac{1}{4}y'(t) + y(t) = x(t)$$ an.
Die Gleichung $1/4h' + h = 0$ hat die $2\pi$-periodisch fortgesetzte Lösung $h(t) = ce^{-4t}$ für $t \in (0, 2\pi)$. 
Offenbar ist h auf $(0, 2\pi)$ glatt. Weil $m = 1$ ist, müssen wir nur Bedingung (1.26) erfüllen (d.h. $c$ geeignet wählen). Es gilt $$h^{(0)}(0^+) = h(0^+) = c$$ $$h^{(0)}(2\pi^-) = h(2\pi^-) = ce^{-8\pi}$$Mit $T = 2\pi, m=1, a_1 = 1/4$ ist [[202510202210 - Lemma für Alternative Charakterisierung der Impulsantwort|Gleichung 1.26]] gegeben durch
$$c = ce^{-8\pi} + 8\pi$$, d.h. $c = 8\pi/(1 - e^{-8\pi})$. Die $2\pi$-periodische [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Impulsantwort]] ist:
$$
h(t) = \frac{8\pi}{1 - e^{-8\pi}}e^{-4t} \quad \text{für } t \in (0, 2\pi) \quad (1.27)
$$
Wir prüfen nach, dass das Resultat (1.27) mit dem im [[202510202110 - Beispiel für RC-Glied als LTI-System|Beispiel 1.1.51]] berechneten [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Frequenzgang]] übereinstimmt. Dazu berechnen wir den $k$-ten Fourierkoeffizient von $h$. Wir erhalten
$$
\begin{align}
\frac{c}{2\pi} \int_0^{2\pi} e^{-4t}e^{-ikt}dt = \frac{c}{2\pi} \int_0^{2\pi} e^{-(4+ik)t}dt  \\
= \frac{c}{2\pi} \left[ \frac{e^{-(4+ik)t}}{-(4+ik)} \right]_0^{2\pi}  \\
= \frac{c}{2\pi} \frac{e^{-8\pi} - e^0}{-(4+ik)} = \frac{c(1 - e^{-8\pi})}{2\pi(4+ik)} = \frac{4}{4+ik}
\end{align}
$$
, also ist der [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Frequenzgang]] tatsächlich $d_k = \frac{4}{4+ik}$.
[^1]

# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510210110 - Resonanz für Alternative Charakterisierung der Impulsantwort|Resonanz für Alternative Charakterisierung der Impulsantwort]]
## Quellen
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V7.pdf#page=1]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=24]]




