---
"created date:": 22.10.2025 20:25
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Differenzierbarkeit]]"
  - "[[202510271310 - Cauchy-Riemann Differentialgleichungen|Cauchy-Riemann Differentialgleichungen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis zu Holomorphe Funktion mit konstantem Betrag
  - Beweis 2.2.15
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Die Aussage ist trivial für $C = 0$.
Sei $C \ne 0$. Dann gilt offenbar
$$ f(z)\overline{f(z)} = |C|^2 = C^2 \ne 0 $$
also ist
$$ z \mapsto \overline{f(z)} = C^2 / f(z) \quad (2.6) $$
auf $U$ holomorph. Wir schreiben wieder $f(x+iy) = u(x, y) + iv(x, y)$. Dann ist die Funktion (2.6) durch
$$ (x + iy) \mapsto u(x, y) - iv(x, y) $$
gegeben und die Cauchy-Riemann-Gleichungen nehmen für diese Funktion die Form
$$ \frac{\partial u}{\partial x} = \frac{\partial(-v)}{\partial y} = -\frac{\partial v}{\partial y} \quad \text{sowie} \quad \frac{\partial u}{\partial y} = -\frac{\partial(-v)}{\partial x} = \frac{\partial v}{\partial x} $$
an. Zusammen mit den Cauchy-Riemann-Gleichungen für die Funktion $f$, d.h.
$$ \frac{\partial u}{\partial x} = \frac{\partial v}{\partial y} \quad \text{sowie} \quad \frac{\partial u}{\partial y} = -\frac{\partial v}{\partial x} $$
erhalten wir
$$ \frac{\partial u}{\partial x} = \frac{\partial u}{\partial y} = \frac{\partial v}{\partial x} = \frac{\partial v}{\partial y} = 0, $$
also $f'(z) = 0$ für alle $z \in U$. Damit folgt die Behauptung mit Lemma 2.2.14.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=72]]


