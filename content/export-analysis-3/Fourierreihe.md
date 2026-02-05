---
"created date:": 29.01.2025 12:41
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[Approximation mit Fourierpolynomen im quadratischen Mittel]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[6 - Atomic Notes/Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[reelle fourieranalyse]]"
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
Sei $f : \mathbb{R} \to \mathbb{R}$ eine $T$-periodische Funktion mit den Fourierkoeffizienten $a_k$ und $b_k$ und sei $\omega = \frac{2\pi}{T}$. Dann heißt
$$
\frac{a_0}{2} + \sum_{k=1}^{\infty} (a_k \cos(k\omega t) + b_k \sin(k\omega t)) := \lim_{n\to\infty} \left( \frac{a_0}{2} + \sum_{k=1}^{n} (a_k \cos(k\omega t) + b_k \sin(k\omega t)) \right)
$$
die Fourierreihe von $f$.

1. Die Fourierreihe von $f$ entspricht der [[Orthonormalbasis|ONB]]-Entwicklung (siehe Satz 3, VL 35, Folie 10), nur mit unendlich vielen Termen.
2. Die Fourierpolynome entsprechen der Bestapproximation durch trigonometrische Polynome (siehe Satz 2, VL 36, Folie 3), d.h. $φ_n$ ist die orthogonale Projektion von $f$ auf den Teilraum der trigonometrischen Polynome.
3. Die Approximation im quadratischen Mittel auf Folie 11 besagt, dass die Fourierreihe im quadratischen Mittel gegen $f$ konvergiert. Der Approximationsfehler $\|f - φ_n\|_{L^2} = \sqrt{\frac{2}{T} \int_{0}^{T} (f(t) - φ_n(t))^2 dt}$ konvergiert gegen 0 für $n \to \infty$.
# Beispiele
Die Funktionen $\cos, \sin : \mathbb{R} \to \mathbb{R}$ sind $2\pi$-periodisch. Seien $k \in \mathbb{Z}\setminus\{0\}$ und $\omega > 0$. Mit
$$e^{ik\omega t} = \cos(k\omega t) + i \sin(k\omega t) \quad (1.1)$$
folgt, dass die Funktion $t \mapsto e^{ik\omega t}$ periodisch ist mit Periode $T_k = T/|k|$, wobei $T = \frac{2\pi}{\omega}$. Die zugehörige Kreisfrequenz ist $\omega_k = |k|\omega$, also:

| | Periode | Kreisfrequenz $\omega_k$ | Frequenz in Hertz |
|---|---|---|---|
| $k \in \{\pm 1\}$ | $T$ | $\omega$ | $1/T$ |
| $k \in \{\pm 2\}$ | $T/2$ | $2\omega$ | $2/T$ |
| ... | ... | ... | ... |

Hier bezeichnet die [[Frequenz]] (in Hertz) die Anzahl der Schwingungen pro Sekunde.

**Bemerkung 1.1.3.**
Genauer ist die Funktion $t \mapsto e^{ik\omega t}$ periodisch mit Periode $nT/k = nT_k$ für jedes $n \in \mathbb{N}$, d.h. $T_k$ ist die kleinste Periode der Funktion.

**Bemerkung 1.1.4.**
Für $k = 0$ (und damit $\omega_k = 0$) ist die Funktion $t \mapsto e^{ik\omega t}$ konstant (also $T$-periodisch für jedes $T > 0$).

Aus Beispiel 1.1.2 folgt, dass für alle $n \in \mathbb{N}$ und $\{c_k\}_{k=-n}^n \subset \mathbb{C}$ die Funktion
$$s_n(t) = \sum_{k=-n}^{n} c_k e^{ik\omega t} \quad (1.2)$$
$T$-periodisch ist mit $T = \frac{2\pi}{\omega}$. Nach Bemerkung 1.1.3 ist dies die kleinste gemeinsame Periode der Funktionen $t \mapsto e^{ik\omega t}$, $k = -n, \dots, n$. Eine Funktion der Form (1.2) heißt **trigonometrisches Polynom** oder **Fourierpolynom**.

**Beispiel 1.1.6.**
Sei $\theta \in \mathbb{R}$. Die Funktion $f(t) := \cos(t + \theta)$ ist $2\pi$-periodisch (also $\omega = 1$). Dies ist die kürzeste Periode (die Funktion ist auch $T$-periodisch für $T = 2\pi, 4\pi, 6\pi, \dots$). Sie hat, wie wir jetzt zeigen werden, die Fourierdarstellung
$$f(t) = \frac{e^{i\theta}}{2} e^{it} + \frac{e^{-i\theta}}{2} e^{-it} \quad (1.3)$$
also Fourierkoeffizienten
$$
c_k = \begin{cases}
\frac{e^{i\theta}}{2} & \text{für } k = 1 \\
\frac{e^{-i\theta}}{2} & \text{für } k = -1 \\
0 & \text{sonst}
\end{cases}
$$
Zum Nachweis (1.3) verwenden wir die Eulersche Formel
$$\cos(t) = \frac{e^{it} + e^{-it}}{2} \quad \text{für alle } t \in \mathbb{R} \quad (1.4)$$
und die Tatsache, dass $e^{i(u+v)} = e^{iu}e^{iv}$:
$$\cos(t + \theta) = \frac{e^{i(t+\theta)} + e^{-i(t+\theta)}}{2} = \frac{e^{i\theta}}{2} e^{it} + \frac{e^{-i\theta}}{2} e^{-it}.$$
Ähnlich erhalten wir aus
$$\sin(t) = \frac{e^{it} - e^{-it}}{2i} = -\frac{i}{2}e^{it} + \frac{i}{2}e^{-it} \quad (1.5)$$
(wir haben $1/i = -i$ verwendet) die Fourierdarstellung
$$\sin(3t) = -\frac{i}{2}e^{3it} + \frac{i}{2}e^{-3it}$$
der Funktion $t \mapsto \sin(3t)$, deren kürzeste Periode $T = 2\pi/3$ ist. In beiden Fällen hat die Fourierreihe nur endlich viele Summanden, ist also ein Fourierpolynom.

**Beispiel 1.1.7 (Endliche Überlagerung).**
Seien $A, B \in \mathbb{R}$. Betrachte die Funktion (siehe Fig. 1)
$$f(t) = A + \cos(t + \theta) + B \sin(3t). \quad (1.6)$$
Da die konstante Funktion $t \mapsto A$ $T$-periodisch für jedes $T > 0$ ist und $t \mapsto \cos(t + \theta)$ bzw. $t \mapsto \sin(3t)$ kürzeste Perioden $2\pi$ bzw. $2\pi/3$ besitzen, ist die kürzeste gemeinsame Periode aller Summanden gleich $T = 2\pi$. Die zugehörige Kreisfrequenz ist $\omega = \frac{2\pi}{T} = \frac{2\pi}{2\pi} = 1$. Wir erhalten damit die Fourierdarstellung
$$f(t) = A + \frac{e^{i\theta}}{2} e^{it} + \frac{e^{-i\theta}}{2} e^{-it} - \frac{Bi}{2} e^{3it} + \frac{Bi}{2} e^{-3it},$$
also die Fourierkoeffizienten
$$
c_k = \begin{cases}
A & \text{für } k = 0 \\
\frac{e^{i\theta}}{2} & \text{für } k = 1 \\
\frac{e^{-i\theta}}{2} & \text{für } k = -1 \\
-\frac{Bi}{2} & \text{für } k = 3 \\
\frac{Bi}{2} & \text{für } k = -3 \\
0 & \text{sonst}
\end{cases}
$$
![[Bildschirmfoto 2025-10-13 um 10.04.50.png]]
# Referenz
## Verknüpfung
- [[Fourierpolynom]]
- [[Konvergenz von Fourierreihen]]
- [[Sägezahnkurve]]
- [[Euler-Formel|Polardarstellung]]
- [[Sinus]]
- [[Cosinus]]
## Quellen
- [[VL-38-Folien-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=12]]
- [[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf]]
- [[Vorlesung203820-20Teil20320-20Approximation20im20quadratischen20Mittel20und20Konvergenz20von20Fourierreihen.mp4]]
- [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=5]]
## Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.ctime ASC
```



