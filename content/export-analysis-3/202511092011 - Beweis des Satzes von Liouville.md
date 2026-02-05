---
"created date:": 29.10.2025 22:55
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
  - Beweis des Satzes von Liouville
  - Beweis 2.7.9
parent:
siblings:
child:
mathematical statement: "[[202511091911 - Satz von Liouville|Satz von Liouville]]"
---
# Beweis
Angenommen, es gelte $|f(z)| \le C$ für alle $z \in \mathbb{C}$. Dann folgt mit der Cauchy-Integralformel für Ableitungen und der Standardabschätzung, dass für $z \in \mathbb{C}$ und $r > 0$ beliebig gilt
$$|f'(z)| = \left| \frac{1}{2\pi i} \oint_{|\zeta-z|=r} \frac{f(\zeta)}{(\zeta-z)^2} d\zeta \right| \le \frac{1}{2\pi} 2\pi r \frac{C}{r^2} = \frac{C}{r} .$$
Daraus folgt
$$|f'(z)| \le \frac{C}{r} \to 0 \quad \text{für } r \to \infty,$$
also
$$f'(z) = 0 \quad \text{für alle } z \in \mathbb{C} .$$
Nach [[202510311410 - Konstanz bei verschwindender Ableitung|Lemma 2.2.14]] ist $f$ konstant.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=86]]


