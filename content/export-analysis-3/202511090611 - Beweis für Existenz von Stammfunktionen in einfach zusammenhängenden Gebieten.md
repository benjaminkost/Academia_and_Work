---
"created date:": 29.10.2025 22:27
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202511021711 - Integralsatz von Cauchy|Integralsatz von Cauchy]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis für Existenz von Stammfunktionen in einfach zusammenhängenden Gebieten
  - Beweis 2.6.6
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Wir zeigen zunächst, dass der Ausdruck ([[202511090511 - Existenz von Stammfunktionen in einfach zusammenhängenden Gebieten|Gleichung 2.11]]) wohldefiniert ist, d.h. nicht von der gewählten Kurve $\gamma$ abhängt: sind $\gamma_1, \gamma_2 : [a, b] \to U$ zwei Kurven mit
$$\begin{aligned}\gamma_j(a) &= z_0 \\\gamma_j(b) &= z \quad \text{für } j = 1, 2 ,\end{aligned}$$
dann gilt wegen dem Integralsatz [[202511021711 - Integralsatz von Cauchy|Theorem 2.6.1]] von Cauchy
$$\int_{\gamma_1} f(\zeta)d\zeta - \int_{\gamma_2} f(\zeta)d\zeta = \int_\eta f(\zeta)d\zeta = 0 ,$$
wobei $\eta$ die geschlossene Kurve ist, die man durch Durchlaufen von $\gamma_1$ und darauffolgendendem Durchlaufen von $\gamma_2^*$ (also $\gamma_2$ im umgekehrten Sinne) erhält. Somit ist der Wert $F(z)$ unabhängig von der Wahl von $\gamma$.
Es bleibt zu prüfen, dass $F$ eine Stammfunktion von $f$ ist. Sei dazu $z \in U$. Weil $U$ offen ist, verläuft die Kurve
$$\gamma(t) = z + th \quad \text{für } t \in [0, 1]$$
für hinreichende kleine $h$ vollständig in $U$ (siehe [[202511011711 - Bemerkung zur Notation für Liniensegmente|Bemerkung 2.5.5]]). Es folgt⁹, dass
$$\begin{aligned}F(z+h) - F(z) &= \int_{[z_0, z+h]} f(\zeta)d\zeta - \int_{[z_0, z]} f(\zeta)d\zeta = \int_{[z_0, z]} f(\zeta)d\zeta + \int_{[z, z+h]} f(\zeta)d\zeta - \int_{[z_0, z]} f(\zeta)d\zeta \\&= \int_{[z, z+h]} f(\zeta)d\zeta = \int_0^1 f(z+th)hdt\end{aligned}$$
Damit erhalten wir
$$\frac{F(z+h) - F(z)}{h} = \int_0^1 f(z+th)dt \to f(z) \quad (h \to 0)$$
was zeigt, dass $F$ in $z$ komplex differenzierbar mit Ableitung $F'(z) = f(z)$ ist.
⁹Hier nehmen wir zur Einfachheit an, dass $[z_0, z+h] \subset U$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=82]]


