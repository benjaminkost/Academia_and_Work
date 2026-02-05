---
"created date:": 20.10.2025 09:41
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[202510201010 - Periodisches Faltungsprodukt|Das periodische Faltungsprodukt oder die Faltung]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - vl-3
  - baby
aliases:
  - Faltung mit konstanten und harmonischen Funktionen
  - Beispiel 1.1.45
parent:
siblings:
child:
mathematical statement: "[[202510201010 - Periodisches Faltungsprodukt|Das periodische Faltungsprodukt]]"
---
# Beispiel
Sei $1$ die konstante Funktion $1(t) = 1$ für alle $t \in \mathbb{R}$. Dann ist:
$$
(1 * f)(t) = \frac{1}{T} \int_{0}^{T} 1 \cdot f(s)ds = c_0 \quad \text{für jedes } t \in \mathbb{R}
$$
der 0-te Fourierkoeffizient von $f$. Allgemeiner sei für $k \in \mathbb{Z}$ die Funktion $e_k : \mathbb{R} \to \mathbb{C}$ definiert durch $e_k(t) = e^{ik\omega t}$ für alle $t \in \mathbb{R}$, wobei $\omega = 2\pi/T$. Dann gilt:
$$
(e_k * f)(t) = \frac{1}{T} \int_{0}^{T} e^{ik\omega(t-s)}f(s)ds = \frac{e^{ik\omega t}}{T} \int_{0}^{T} e^{-ik\omega s}f(s)ds = c_k \cdot e^{ik\omega t} \quad \text{für alle } t \in \mathbb{R}
$$
Die Faltung einer Funktion $f$ mit der Funktion $e_k$ gibt uns also die k-te Teilschwingung in der Fourierreihe von $f$.[^1]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=20]]




