---
"created date:": 05.11.2025 10:23
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510201010 - Periodisches Faltungsprodukt|Periodisches Faltungsprodukt]]"
tags:
  - aufgaben
  - 3-Semester
  - 1-Semester
  - baby
  - flashcards
  - Analysis3
aliases:
  - Übung 4
parent:
siblings:
child:
---
# 4. Übung zur Vorlesung „Analysis 3 (EI)“ (WS 2025/2026)

## Zentralübung (5.11.):
### Aufgabe Z 4.1: (LTI-System)
Betrachtet werde die Gleichung
$$ \ddot{y}(t) + 2 \dot{y}(t) + 2 y(t) = x(t) $$
mit $2\pi$-periodischem Eingang $x : \mathbb{R} \to \mathbb{R}$. Bestimmen Sie
a) den zugehörigen Frequenzgang $(d_k)_{k \in \mathbb{Z}}$,
b) die Fourier-Reihe der Impulsantwort $h$,
c) die Fourier-Reihe der $2\pi$-periodischen Antwort $y$ für den Eingang $x \equiv s$, also für die Sägezahnfunktion $s$ aus der Vorlesung.
?
## Lösung Z 4.1:

a) Mit $\omega = 2\pi T = 1$ und dem charakteristischen Polynom $P(s) = s^2 + 2s + 2$ erhalten wir für $k \in \mathbb{Z}$ den Frequenzgang $d_k = \frac{1}{P(ik\omega)} = \frac{1}{2 + 2ik - k^2}$ des LTI-Systems.

b) Folglich hat $h$ die Fourier-Reihe $S_h(t) = \sum_{k=-\infty}^{\infty} d_k e^{i k \omega t} = \sum_{k=-\infty}^{\infty} \frac{e^{i k t}}{2 + 2ik - k^2}$.

c) Laut Vorlesung hat $s : \mathbb{R} \to \mathbb{R}$ Fourier-Koeffizienten $c_k = \frac{1}{2ik}$ für $k \neq 0$ und $c_0 = 0$. Demnach besitzt das periodisch gefaltete Ausgangssignal $y \equiv h * s$ wegen der Produktregel die Fourier-Reihe $S_y(t) = \sum_{k=-\infty}^{\infty} c_k d_k e^{i k t} = \sum_{k=-\infty, k \neq 0}^{\infty} \frac{e^{i k t}}{2ik (2 + 2ik - k^2)}$ für alle $t \in \mathbb{R}$.
***
[^1]
### Aufgabe Z 4.2: (Die schwingende Saite)
Die stetige Saite $u \equiv u(x, t)$ sei gemäß $u(0, t) \equiv 0$ und $u(\pi, t) \equiv 0$ eingespannt und erfülle die Wellengleichung $\partial^2_t u = c^2 \partial^2_x u$ mit $c > 0$. Bestimmen Sie durch das in a) bis c) dargestellte „Rezept“ die Schwingung für $x \in [0, \pi]$ und $t \geq 0$, welche durch die zwei Anfangsbedingungen $u(x, 0) \equiv g(x)$ und $\partial_t u(x, 0) \equiv h(x)$ ausgelöst wird.

a) Zeigen Sie, dass der Separationsansatz $u(x, t) \equiv v(x)w(t)$ im Fall $u \not\equiv 0$ die Identität $v'' + \lambda v \equiv 0$ für ein $\lambda \in \mathbb{R}$ impliziert. Was muss $w$ dann erfüllen?
b) Warum muss für nichttriviale Lösungen $u$ sogar $\lambda > 0$ sein? Bestimmen Sie aus den Einspannbedingungen alle möglichen Werte $\lambda_n$ von $\lambda$ und eine zugehörige Lösungsbasis $u_n(x, t) \equiv v_n(x)w_n(t)$ für $n \in \mathbb{N}$ der Wellengleichung.
c) Erklären Sie mittels Superposition $u \equiv \sum_{n=1}^{\infty} u_n$ der Lösungen in b), warum
$$ u(x, t) \equiv \sum_{n=1}^{\infty} \sin nx (d_n \cos cnt + e_n \sin cnt) \quad (*) $$
im Konvergenzfall für passende $d_n, e_n \in \mathbb{R}$ die Saite darstellt. Wie muss man $d_n$ und $e_n$ wählen, damit die zwei Anfangsbedingungen erfüllt sind? Hierbei seien im Intervall $[0, \pi]$ einerseits $g$ stetig und stückweise $C^2$, andererseits $h$ eine stückweise $C^1$-Funktion, damit die Wellengleichung sinnvoll bleibt. Außerdem müssen $g$ und $h$ aufgrund der Einspannbedingungen offenbar $g(0) = g(\pi) = 0$ und $h(0) = h(\pi) = 0$ erfüllen.
?
## Lösung Z 4.2:

a) Separieren wir Ort $x$ und Zeit $t$ gemäß $u(x, t) \equiv v(x)w(t)$, so reduziert sich die Wellengleichung zu $v(x) \ddot{w}(t) \equiv c^2 v''(x)w(t)$. An Stellen $(x, t)$ mit $v(x) \neq 0$ und $w(t) \neq 0$ lässt sich dies schreiben als
$$ \frac{\ddot{w}(t)}{c^2 w(t)} \equiv \frac{v''(x)}{v(x)} $$
Da $t$ und $x$ unabhängig voneinander variiert werden können, kann diese Identität nur gelten, wenn beide Seiten konstant sind. Wählt man als Konstante $-\lambda \in \mathbb{R}$, so führt das auf die Identitäten $v''(x) + \lambda v(x) = 0$ für alle $x$ mit $v(x) \neq 0$ sowie $\ddot{w}(t) + c^2 \lambda w(t) = 0$ an allen Stellen $t$ mit $w(t) \neq 0$. An einer Stelle $x$ mit $v(x) = 0$ folgt aus der Wellengleichung $v(x) \ddot{w}(t) \equiv c^2 v''(x)w(t)$, dass entweder $v''(x) = 0$ oder $w \equiv 0$ gelten muss. Im zweiten Fall gilt wegen $u \equiv vw$ offensichtlich $u \equiv 0$, was nach Voraussetzung ausgeschlossen ist. Daher gilt $v''(x) = 0$ und somit auch hier $v''(x) + \lambda v(x) = 0$. Analog für $\ddot{w}(t) + c^2 \lambda w(t) = 0$ an den Stellen $t$ mit $w(t) = 0$. Damit ist gezeigt, dass sowohl $v'' + \lambda v \equiv 0$ als auch $\ddot{w} + c^2 \lambda w \equiv 0$ gilt.

b) Da $u \not\equiv 0$ vorausgesetzt ist, ist das stetige $v \equiv v(x)$ nicht überall Null, also folgt mit partieller Integration
$$ \lambda \int_0^\pi v(x)^2 dx = - \int_0^\pi v(x)v''(x) dx = - [v(x)v'(x)]_0^\pi + \int_0^\pi v'(x)^2 dx $$
wobei wir die Einspannbedingungen $v(0) = v(\pi) = 0$ benutzt haben, die aus $u(0, t) \equiv 0$ und $u(\pi, t) \equiv 0$ folgen. Offenbar kann die Gleichung nur für Werte $\lambda > 0$ erfüllt sein. Daher besitzt die lineare Differentialgleichung $v'' + \lambda v = 0$ die allgemeine Lösung $v(x) = C_1 \cos(\sqrt{\lambda} x) + C_2 \sin(\sqrt{\lambda} x)$, die allerdings hierbei die Einspannbedingungen erfüllen muss: $v(0) = 0$ zeigt $C_1 = 0$, $v(\pi) = 0$ daraufhin die Ganzzahligkeit von $\sqrt{\lambda}$, d.h. $\sqrt{\lambda} = n \in \mathbb{N}$.

Die Basislösungen der Gleichungen $v'' + \lambda v = 0$ mit $v(0) = v(\pi) = 0$ und $\sqrt{\lambda} = n \in \mathbb{N}$ sind daher durch die Funktionen $v_n(x) := \sin nx$ für $n \in \mathbb{N}$ gegeben. Für die Gleichung $\ddot{w} + c^2 \lambda w = 0$ erhält man die Lösungen $w_n(t) := d_n \cos cnt + e_n \sin cnt$ mit Konstanten $d_n, e_n \in \mathbb{R}$, womit wir die Lösungsbasis
$$ u_n(x, t) := v_n(x)w_n(t) = \sin nx (d_n \cos cnt + e_n \sin cnt) \quad \forall n \in \mathbb{N} $$
erhalten. Derartige Funktionen $u_n$ erfüllen die Wellengleichung mit Einspannbedingungen — es fehlen aber noch die Anfangsbedingungen.

c) Machen wir nun die Separation rückgängig, indem wir eine Superposition $u \equiv \sum_{n=1}^{\infty} u_n$ der Funktionen aus (2) vornehmen, so ergibt sich gerade die Darstellung $(*)$ aus der Aufgabenstellung. Wir müssen noch die $d_n$ und $e_n$ so bestimmen, dass auch die Anfangsbedingungen erfüllt sind. Die Anfangsbedingungen lauten
$$ u(x, 0) = \sum_{n=1}^{\infty} d_n \sin nx = g(x), \quad \partial_t u(x, 0) = \sum_{n=1}^{\infty} c n e_n \sin nx = h(x) $$
für $x \in [0, \pi]$. Wir setzen nun $g$ und $h$ gemäß $g(-x) := -g(x)$ und $h(-x) := -h(x)$ für $x \in [0, \pi)$ zu ungeraden Funktionen der Periode $2\pi$ fort, denn dann handelt es sich bei obigen Reihen gerade um die Fourier-Reihen von $g$ und $h$, so dass sich die Koeffizienten $d_n$ und $c n e_n$ also als Fourier-Koeffizienten bestimmen lassen: In der Darstellung von $g(x)$ und $h(x)$ als Fourierreihe sind jeweils die $a_n = 0$. Für $g(x)$ ist $b_n = d_n$ und für $h(x)$ ist $b_n = c n e_n$. Insgesamt ergibt sich mit den Symmetrieformeln für die Fourier-Koeffizienten $b_n$:
$$ d_n = \frac{2}{\pi} \int_0^\pi g(x) \sin nx dx, \quad e_n = \frac{2}{cn\pi} \int_0^\pi h(x) \sin nx dx $$
Damit ist das Problem der schwingenden Saite gelöst.
***
[^2]
## Hausaufgaben (bis 10.11. - 12.11.):
### Aufgabe H 4.1: (Dreifacher Tiefpass)
Es sei $L[y] \equiv (\alpha \frac{d}{dt} + 1)^3 y(t) = x(t)$ mit $\alpha = RC > 0$ und $2\pi$-periodischer Eingangsspannung $x$ gegeben. Berechnen Sie
a) den zugehörigen Frequenzgang $(d_k)_{k \in \mathbb{Z}}$,
b) die Fourier-Reihe der $2\pi$-periodischen Impulsantwort $h_{2\pi}$,
c) die Fourier-Reihe der „Antwort“ $y$, wenn $x(t) = t$ für $t \in [0, 2\pi)$ gilt.
?

***
[^3]
### Aufgabe H 4.2: (Die Faltung)
Gegeben sei die $2\pi$-periodische Funktion $f$ mit $f(x) := x^2$ für $-\pi \leq x \leq \pi$.
a) Skizzieren Sie den Graphen von $f$ für $-3\pi \leq x \leq 3\pi$.
b) Begründen Sie ohne Rechnung, dass die Fourierreihe von $f$ eine Cosinusreihe ist.
c) Bestimmen Sie explizit die periodische Faltung $(f * f)(x)$ für $0 \leq x \leq \pi$.
?

***
[^4]
### Aufgabe H 4.3: (Die angeschlagene Saite)
Betrachtet werden im Setting der Aufgabe Z 4.2 für ein festes $\varepsilon \in [0, \pi]$ die Anfangsbedingungen
$g \equiv 0$ und
$$ h(x) = \begin{cases} 1 & \text{für } x \in \left[ \frac{\pi-\varepsilon}{2}, \frac{\pi+\varepsilon}{2} \right] \\ 0 & \text{für } x \in \left[0, \frac{\pi-\varepsilon}{2}\right) \cup \left(\frac{\pi+\varepsilon}{2}, \pi \right] \end{cases} $$
Stellen Sie die Schwingung $u(x, t)$ der angeschlagenen Klaviersaite als Reihe dar. Rechnen Sie dabei $u(x, t)$ soweit aus, dass keine Integrale mehr vorkommen.
?

***
[^5]
### Aufgabe H 4.4: (Rechenregeln für Faltungen)
Bestätigen Sie die Formeln
a)
$$ \left( \sum_{k=1}^{\infty} b_k \sin kt \right) * \left( \sum_{k=1}^{\infty} \beta_k \sin kt \right) = - \frac{1}{2} \sum_{k=1}^{\infty} b_k \beta_k \cos kt $$
b)
$$ \left( \frac{a_0}{2} + \sum_{k=1}^{\infty} a_k \cos kt \right) * \left( \frac{\alpha_0}{2} + \sum_{k=1}^{\infty} \alpha_k \cos kt \right) = \frac{a_0 \alpha_0}{4} + \frac{1}{2} \sum_{k=1}^{\infty} a_k \alpha_k \cos kt $$
?

***
[^6]
## Ergänzende Hausaufgaben:
### Aufgabe E 4.1: (E-Test-Aufgaben in Moodle)
Ab dem 5.11. ist der erste E-Test mit ergänzenden Aufgaben zu den Unterkapiteln 1.1 bis 1.6 des Kapitels Fourierreihen in Moodle verfügbar. Darin finden Sie einige Aufgaben, deren Schwerpunkt auf dem Verständnis des Stoffes liegen und die viele gelernte Dinge dieses Kapitels überprüfen. Auch einige ehemalige Klausuraufgaben sind hier enthalten. Sie haben Zeit diese Aufgaben bis Montag, 17.11., 22:00 Uhr zu lösen. Die Aufgaben können dabei in beliebiger Reihenfolge bearbeitet werden, da man Fragen überspringen kann. Zudem kann die Bearbeitung auch unterbrochen und zu einem späteren Zeitpunkt fortgesetzt werden. Bitte beachten Sie in diesem Zusammenhang auch die Probeklausur-Challenge (Details siehe Moodle).
?

***
[^7]
### Aufgabe E 4.2: (Ein weiteres LTI-System)
Gegeben sei die Differentialgleichung eines LTI-Systems
$-2y''(t) + 5y(t) = x(t)$ mit $t \in \mathbb{R}$,
wobei $x(t)$ das $2\pi$-periodische Eingangssignal und $y(t)$ die Ausgangsgröße ist.
a) Bestimmen Sie die Fourierkoeffizienten $d_k$ der $2\pi$-periodischen Impulsantwort $h(t)$.
b) Sei nun das Eingangssignal $x(t)$ die $2\pi$-periodische Funktion
$$ x(t) = \frac{1}{2} + \sum_{k=1}^{\infty} \left( \frac{4}{k^2} \cos(kt) + \frac{6}{k^2} \sin(kt) \right) $$
Bestimmen Sie die Fourierreihe $S_y$ des Ausgangssignals $y(t)$.
?

***
[^8]
### Aufgabe E 4.3: (Rechenregeln, alte Klausuraufgabe)

Kennzeichnen Sie jeweils die richtigen Antworten und geben Sie jeweils eine kurze Begründung an. Alle zutreffenden Möglichkeiten sind anzukreuzen!
a) Gegeben seien die $C^2$-Funktion $f(t) := \sum_{k=1}^{\infty} \frac{1}{k^4} \sin (k\pi t)$ sowie $g_1(t) \equiv s\left( \frac{2\pi t}{5} \right)$, wobei die Sägezahnfunktion $s$ bekanntlich die Fourierreihe $S_s(t) = \sum_{k \neq 0} \frac{1}{2ik} e^{ikt}$ besitzt. Welche Periode bzw. Kreisfrequenz weist $f - 3g_1$ auf?
  $T = 10$, $T = 1$, $\omega = 2\pi$, $\omega = \frac{\pi}{5}$.
b) Nun habe $g_2(t) \equiv s\left(\frac{t}{\pi}\right)$ die Periode von $f$. Welche Koeffizienten stehen in der Cosinus-Reihe $\sum_{k=1}^{\infty} a_k \cos(k\pi t)$ der periodischen Faltung $f'' * g_2$?
  $a_k = \frac{i\pi}{k^2}$, $a_k = \frac{\pi^2}{2k^3}$, $a_k = -\frac{1}{k^3}$, $a_k = \frac{1}{2k^4}$, $a_k = \frac{\pi^2}{k^4}$.
c) Entscheiden Sie, welche Koeffizienten in der Fourierreihe der Funktion $\cos(t + \beta) - \sin(t - \beta)$ mit $\beta \in (0, 2\pi)$ auftreten:
  $c_1 = e^{i\beta}$, $c_1 = \frac{e^{i\beta} + ie^{-i\beta}}{2}$, $c_{-1} = \frac{e^{-i\beta} - ie^{i\beta}}{2}$, $c_0 = 1$.
d) Es sei $h : \mathbb{R} \to \mathbb{R}$ die 3-periodische Funktion mit $h(t) := e^{-2t} \cos \frac{\pi t}{2}$ für $t \in [0, 3)$. Entscheiden Sie, in welchen Intervallen $S_h(t) = h(t)$ gilt:
  $t \in \mathbb{R}$, $t \in [0, 3)$, $t \in (0, 3)$, $t \in [7, 9)$.
?

***
[^9]
### Aufgabe E 4.4: (Faltung mit Sägezahn)
Es sei $s : \mathbb{R} \to \mathbb{R}$ mit $s(t) := \frac{\pi-t}{2}$ für $t \in [0, 2\pi)$ die $2\pi$-periodisch fortgesetzte Sägezahnfunktion, das Fundamentalbeispiel der Vorlesung.
a) Zeigen Sie, dass die periodische Faltung $f * g$ $T$-periodisch ist, wenn $f$ und $g$ es sind. Berechnen Sie die periodische Faltung
$$ (s * s)(t) := \frac{1}{2\pi} \int_0^{2\pi} s(t - \tau)s(\tau) d\tau $$
für $t \in \mathbb{R}$ direkt.
b) Welcher Zusammenhang besteht zwischen den Fourier-Koeffizienten $c_k$ von $s$ und den Fourier-Koeffizienten $d_k$ von $s * s$? Welcher Zusammenhang besteht zwischen $s$ und $s * s$?
?

***
[^10]
# Referenz
## Verknüpfung
### Z 3.1
- [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Impulsantwort]]
- [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Gleichung 1.22]]
- [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Frequenzgang]]
- [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Differentialoperator]]
- [[202510260310 - Charakteristisches Polynom und Fouriertransformierte|Charakteristischen Polynom]]
### Z 3.2
- [[202511021011 - Die Wellengleichung|Die Wellengleichung]]
- [[Vorlesung204320-20Teil20220-20Systeme20linearer20Differentialgleichungen201.20Ordnung.mp4]]
- [[Fourierkoeffizient]]
### Z 3.3
### H 4.1
- [[202510201810 - Lineare zeitinvariante Übertragungssysteme|Frequenzgang]]
## Quellen
- [[tum_analysis3_Blatt04.pdf]]
- [[tum_analysis3_ZÜ04.pdf]]
- [[tum_analysis3_Blatt04_ZÜ_lsg.pdf]]

[^1]: [[tum_analysis3_Blatt04_ZÜ_lsg.pdf#page=1]]

[^2]: [[tum_analysis3_Blatt04_ZÜ_lsg.pdf#page=2]]

[^3]: [[tum_analysis3_Blatt04.pdf#page=2]]

[^4]: [[tum_analysis3_Blatt04.pdf#page=2]]

[^5]: [[tum_analysis3_Blatt04.pdf#page=2]]

[^6]: [[tum_analysis3_Blatt04.pdf#page=2]]

[^7]: [[tum_analysis3_Blatt04.pdf#page=3]]

[^8]: [[tum_analysis3_Blatt04.pdf#page=3]]

[^9]: [[tum_analysis3_Blatt04.pdf#page=3]]

[^10]: [[tum_analysis3_Blatt04.pdf#page=4]]



