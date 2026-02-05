---
"created date:": 17.10.2025 15:13
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[beweise]]"
  - "[[eigenschaften von fourierreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Beweis für Stammfunktionen als Transformation des Fourierspektrums
  - Beweis 1.1.36
parent:
siblings:
child:
mathematical statement: "[[202510172010 - Lemma für das Fourierspektrums der Stammfunktion]]"
---
# Beweis
Zum Beweis von [[202510172010 - Lemma für das Fourierspektrums der Stammfunktion|Stammfunktionen als Transformation des Fourierspektrums]] berechnen wir den 0-ten Fourierkoeffizient ${d_0}$ von ${F}$ durch partielle Integration. Wir erhalten
$${
\begin{aligned}
d_0 &= \frac{1}{T} \int_0^T \left( \int_0^t f(s)ds \right) dt \\
&= \frac{1}{T} \left[ t \int_0^t f(s)ds \right]_{t=0^+}^{t=T^-} - \frac{1}{T} \int_0^T tf(t)dt \\
&= -\frac{1}{T} \int_0^T tf(t)dt \quad \text{wegen Bedingung (1.16)}.
\end{aligned}
}$$
[^1]
Für ${k \in \mathbb{Z}\setminus\{0\}}$ wenden wir Aussage (i) auf ${F}$ an: Weil ${F' = f}$ erhalten wir die Beziehung
${ik\omega d_k = c_k \quad \text{für alle } k \in \mathbb{Z}\setminus\{0\}}$.
Daraus folgt ${d_k = \frac{c_k}{ik\omega}}$ für ${k \ne 0}$ wie behauptet.
[^2]
# Beispiele


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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=16]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=17]]



