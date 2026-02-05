---
"created date:": 29.10.2025 22:41
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Cauchy Integralformel]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beispiele
aliases:
  - Anwendung der Cauchy-Integralformel
  - Beispiel 2.7.5
parent:
siblings:
child:
---
# Beispiel
Als Anwendung der Cauchy-Integralformel berechnen wir das Integral
$$\oint_{|z|=4} \frac{e^z}{z^2 + 3z} dz .$$
Wir führen erst eine Partialbruchzerlegung durch: Wir setzen
$$\frac{1}{z^2 + 3z} = \frac{a}{z} + \frac{b}{z+3}$$
an und erhalten durch Erweitern
$$a(z+3) + bz = 1$$
also durch Koeffizientenvergleich
$$a = \frac{1}{3}, \quad b = -a = -\frac{1}{3} .$$
Damit ist das betrachtete Integral gleich
$$\oint_{|z|=4} \frac{e^z}{z^2 + 3z} dz = \frac{1}{3} \oint_{|z|=4} \frac{e^z}{z} dz - \frac{1}{3} \oint_{|z|=4} \frac{e^z}{z+3} dz \\= \frac{1}{3} 2\pi i e^0 - \frac{1}{3} 2\pi i e^{-3} = \frac{2\pi i}{3} (1 - e^{-3})$$
Hier haben wir verwendet, dass mit $\zeta = 0$, $r=4$ und der Funktion $z \mapsto e^z$, bzw. mit $\zeta = -3$, $r=4$ und $z \mapsto e^z$ die Voraussetzungen der Cauchy-Integralformel erfüllt sind.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=85]]


