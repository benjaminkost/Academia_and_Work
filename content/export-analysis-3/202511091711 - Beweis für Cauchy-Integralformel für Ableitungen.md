---
"created date:": 29.10.2025 22:51
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
  - beweise
aliases:
  - Beweis für Cauchy-Integralformel für Ableitungen
  - Beweis 2.7.7
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Offenbar gilt die Formel für $k = 0$: dies ist die Cauchy-Integralformel.
Wir gehen jetzt induktiv vor: angenommen, die Formel gelte für $k-1$. Da der Integrand bzgl. $z$ im Innern von $\partial B_r(z_0)$ komplex differenzierbar ist, darf man das Integral bzgl. $\zeta$ differenzieren (hier verwendet man eine komplexe Variante des Satzes über parameterabhängige Integrale). Damit erhält man
$$f^{(k)}(\zeta) = \frac{d}{d\zeta} f^{(k-1)}(\zeta) = \frac{(k-1)!}{2\pi i} \oint_{\partial B_r(z_0)} \frac{d}{d\zeta} \frac{f(z)}{(z-\zeta)^k} dz = \frac{(k-1)!}{2\pi i} \oint_{\partial B_r(z_0)} \frac{kf(z)}{(z-\zeta)^{k+1}} dz$$
also die Behauptung für $k$.
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


