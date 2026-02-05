---
"created date:": 22.10.2025 15:18
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270410 - Das Abtasttheorem|Das Abtasttheorem]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Abtastwerte eines harmonischen Signals
  - Beweis 1.2.37
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Unter Bedingung [[202510272010 - Abtastwerte eines harmonischen Signals|Gleichung 1.60]] existieren $m \in \mathbb{Z}\setminus\{0\}$ und eine $\tilde{\omega} \in [-\omega_s/2, \omega_s/2]$ so dass
$$
\omega = \tilde{\omega} + m\omega_s.
$$
Dann gilt für jedes $k \in \mathbb{Z}$
$$
f(k\Delta t) = e^{i\omega k\Delta t} = e^{i\tilde{\omega} k\Delta t} e^{ikm\omega_s \Delta t} = e^{i\tilde{\omega} k\Delta t} e^{2\pi ikm} = e^{i\tilde{\omega} k\Delta t}.
$$
Also sind die Abtastwerte für $f$ dieselben wie für die niederfrequentere Schwingung $t \to e^{i\tilde{\omega}t}$, und $f$ ist anhand der Abtastwerte nicht von letzteren unterscheidbar.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=49]]


