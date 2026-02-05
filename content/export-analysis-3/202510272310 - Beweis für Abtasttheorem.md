---
"created date:": 22.10.2025 15:30
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510270410 - Das Abtasttheorem|Das Abtasttheorem]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Abtasttheorem
parent:
siblings:
child:
mathematical statement: "[[202510270410 - Das Abtasttheorem|Das Abtasttheorem]]"
---
# Beweis
Wir zeigen die Behauptung zunaechst für die Funktion $t \to f(t) = e^{i\omega t}$, d.h. wir beweisen die Abtastformel
$$
e^{i\omega t} = \sum_{k \in \mathbb{Z}} e^{ik\omega \Delta t} \text{sinc} \left( \frac{\pi}{\Delta t}(t-k\Delta t) \right) \quad \text{für } t \in \mathbb{R},
$$
wobei wir als Bedingung annehmen dass $2|\omega| < \omega_s$ gelten muss.
Wir betrachten dazu die Abtastwerte $f(k\Delta t) = e^{i\omega(k\Delta t)} =: e_k(\omega)$ als Funktionen von $\omega$. Offenbar ist $e_k(\omega) = e^{ik\Delta t \omega}$ genau die k-te harmonische Funktion über dem $\omega$-Periodenintervall $(-\omega_s/2, \omega_s/2)$ der Länge $\omega_s = \frac{2\pi}{\Delta t}$. Die zugehörige Kreisfrequenz ist $2\pi/\omega_s = \Delta t$.
Betrachten wir jetzt ein fixes $t \in \mathbb{R}$. Dann ist die Fourierreihe der Funktion $\omega \to e^{i\omega t} =: g(\omega)$ für $\omega \in (-\omega_s/2, \omega_s/2)$, und $\omega_s$-periodisch fortgesetzt
$$
S_g(\omega) = \sum_{k \in \mathbb{Z}} c_k e_k(\omega) = \sum_{k \in \mathbb{Z}} c_k e^{ik\Delta t \omega} \quad \text{mit} \quad c_k = \frac{\Delta t}{2\pi} \int_{-\pi/\Delta t}^{\pi/\Delta t} e^{i\omega t} e^{-i\omega k \Delta t} d\omega.
$$
Das Integral für $c_k$ kann mit der Eulerschen Formel $e^{i\theta} = \cos(\theta) + i\sin(\theta)$ berechnet werden mit dem Ergebnis
$$
c_k = \text{sinc}\left( \frac{\pi}{\Delta t}(t-k\Delta t) \right) \quad \text{für } k \in \mathbb{Z}.
$$
Damit ist die Fourierreihe
$$
S_g(\omega) = \sum_{k \in \mathbb{Z}} \text{sinc}\left( \frac{\pi}{\Delta t}(t-k\Delta t) \right) e_k(\omega)
$$
eine $\omega_s$-periodische Funktion, die $S_g(\omega) = g(\omega)$, d.h.
$$
\sum_{k \in \mathbb{Z}} \text{sinc}\left( \frac{\pi}{\Delta t}(t-k\Delta t) \right) e^{ik\omega \Delta t} = e^{i\omega t} \quad \text{für alle } \omega \in (-\omega_s/2, \omega_s/2)
$$
erfüllt. Dies folgt aus Theorem 1.1.21, weil die Funktion $g$ in jedem Punkt $\omega \in (-\omega_s/2, \omega_s/2)$ stetig ist und dort den Wert $g(\omega) = e^{i\omega t}$ annimmt. Da $t \in \mathbb{R}$ beliebig war, ist die Abtastformel (1.63) für die Funktion $f(t) = e^{i\omega t}$ bewiesen.
Sei jetzt $f \in L^1(\mathbb{R})$ beliebig aber bandbegrenzt mit Schranke $\Omega \ge 0$ und $\omega_s > 2\Omega$. Es folgt (unter den gemachten Voraussetzungen an f gilt $f = \check{\hat{f}}$)
$$
\begin{align*}
f(t) = \check{\hat{f}}(t) &= \frac{1}{2\pi} \int_{-\infty}^{\infty} \hat{f}(\omega) e^{i\omega t} d\omega = \frac{1}{2\pi} \int_{-\Omega}^{\Omega} \hat{f}(\omega) e^{i\omega t} d\omega \\
&= \frac{1}{2\pi} \int_{-\Omega}^{\Omega} \hat{f}(\omega) \left( \sum_{k \in \mathbb{Z}} e^{ik\omega\Delta t} \text{sinc}\left( \frac{\pi}{\Delta t}(t-k\Delta t) \right) \right) d\omega \\
&= \sum_{k \in \mathbb{Z}} \left( \frac{1}{2\pi} \int_{-\Omega}^{\Omega} \hat{f}(\omega)e^{ik\omega\Delta t} d\omega \right) \text{sinc}\left( \frac{\pi}{\Delta t}(t-k\Delta t) \right) \\
&= \sum_{k \in \mathbb{Z}} \check{\hat{f}}(k\Delta t) \text{sinc}\left( \frac{\pi}{\Delta t}(t-k\Delta t) \right) = \sum_{k \in \mathbb{Z}} f(k\Delta t) \text{sinc}\left( \frac{\pi}{\Delta t}(t-k\Delta t) \right),
\end{align*}
$$
wie behauptet.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=51]]


