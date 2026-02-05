---
"created date:": 29.01.2025 12:41
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[Approximation mit Fourierpolynomen im quadratischen Mittel]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-1
  - baby
aliases:
  - Theorem 1.1.21
  - Gleichmäßige Konvergenz von Fourierreihen
  - Punktweise Konvergenz gegen Fourierreihen
parent:
siblings:
child:
in own words: "[[202511131811 - Konvergenz von Fourierreihen in eigenen worten]]"
---
# Definition
Sei $f : \mathbb{R} → \mathbb{C}$ $T$-periodisch und stückweise stetig differenzierbar. Dann gilt:

(i) (Punktweise Konvergenz): $S_f(t)$ konvergiert in jedem $t \in \mathbb{R}$ gegen $\frac{f(t^{-}) + f(t^{+})}{2}$. Insbesondere konvergiert $S_f(t)$ gegen $f(t)$, falls $f$ in $t$ stetig ist.

(ii) (Gleichmäßige Konvergenz): Auf jedem abgeschlossenen Intervall $[a, b]$ ohne Sprungstellen von $f$ konvergieren die Partialsummen $S_{f}^n$ gleichmäßig gegen $f$ für $n \to \infty$.
[^1]
# Visualisierung
![[Bildschirmfoto 2025-10-13 um 10.17.06.png]]
[^2]
# Beispiele
![[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=12]]
![[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=13]]
![[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=14]]

# Referenz
# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.ctime ASC
```
## Fragen
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[fragen]])
SORT file.ctime ASC
```
## Verknüpfung
- [[Konvergenz]]
- [[Arithmetisches Mittel|Mittelwert]]
- [[Fourierreihe]]
- [[6 - Atomic Notes/Monotonie|Monotonie]]
- [[Periodische Funktion]]
- [[Rechtsseitiger Grenzwert]]
- [[Linksseitiger Grenzwert]]
## Quellen
- [[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=12]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=10]] ähnlich wie [[VL-38-Folien-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=14]]  

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=10]]



