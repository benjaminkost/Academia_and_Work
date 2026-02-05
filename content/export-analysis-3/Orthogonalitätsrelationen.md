---
"created date:": 29.01.2025 12:41
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[reelle fourieranalyse]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - grundlagen
  - vl-1
  - baby
aliases:
parent:
siblings:
child:
---
# Definition
Sei $T > 0$ und $\omega = \frac{2\pi}{T}$. Dann gilt für alle $k, \ell \in \mathbb{N}_0$:

1.  $\frac{2}{T} \int_0^T \cos(k\omega t) \cos(\ell\omega t) dt = \begin{cases} 2 & \text{falls } k = \ell = 0, \\ 1 & \text{falls } k = \ell > 0, \\ 0 & \text{falls } k \neq \ell \end{cases}$

2.  $\frac{2}{T} \int_0^T \sin(k\omega t) \sin(\ell\omega t) dt = \begin{cases} 1 & \text{falls } k = \ell > 0, \\ 0 & \text{sonst} \end{cases}$

3.  $\frac{2}{T} \int_0^T \sin(k\omega t) \cos(\ell\omega t) dt = 0$
[^1]
## In Polardarstellung
Sei $T > 0$ und $\omega = \frac{2\pi}{T}$. Für $k_1, k_2 \in \mathbb{Z}$ gilt die Identität:
$$
\frac{1}{T} \int_0^T e^{ik_1\omega t} e^{-ik_2\omega t} dt = \delta_{k_1,k_2}
$$
wobei
$$
\delta_{k_1,k_2} = \begin{cases} 1 & \text{falls } k_1 = k_2 \\ 0 & \text{sonst} \end{cases}
$$
das Kronecker-Delta ist.
[^2]
# Beweis
Es gilt
$$ \frac{1}{T} \int_0^T e^{ik_1\omega t} e^{-ik_2\omega t} dt = \frac{1}{T} \int_0^T e^{i(k_1-k_2)\omega t} dt = \int_0^1 e^{2\pi i(k_1-k_2)\tau} \,d\tau, $$
wobei wir die Substitution $t = \tau T$ benutzt haben.

Die Behauptung für $k_1 = k_2$ folgt daraus mit $\int_0^1 d\tau = 1$.

Für $k_1 \neq k_2$ erhalten wir
$$ \int_0^1 e^{2\pi i(k_1-k_2)\tau} \,d\tau = \left[ \frac{e^{2\pi i(k_1-k_2)\tau}}{2\pi i(k_1 - k_2)} \right]_0^1 = \frac{e^{2\pi i(k_1-k_2)} - 1}{2\pi i(k_1 - k_2)} = 0. $$
[^3]
# Beispiele


# Referenz
## Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.ctime ASC
```
## Verknüpfung
- [[Trigonometrische Polynome]]
- [[Orthogonale Vektoren]]
- [[Fourierpolynom]]
- [[Integration komplexer Funktionen]]
- [[Sinus]]
## Quellen
- [[VL-37-Folien-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf]]
- [[VL-37-E-Kreide-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf]]
- [[Vorlesung203720-20Teil20220-20Fourierkoeffizienten20und20Fourierpolynome.mp4]]
- [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=8]]
- [[tub_Analysis_I_und_Lineare_Algebra.pdf#page=283]]

[^1]: [[VL-37-Folien-Ana1-LinA-Winkert-Reelle-Fourieranalysis.pdf#page=page=5]]

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=8]]

[^3]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=8]]




