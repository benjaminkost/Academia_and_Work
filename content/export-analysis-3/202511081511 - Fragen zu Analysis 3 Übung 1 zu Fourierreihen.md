---
"created date:": 27.10.2025 09:39
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[fragen]]"
  - "[[Fourierreihe]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Fragen zu Übung 1
parent:
siblings:
child:
exercise: "[[Analysis 3 - Übung 1]]"
---
# Betroffene Notes
```dataview
LIST 
FROM "6 - Atomic Notes"
WHERE contains(this.file.outlinks, file.link)
SORT file.ctime ASC
```
# Fragen
## Aufgabe H 1.1
 > [!question]- wie verändert sich die Periode wenn man eine Funktion substituiert
 
 > [!question]- Woher kommt das $i$ bzw. das Minus beim zweiten Summanden
## Aufgabe H 1.2
#### a)
> [!question]- Welche der Teilfunktionen nutzt man um die Koeffizienten zu bestimmen
> Alle man teilt einfach das Integral in die einzelnen Intervalle

> [!question]- Wie bekommt man diese Umformung: $c_0 = \frac{1}{2\pi} \int_{-\pi}^{\pi} f(t) dt = \frac{1}{2\pi} \int_{0}^{\pi} t dt$
> Die Umformung $c_0 = \frac{1}{2\pi} \int_{-\pi}^{\pi} f(t) dt = \frac{1}{2\pi} \int_{0}^{\pi} t dt$ ergibt sich aus der stückweisen Definition der Funktion $f(t)$ aus der Aufgabe H 1.2 in der Notiz [[Analysis 3 - Übung 1]].
> 
> Die Funktion ist dort wie folgt definiert:
> $$f(t) := \begin{cases} 0 & \text{für } t \in (-\pi, 0) \\ t & \text{für } t \in [0, \pi) \\ \frac{\pi}{2} & \text{für } t = \pi \end{cases}$$
> 
> Um das Integral für $c_0$ zu berechnen, teilt man es entsprechend der Definition von $f(t)$ auf:
> $$ c_0 = \frac{1}{2\pi} \int_{-\pi}^{\pi} f(t) dt = \frac{1}{2\pi} \left( \int_{-\pi}^{0} f(t) dt + \int_{0}^{\pi} f(t) dt \right) $$
> 
> Jetzt setzt man die jeweiligen Funktionswerte für die Intervalle ein:
> *   Im Intervall $(-\pi, 0)$ ist $f(t) = 0$.
> *   Im Intervall $[0, \pi)$ ist $f(t) = t$.
> 
> Dadurch vereinfacht sich der Ausdruck:
> $$ c_0 = \frac{1}{2\pi} \left( \int_{-\pi}^{0} 0 \ dt + \int_{0}^{\pi} t \ dt \right) $$
> 
> Da das erste Integral $\int_{-\pi}^{0} 0 \ dt$ gleich $0$ ist, bleibt nur der zweite Teil übrig:
> $$ c_0 = \frac{1}{2\pi} \left( 0 + \int_{0}^{\pi} t \ dt \right) = \frac{1}{2\pi} \int_{0}^{\pi} t \ dt $$
> 
> Das ist genau die Umformung aus deiner Frage.

> [!question]- Warum ist $e^{-i\pi k}=(-1)^k$
> [[Euler-Formel]]
#### c)
> [!question]- Wie kommt man auch diesen Lösungsansatz der Argumentation

## Aufgabe H 1.3
#### c)
> [!question]- Wie geht man mit dem Verschieben der Integralgrenzen um
> Die Aussage, dass der $k$-te Fourierkoeffizient über $c_k = \frac{1}{T} \int_{-T/2}^{T/2} f(t)e^{-ik\omega t}dt$ berechnet werden kann, ist korrekt und beruht auf einer fundamentalen Eigenschaft periodischer Funktionen.
>
> Der Kernpunkt ist: **Das Integral einer $T$-periodischen Funktion über ein beliebiges Intervall der Länge $T$ ist immer dasselbe.**
>
> Hier die detaillierte Begründung:
>
> 1.  **Periodizität des Integranden:**
>     Betrachten wir den Integranden in der Formel für den Fourierkoeffizienten: $g(t) = f(t)e^{-ik\omega t}$.
>     *   Die Funktion $f(t)$ ist per Definition $T$-periodisch. Das bedeutet $f(t+T) = f(t)$ für alle $t \in \mathbb{R}$.
>     *   Der Exponentialterm $e^{-ik\omega t}$ ist ebenfalls $T$-periodisch. Das können wir zeigen, indem wir $\omega = \frac{2\pi}{T}$ einsetzen:
>         $e^{-ik\omega (t+T)} = e^{-ik\frac{2\pi}{T}(t+T)} = e^{-ik\frac{2\pi}{T}t - ik\frac{2\pi}{T}T} = e^{-ik\omega t} \cdot e^{-ik2\pi}$.
>         Da $k$ eine ganze Zahl ist, ist $e^{-ik2\pi} = \cos(-2\pi k) + i\sin(-2\pi k) = 1 + 0i = 1$.
>         Somit ist $e^{-ik\omega (t+T)} = e^{-ik\omega t} \cdot 1 = e^{-ik\omega t}$.
>     *   Da sowohl $f(t)$ als auch $e^{-ik\omega t}$ $T$-periodisch sind, ist auch ihr Produkt $g(t) = f(t)e^{-ik\omega t}$ eine $T$-periodische Funktion.
>
> 2.  **Integral über eine Periode:**
>     Für jede $T$-periodische Funktion $g(t)$ gilt:
>     $ \int_{a}^{a+T} g(t) dt = \int_{0}^{T} g(t) dt $
>     Das bedeutet, es ist egal, wo du das Integrationsintervall der Länge $T$ beginnst. Ob du von $0$ bis $T$, von $-\pi$ bis $\pi$ (wenn $T=2\pi$), von $T/2$ bis $3T/2$, oder eben von $-T/2$ bis $T/2$ integrierst – das Ergebnis ist dasselbe.
>
>     **Anschauliche Erklärung:** Stell dir den Graphen einer periodischen Funktion vor. Das Integral entspricht der Fläche unter der Kurve. Wenn du das Integrationsintervall um eine ganze Periode verschiebst, verschiebst du die "Fenster" der Betrachtung, aber die Form der Funktion innerhalb dieses Fensters bleibt aufgrund der Periodizität identisch. Die Fläche unter der Kurve über eine volle Periode ändert sich daher nicht.
>
> 3.  **Anwendung auf Fourierkoeffizienten:**
>     Die Standarddefinition des Fourierkoeffizienten ist oft gegeben als:
>     $ c_k = \frac{1}{T} \int_{0}^{T} f(t)e^{-ik\omega t}dt $
>     Aufgrund der oben erklärten Eigenschaft der Periodizität des Integranden kann dieses Integral über jedes beliebige Intervall der Länge $T$ berechnet werden. Das Intervall $[-T/2, T/2]$ ist dabei eine häufig gewählte Konvention, da es symmetrisch um den Nullpunkt liegt. Dies kann besonders vorteilhaft sein, wenn man Symmetrieeigenschaften der Funktion $f(t)$ (gerade oder ungerade) ausnutzen möchte, da sich Integrale über symmetrische Intervalle dann oft vereinfachen lassen.
>
> Zusammenfassend lässt sich sagen, dass die Verschiebung der Integrationsgrenzen von $[0, T]$ zu $[-T/2, T/2]$ (oder jedem anderen Intervall der Länge $T$) mathematisch gültig ist, weil der gesamte Integrand $T$-periodisch ist und das Integral einer periodischen Funktion über eine volle Periode unabhängig vom Startpunkt des Intervalls ist.

#### d)
> [!question]- Wie können Fourierpolynome stetig sein aber Fourierreihen, dann nicht mehr?
>
> Diese Frage beleuchtet einen wichtigen Unterschied zwischen endlichen Summen (Fourierpolynome) und unendlichen Reihen (Fourierreihen) in der Analysis. Die Notiz [[Analysis 3 - Übung 1]] spricht dies auch in Aufgabe H 1.3 d) an.
>
> Hier ist die Erklärung:
>
> 1.  **Fourierpolynome (Partialsummen der Fourierreihe) sind immer stetig:**
>     *   Ein Fourierpolynom $S_n f(t) = \sum_{k=-n}^{n} c_k e^{ik\omega t}$ ist eine **endliche Summe** von Funktionen.
>     *   Jeder einzelne Term $e^{ik\omega t}$ (oder äquivalent $\cos(k\omega t)$ und $\sin(k\omega t)$ in der reellen Darstellung) ist eine **stetige Funktion**.
>     *   Ein grundlegender Satz der Analysis besagt, dass die **Summe einer endlichen Anzahl stetiger Funktionen immer stetig ist**.
>     *   Daher sind die Fourierpolynome, egal wie viele Terme $n$ sie enthalten, stets stetige Funktionen. Sie sind "glatt" und haben keine Sprünge.
>
> 2.  **Die Fourierreihe (unendliche Summe) kann unstetig sein:**
>     *   Die Fourierreihe $S_f(t) = \sum_{k=-\infty}^{\infty} c_k e^{ik\omega t}$ ist eine **unendliche Summe** von Funktionen.
>     *   Im Gegensatz zu endlichen Summen ist die Stetigkeit einer unendlichen Summe stetiger Funktionen **nicht automatisch gegeben**.
>     *   Damit eine unendliche Reihe stetiger Funktionen wieder eine stetige Funktion ergibt, muss die Reihe **gleichmäßig konvergieren**.
>     *   Wenn die ursprüngliche Funktion $f(t)$, deren Fourierreihe wir betrachten, selbst **Unstetigkeiten** (z.B. Sprungstellen) aufweist, dann kann die Fourierreihe an diesen Stellen nicht gleichmäßig konvergieren. Stattdessen konvergiert sie dort in der Regel punktweise gegen den Mittelwert der links- und rechtsseitigen Grenzwerte der Funktion $f(t)$ (gemäß dem Dirichlet-Kriterium, wie in [[Konvergenz von Fourierreihen|Theorem 1.1.21]] angedeutet).
>     *   Da die Fourierreihe an den Unstetigkeitsstellen der ursprünglichen Funktion selbst Sprünge aufweist (oder zumindest nicht stetig ist), ist sie als Ganzes nicht stetig.
>
> **Zusammenfassend:**
> Die Fourierpolynome sind endliche Summen stetiger Funktionen und daher immer stetig. Die Fourierreihe ist eine unendliche Summe. Wenn die Funktion, die durch die Fourierreihe dargestellt wird, selbst unstetig ist, kann die Fourierreihe an diesen Stellen nicht gleichmäßig konvergieren und ist daher auch nicht stetig. Ein klassisches Beispiel dafür ist die [[Sägezahnkurve]], die in Aufgabe H 1.3 d) als Gegenbeispiel für die Stetigkeit einer Fourierreihe genannt wird. Ihre Partialsummen sind stetig, aber die vollständige Reihe hat Sprünge.
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


