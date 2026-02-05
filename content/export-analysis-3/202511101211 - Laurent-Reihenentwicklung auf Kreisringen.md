---
"created date:": 29.10.2025 23:30
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
  - Lemma
aliases:
  - Laurent-Reihenentwicklung auf Kreisringen
  - Theorem 2.9.4
parent:
siblings:
child:
proof:
  - "[[202511101311 - Beweis für Laurent-Reihenentwicklung auf Kreisringen|Beweis für Laurent-Reihenentwicklung auf Kreisringen]]"
---
# Lemma
Seien $0 \le r < R \le \infty$ und sei $f : A_{r,R}(z_0) \to \mathbb{C}$ holomorph auf $A_{r,R}(z_0)$. Dann kann $f$ auf $A_{r,R}(z_0)$ als Laurent-Reihe
$$ f(z) = \sum_{k=-\infty}^{\infty} c_k (z - z_0)^k $$
dargestellt werden mit absoluter und gleichmäßiger Konvergenz des Hauptteils auf $A_{\tilde{r},\infty}(z_0)$ für jedes $\tilde{r}>r$, und absoluter und gleichmäßiger Konvergenz des Nebenteils auf $B_{R'}(z_0)$ für jedes $R' < R$. Die Koeffizienten $\{c_k\}_{k\in\mathbb{Z}}$ sind durch die Formel
$$ c_k = \frac{1}{2\pi i} \oint_{|z-z_0|=\rho} \frac{f(z)}{(z-z_0)^{k+1}} dz \quad \forall k \in \mathbb{Z} $$
für $\rho \in (r, R)$ beliebig gegeben. Insbesondere ist die darstellende Laurent-Reihe eindeutig durch $f$ bestimmt.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=92]]




