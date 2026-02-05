---
"created date:": 22.10.2025 14:34
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270410 - Das Abtasttheorem|Das Abtasttheorem]]"
  - "[[satz]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Das Abtasttheorem
  - Gleichung 1.59
  - Gleichung 1.61
  - Gleichung 1.62
parent:
siblings:
child:
proof: "[[202510272310 - Beweis für Abtasttheorem]]"
---
# Einführung
Sei $\Delta t > 0$. Angenommen, von einer Funktion $f : \mathbb{R} \to \mathbb{C}$ seien nur die Abtastwerte 
$$f(k\Delta t)$ für $k \in \mathbb{Z}$$ 
(1.59) (mit $\Delta t \in \mathbb{R}$ fix) bekannt. Die Größe 
$$\omega_s := \frac{2\pi}{\Delta t}$$
[^2]
# Definition
Sei $f \in L^1(\mathbb{R})$ stetig, stückweise stetig differenzierbar und bandbegrenzt mit Schranke $\Omega \ge 0$. Sei $\omega_s = \frac{2\pi}{\Delta t} > 0$ eine Abtastfrequenz, die
$$
\omega_s > 2\Omega
$$
erfüllt. Dann gilt an jeder Stetigkeitsstelle $t$ von $f$
$$
f(t) = \sum_{k \in \mathbb{Z}} f(k\Delta t) \text{sinc} \left( \frac{\pi}{\Delta t}(t - k\Delta t) \right),
$$
wobei $\text{sinc}(x) = \sin(x)/x$ der sinus cardinalis ist. Insbesondere ist $f(t)$ eindeutig durch die Abtastwerte bestimmt.

![[Bildschirmfoto 2025-10-22 um 15.27.26.png|400]]
![[Bildschirmfoto 2025-10-22 um 15.27.38.png|400]]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=50]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=49]]



