---
"created date:": 03.02.2025 14:16
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[komplexe fourieranalyse]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
parent:
siblings:
child:
---
# Definition
Sei $f: \mathbb{R} \to \mathbb{R}$ (oder $f: \mathbb{R} \to \mathbb{C}$) eine $T$-periodische Funktion und $\omega = \frac{2\pi}{T}$.
1.  **Von reellen zu komplexen Fourierkoeffizienten:**
    Sind die reellen Fourierkoeffizienten $a_k, b_k$ gegeben, so sind die komplexen Koeffizienten:
    *   $c_k = \frac{1}{2} (a_k - ib_k)$, für $k \geq 1$
    *   $c_0 = \frac{a_0}{2}$
    *   $c_{-k} = \frac{1}{2} (a_k + ib_k)$, für $k \geq 1$

2.  **Von komplexen zu reellen Fourierkoeffizienten:**
    Sind die komplexen Fourierkoeffizienten $c_k, k \in \mathbb{Z}$, gegeben, so gilt:
    *   $a_0 = 2c_0$
    *   $a_k = c_k + c_{-k}=2\cdot \mathrm{Re}(c_{k})$, für $k \geq 1$
    *   $b_k = i(c_k - c_{-k})=-2 \cdot Im(c_{k})$, für $k \geq 1$
[^1]
# Herleitung
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=10]]
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=11]]
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=12]]
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=13]]
![[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=14]]


# Referenz
## Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.ctime ASC
```
## Verknüpfung
- [[Fourierpolynom]]
- [[Fourierkoeffizient]]
- [[Komplexe Fourierkoeffizienten]]
- [[Komplexe Fourierpolynome]]
- [[Realteil der komplexen Zahl]]
- [[Imaginärteil der komplexen Zahl]]
## Quellen
- [[VL-39-E-Kreide-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf]]
- [[Vorlesung203920-20Teil20120-20Komplexe20Fourierkoeffizienten20und20Fourierpolynome.mp4]]
- [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=11]]

[^1]: [[VL-39-Folien-Ana1-LinA-Winkert-Komplexe-Fourieranalysis.pdf#page=5]]



