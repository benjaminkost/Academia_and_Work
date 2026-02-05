---
"created date:": 22.10.2025 19:56
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Differenzierbarkeit]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beiweis für Nicht-Differenzierbarkeit von f(z) = komplex konjugiert z
  - Beweis 2.2.3
parent:
siblings:
child:
mathematical statement: "[[202510301710 - Beispiel zu Nicht-Differenzierbarkeit von f(z) = komplex konjugiert z|Beispiel zu Nicht-Differenzierbarkeit von f(z) = komplex konjugiert z]]"
---
# Beweis
Für $z_0 \in \mathbb{C}$ beliebig betrachten wir die Folgen
$$
z_n = z_0 + 1/n \to z_0 \quad (n \to \infty) \\
y_n = z_0 + i/n \to z_0 \quad (n \to \infty).
$$
Dann gilt
$$
\lim_{n \to \infty} \frac{f(z_n) - f(z_0)}{z_n - z_0} = \lim_{n \to \infty} \frac{\overline{z_0 + 1/n} - \bar{z_0}}{z_0 + 1/n - z_0} = 1
$$
$$
\lim_{n \to \infty} \frac{f(y_n) - f(z_0)}{y_n - z_0} = \lim_{n \to \infty} \frac{\overline{z_0 + i/n} - \bar{z_0}}{z_0 + i/n - z_0} = -1.
$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=68]]


