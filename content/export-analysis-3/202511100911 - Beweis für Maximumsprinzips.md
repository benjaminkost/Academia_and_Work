---
"created date:": 29.10.2025 23:22
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301010 - Weitere Anwendungen der Cauchy-Integralformel|Weitere Anwendungen der Cauchy-Integralformel]]"
  - "[[202511020411 - Identitätssatz|Identitätssatz]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis für Maximumsprinzips
  - Gleichung 2.20
parent:
siblings:
child:
mathematical statement: "[[202511100811 - Maximumsprinzip|Maximumsprinzip]]"
---
# Beweis
Angenommen, $z_0 \in U$ sei ein lokales Maximum der Funktion $z \mapsto |f(z)|$. Dann gibt es ein $r > 0$, so dass
$$|f(z)| \le |f(z_0)| \quad \text{für alle } z \in B_r(z_0) \subset U. \quad (2.20)$$
Damit folgt für alle $\rho \in (0, r)$
$$|f(z_0)| = \left| \frac{1}{2\pi i} \oint_{|\xi-z_0|=\rho} \frac{f(\xi)}{\xi - z_0} d\xi \right| \le \frac{1}{2\pi} \int_0^{2\pi} |f(z_0 + \rho e^{it})| dt \le |f(z_0)|.$$
Wegen (siehe (2.20)) $|f(z_0 + \rho e^{it})| \le |f(z_0)|$ kann dies nur gelten, falls $|f(z)| = |f(z_0)|$ für alle $z \in U$ mit $|z-z_0| = \rho$. Weil $\rho \in (0, r)$ beliebig war, folgt
$$|f(z)| = |f(z_0)| \quad \text{für alle } z \in B_r(z_0).$$
Damit ist $|f(z)|$ konstant auf $B_r(z_0)$. Nach [[202510311610 - Holomorphe Funktion mit konstantem Betrag|Lemma 2.2.15]] ist $f$ konstant auf $B_r(z_0)$. Der Identitätssatz liefert damit, dass $f$ auf $U$ konstant ist.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=90]]


