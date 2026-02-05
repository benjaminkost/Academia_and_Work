---
"created date:": 30.10.2025 00:21
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
  - Lemma
aliases:
  - Berechnung trigonometrischer Integrale
  - Gleichung 2.25
  - Gleichung 2.26
  - Lemma 2.11.11
parent:
siblings:
child:
proof:
  - "[[202511111811 - Beweis zu Berechnung trigonomische Integrale|Beweis zu Berechnung trigonomische Integrale]]"
---
# Lemma
Sei $g : \mathbb{C} \times \mathbb{C} \to \mathbb{C}$ gegeben. Dann ist
$$\int_0^{2\pi} g(\cos(t), \sin(t)) dt = \oint_{\partial B_1(0)} \frac{f(z)}{iz} dz, \quad (2.25)$$
wobei die Funktion $f$ durch
$$f(z) = g\left( (z+z^{-1})/2, (z-z^{-1})/(2i) \right) \quad (2.26)$$
definiert ist.
[^1]
# Visualisierung
![[Bildschirmfoto 2025-10-30 um 00.22.30.png|400]]
Abbildung 11: Beweisidee für den Beweis des Residuensatzes.
[^2]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=100]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=101]]


