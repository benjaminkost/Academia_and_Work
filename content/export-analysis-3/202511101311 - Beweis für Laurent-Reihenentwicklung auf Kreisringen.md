---
"created date:": 29.10.2025 23:32
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Laurentreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beweise
aliases:
  - Beweis für Laurent-Reihenentwicklung auf Kreisringen
  - Gleichung 2.21
  - Gleichung 2.22
parent:
siblings:
child:
mathematical statement: "[[202511101211 - Laurent-Reihenentwicklung auf Kreisringen|Laurent-Reihenentwicklung auf Kreisringen]]"
---
# Beweis
(Beweisidee) Nach der Cauchy-Integralformel gilt für $\epsilon > 0$ klein genug
$$ 2\pi i f(z) = \oint_{\partial B_\epsilon(z)} \frac{f(w)}{w-z} dw. \quad (2.21) $$
Seien $\tilde{r}$ und $\tilde{R}$ so dass $r < \tilde{r} < \tilde{R} < R$. Wie im Beweis von [[202511090711 - Deformierbarkeit des Integrationsweges|Lemma 2.7.1]] verbinden wir den Kreis $\partial B_\epsilon(z)$ mittels zweier Liniensegmente $\nu_1, \nu_2$ mit $\partial B_{\tilde{r}}(z_0)$. Ebenso verbinden wir den Kreis $\partial B_\epsilon(z)$ mittels zweier Kurven $\tilde{\nu}_1, \tilde{\nu}_2$ mit $\partial B_{\tilde{R}}(z_0)$, siehe Abbildung 10.
Mit dem Integralsatz von Cauchy erhalten wir (weil wir die gesamte Kurve homotop innerhalb von $A_{r,R}(z_0)$ zu einem Punkt zusammen ziehen können und weil sich die Beiträge von $\tilde{\nu}_1$ und $\tilde{\nu}_2$, bzw. von $\nu_1$ und $\nu_2$ wegheben da sich die Kurven in einem passenden Grenzwert in unterschiedliche Richtungen überlappen)
$$\oint_{\partial B_\epsilon(z)} \frac{f(w)}{w-z} dw = \oint_{\partial B_{\tilde{R}}(z_0)} \frac{f(w)}{w-z} dw - \oint_{\partial B_{\tilde{r}}(z_0)} \frac{f(w)}{w-z} dw .$$
Damit folgt mit (2.21)
$$\begin{aligned}f(z) &= \frac{1}{2\pi i} \oint_{\partial B_{\tilde{R}}(z_0)} \frac{f(w)}{w-z} dw + \frac{1}{2\pi i} \oint_{\partial B_{\tilde{r}}(z_0)} \frac{f(w)}{z-w} dw \\&= \frac{1}{2\pi i} \oint_{\partial B_{\tilde{R}}(z_0)} \frac{f(w)}{w-z_0} \left( \frac{1}{1-\frac{z-z_0}{w-z_0}} \right) dw + \frac{1}{2\pi i} \oint_{\partial B_{\tilde{r}}(z_0)} \frac{f(w)}{z-z_0} \left( \frac{1}{1-\frac{w-z_0}{z-z_0}} \right) dw .\end{aligned}$$
Die Behauptung folgt dann durch Ersetzen der Ausdrücke in Klammern durch geometrische Reihen (wobei man hier wieder gleichmäßige Konvergenz benutzt).
[^1]
# Visualisierung
![[Bildschirmfoto 2025-10-29 um 23.34.56.png|400]]
Abbildung 10: Beweisidee für den Laurent-Reihenentwicklungssatz

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=93]]


