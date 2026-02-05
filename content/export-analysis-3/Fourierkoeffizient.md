---
"created date:": 30.01.2025 20:12
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[reelle fourieranalyse]]"
  - "[[Analina I - Klausur-Formelzettel]]"
  - "[[analina_I_problemfeld]]"
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
  - Bestimmen von reellen Fourierkoeffizienten
parent:
siblings:
child:
---
# Definition
Sei $f : \mathbb{R} \to \mathbb{R}$ (oder $f : \mathbb{R} \to \mathbb{C}$) eine stückweise monotone Funktion (dann ist $f$ integrierbar, vgl. VL 28) der Periode $T > 0$ und $\omega = \frac{2\pi}{T}$.

Für $k \in \mathbb{N}$ heißen
$a_k = \langle f, \cos(k\omega t) \rangle = \frac{2}{T} \int_{0}^{T} f(t) \cos(k\omega t) dt,$
$b_k = \langle f, \sin(k\omega t) \rangle = \frac{2}{T} \int_{0}^{T} f(t) \sin(k\omega t) dt,$
die **reellen Fourierkoeffizienten** von $f$.

$\varphi_n(t) = \frac{a_0}{2} + \sum_{k=1}^{n} (a_k \cos(k\omega t) + b_k \sin(k\omega t))$
heißt das **n-te Fourierpolynom** oder das **Fourierpolynom der Ordnung n** von $f$.
[^1]
## Bemerkung
1. Die Fourierkoeffizienten sind genau wie die Koeffizienten eines Vektors bezüglich einer ONB definiert.
2. Der konstante Term ist $\frac{a_0}{2}$ und nicht $a_0$, da $\langle \cos(0\omega t), \cos(0\omega t) \rangle = 2$ und nicht 1 ist (siehe [[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=11|E-Kreide]]), was hier ausgeglichen wird.
3. Es ist immer $b_0 = 0$, da $\sin(0\omega t) = 0$ ist.
4. Für die Fourierkoeffizienten von $\varphi_n$ gilt:
   $\frac{2}{T} \int_{0}^{T} \varphi_n(t) \cos(k\omega t) dt = a_k = \frac{2}{T} \int_{0}^{T} f(t) \cos(k\omega t) dt,$
   $\frac{2}{T} \int_{0}^{T} \varphi_n(t) \sin(k\omega t) dt = b_k = \frac{2}{T} \int_{0}^{T} f(t) \sin(k\omega t) dt.$
[^2]
# Beispiele
![[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=5]]
![[Bildschirmfoto 2025-01-29 um 12.55.16.png]]
## Sägezahnkurve
![[Bildschirmfoto 2025-01-29 um 12.58.13.png]]
![[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=12]]
![[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=13]]
![[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=14]]
# Referenz
## Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.ctime ASC
```
- [[analina_I_2024_02_Probeklausur_1.pdf#page=7]] d)
## Verknüpfung
- [[Sinus]]
- [[Cosinus]]
- [[Skalarprodukt]]
- [[Norm]]
- [[Sägezahnkurve]]
- [[Fourierpolynom]]
- [[Umrechnungsformeln zwischen reellen und komplexen Fourierkoeffizienten]]
## Quellen
- [[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf]]
- [[Vorlesung203720-20Teil20220-20Fourierkoeffizienten20und20Fourierpolynome.mp4]]
- [[Vorlesung203720-20Teil20320-20Beispiel20Sgezahnkurve.mp4]]
- [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=11]]

[^1]: [[VL-37-Folien-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=6]]

[^2]: [[VL-37-Folien-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=7]]



