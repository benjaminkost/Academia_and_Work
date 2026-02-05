---
"created date:": 30.10.2025 00:14
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Residuentheorie]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beispiele
aliases:
  - Beispiel zu Berechnung eines Residuums auf zwei Arten
  - Beispiel 2.11.8
parent:
siblings:
child:
---
# Beispiel
Die Funktion $f: \mathbb{C}^\times \to \mathbb{C}$ definiert durch
$$f(z) = \frac{\sin(z)^2}{z^3}$$
hat bei $z_0=0$ einen einfachen Pol. Daher gilt
$$\text{Res}_0(f) = \lim_{z\to 0} \frac{\sin(z)^2}{z^2} = \left(\lim_{z\to 0} \frac{\sin(z)}{z}\right)^2.$$
Wegen $\lim_{z\to 0} \frac{\sin(z)}{z} = \lim_{z\to 0} \frac{\sin(z)-\sin(0)}{z} = \sin'(0) = \cos(0) = 1$ erhalten wir
$$\text{Res}_0(f)=1.$$
Alternativ könnte man direkter die Taylor-Reihe von $\sin(z)$ verwenden, um $\text{Res}_0(f) = c_{-1}$ zu berechnen: Wir haben
$$\sin(z) = z - \frac{z^3}{3!} + O(z^5)$$
und daher
$$\sin(z)^2 = z^2 - \frac{z^4}{3} + O(z^6).$$
Dies liefert
$$f(z) = \frac{\sin(z)^2}{z^3} = z^{-1} - \frac{z}{3} + O(z^3)$$
also $\text{Res}_0(f) = c_{-1} = 1$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=99]]


