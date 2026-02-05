---
"created date:": 30.10.2025 00:23
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
  - beweise
aliases:
  - Beweis zu Berechnung trigonomische Integrale
parent:
siblings:
child:
mathematical statement: "[[202511111711 - Berechnung trigonometrischer Integrale|Berechnung trigonometrischer Integrale]]"
---
# Beweis
Nach Definition des Wegintegrals gilt
$$ \oint_{\partial B_1(0)} f(z)dz = \int_0^{2\pi} f(e^{it})ie^{it}dt $$
also
$$ \oint_{\partial B_1(0)} \frac{f(z)}{iz} dz = \int_0^{2\pi} f(e^{it}) dt . $$
Ist $f$ die Funktion ([[202511111711 - Berechnung trigonometrischer Integrale|Gleichung 2.26]]) dann ist
$$ f(e^{it}) = g(\cos(t), \sin(t)) $$
wegen der Eulerformel. Daraus folgt die Behauptung.

Integrale wie auf der rechten Seite von ([[202511111711 - Berechnung trigonometrischer Integrale|Gleichung 2.25]]) lassen sich direkt mit dem Residuensatz berechnen (wenn $f$ die entsprechenden Voraussetzungen erfüllt).
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=101]]


