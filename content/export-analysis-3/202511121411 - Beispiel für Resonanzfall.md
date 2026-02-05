---
"created date:": 31.10.2025 09:23
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
  - "[[202510201810 - Lineare zeitinvariante Übertragungssysteme|Lineare zeitinvariante Übertragungssysteme]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beispiele
aliases:
  - Beispiel für Resonanzfall
  - Gleichung 1.28
  - Gleichung 1.29
parent:
siblings:
child:
---
# Beispiel
Das Beispiel betrachtet die Differentialgleichung:
$L[y](t) := y'(t) = x(t) \quad (1.28)$

Die allgemeine Lösung ist:
$$y(t) = K + \int_0^t x(s)ds, \space wobei \space  K \in \mathbb{C} \space  eine \space beliebige \space  Konstante \space  ist. \quad (1.29)$$
Das charakteristische Polynom von $L$ ist gleich $P(z) = z$, also ist 
 $P(ik\omega) = 0$ für $k =0$ 
 und es liegt der Resonanzfall vor.

Sei $x : \mathbb{R} \to \mathbb{C}$ $T$-periodisch und 
$$\frac{1}{T} \int_0^T x(s)ds \neq 0$$Dann ist $y$ gegeben durch (Gleichung 1.29) eine Lösung von (Gleichung 1.28), die stetig aber nicht $T$-periodisch ist, denn $$y(T) = K + \int_0^T x(s)ds \neq K = y(0)$$Sei andererseits $x : \mathbb{R} \to \mathbb{C}$ $T$-periodisch mit $$\frac{1}{T} \int_0^T x(s)ds = 0$$Dann ist (1.29) für jedes $K \in \mathbb{C}$ eine $T$-periodische Funktion $y$, welche $L[y] = x$ erfüllt. Somit ist der Output $y$ nicht eindeutig durch den Input $x$ festgelegt.[^1]

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
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V7.pdf#page=8]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=25]]


