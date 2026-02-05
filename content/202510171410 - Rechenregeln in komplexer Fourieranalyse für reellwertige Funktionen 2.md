---
"created date:": 17.10.2025 12:45
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[reelle fourieranalyse]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Rechenregeln in komplexer Fourieranalyse für reellwertige Funktionen
parent:
siblings:
child:
---
# Definition
Betrachten wir reellwertige Funktionen, vereinfachen sich die Ausdrücke wie folgt.

**Lemma 1.1.26.** Sei ${f : \mathbb{R} \to \mathbb{R}}$ T-periodisch. Dann gilt
${c_{-k} = \overline{c_k} \quad \text{für jedes } k \in \mathbb{Z} \quad (1.12)}$
und
$${
\begin{aligned}
a_0 &= 2 \text{Re}(c_0) = 2c_0 \quad \text{und} \\
a_k &= 2 \text{Re}(c_k) \\
b_k &= -2 \text{Im}(c_k)
\end{aligned}
}$$
für jedes ${k \in \mathbb{N}}$.

# Beweis
Nach Definition gilt
$${
c_{-k} = \frac{1}{T} \int_0^T f(t)e^{ik\omega t} dt = \overline{\frac{1}{T} \int_0^T f(t)e^{-ik\omega t} dt} = \overline{\frac{1}{T} \int_0^T \overline{f(t)e^{-ik\omega t}} dt} = \overline{c_k} \quad \text{für alle } k \in \mathbb{Z}.
}$$
Im zweiten Schritt haben wir benutzt, dass ${\overline{e^{ix}} = e^{-ix}}$ und dass ${\overline{f(t)} = f(t)}$ weil ${f}$ reellwertig ist. Dies zeigt (1.12).
Aus (1.12) folgt insbesondere dass ${c_0 = \overline{c_0}}$, also ist ${c_0 \in \mathbb{R}}$. Mit (1.9) folgt damit ${a_0 = 2c_0 = 2\text{Re}(c_0)}$, wie behauptet. Für ${k \in \mathbb{N}}$ folgt außerdem (wieder mit (1.9) und (1.12))
${a_k = c_k + c_{-k} = c_k + \overline{c_k} = 2\text{Re}(c_k)}$
${b_k = i(c_k - c_{-k}) = i(c_k - \overline{c_k}) = -2\text{Im}(c_k)}$. ☐[^1]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=12]]



