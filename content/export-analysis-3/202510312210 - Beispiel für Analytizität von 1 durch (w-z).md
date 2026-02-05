---
"created date:": 22.10.2025 20:31
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510271210 - Potenzreihen in C|Potenzreihen in C]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Beispiel für Analytizität von 1 durch (w-z)
  - Beispiel 2.3.5
parent:
siblings:
child:
---
# Beispiel
Mit anderen Worten: jede analytische Funktion $f$ lässt sich lokal in eine Potenzreihe entwickeln.
Für jedes $w \in \mathbb{C}$ ist die Funktion $f(z) = 1/(w - z)$ analytisch in $\mathbb{C}\setminus\{w\}$.

**Beweis:** Sei $z_0 \in \mathbb{C}\setminus\{w\}$ beliebig. Dann gilt
$$
\begin{align*}
f(z) = \frac{1}{w - z} &= \frac{1}{w - z_0 - (z - z_0)} \\
&= \frac{1}{w - z_0} \cdot \frac{1}{1 - \frac{z-z_0}{w-z_0}} \\
&= \frac{1}{w - z_0} \cdot \sum_{k=0}^{\infty} \left(\frac{z - z_0}{w - z_0}\right)^k = \sum_{k=0}^{\infty} \frac{(z - z_0)^k}{(w - z_0)^{k+1}}.
\end{align*}
$$
Diese Potenzreihe konvergiert für
$$ \left|\frac{z - z_0}{w - z_0}\right| < 1, $$
also alle $z \in B_{|w-z_0|}(z_0)$. Weil $z_0 \in \mathbb{C}\setminus\{w\}$ beliebig war, folgt die Behauptung.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=74]]



