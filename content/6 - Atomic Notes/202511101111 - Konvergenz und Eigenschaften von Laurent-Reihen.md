---
"created date:": 29.10.2025 23:27
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
  - Konvergenz und Eigenschaften von Laurent-Reihen
  - Lemma 2.9.3
parent:
siblings:
child:
proof:
---
# Lemma
Sei $Q(z) = \sum_{k=-\infty}^\infty c_k(z-z_0)^k$ eine Laurent-Reihe und $1/r, R$ die entsprechenden Konvergenzradien des Haupt- und Nebenteils. Dann konvergiert $Q(z)$ auf dem Kreisring $A_{r,R}(z_0)$ und stellt dort eine holomorphe Funktion $f: A_{r,R}(z_0) \to \mathbb{C}$ dar. Weiter gilt:
(i) Die Funktion $f$ ist holomorph auf $A_{r,R}(z_0)$ mit Ableitung
$$ f'(z) = \sum_{k=-\infty}^\infty k c_k (z-z_0)^{k-1}. $$
(ii) Ist $c_{-1}=0$, dann ist
$$ F(z) = \sum_{k=-\infty}^\infty \frac{c_k}{k+1} (z-z_0)^{k+1} $$
eine Stammfunktion von $f$ auf $A_{r,R}(z_0)$.
Analog wie bei Potenzreihen (bzw. Taylor-Reihen) lassen sich die Laurent-Reihenkoeffizienten $\{c_k\}_{k\in\mathbb{Z}}$ durch Kurvenintegrale ausdrücken:
[^1]
# Visualisierung
![[Bildschirmfoto 2025-10-29 um 23.28.28.png|400]]
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=91]]


