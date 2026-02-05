---
"created date:": 22.09.2025 11:57
mytags:
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[komplexe fourieranalyse]]"
  - "[[reelle fourieranalyse]]"
  - "[[Fourierreihe]]"
tags:
  - aufgaben
  - 3-Semester
  - 1-Semester
  - baby
  - flashcards
  - todo
  - "#Analysis3"
  - "#Analysis3/Fourierreihe"
  - vl-2
  - grundlagen
aliases:
parent:
siblings:
child:
questions: "[[202511081511 - Fragen zu Analysis 3 Übung 1 zu Fourierreihen|Fragen zu Übung 1]]"
---
# Zentralübungen (15.10.)
## Aufgabe Z 1.1: (Trigonometrische Polynome)
a) Ist die folgende Funktion ein trigonometrische Polynom: $f(t) = \sin(t + 5)$
?
Für $f$ können wir das Additionstheorem nutzen. Es ist $sin(x + y) = sin(x) cos(y) + cos(x) sin(y)$. Also gilt $f(t) = sin(t) cos(5) + cos(t) sin(5)$. Mithilfe der Euler-Formel kann man die Sinus- und Kosinusterme durch die komplexe Exponentialfunktion ausdrücken, also $sin(t) = \frac{1}{2i} \cdot (e^{it} - e^{-it})$ und $cos(t) = \frac{1}{2} \cdot (e^{it} + e^{-it})$. Damit bekommt man $f(t) = \left( \frac{cos(5)}{2i} + \frac{sin(5)}{2} \right) \cdot e^{it} + \left( \frac{sin(5)}{2} - \frac{cos(5)}{2i} \right) \cdot e^{-it}$, und das ist offensichtlich ein trigonometrisches Polynom.
<!--SR:!2025-10-28,1,230-->
***
[^1]
b) Ist die folgende Funktion ein trigonometrische Polynom:  $g(t) = \sin^2(t) \cdot \cos(2t) + \sin^3(-t) \cdot e^{2it}$
?
Für die Funktion $g$ machen wir zuerst eine Vorüberlegung: Wenn man zwei trigonometrische Polynome mit der gleichen Kreisfrequenz $\omega$ addiert oder multipliziert, bekommt man wieder ein trigonometrisches Polynom (auch mit der Kreisfrequenz $\omega$). Das folgt daraus, dass ein trigonometrisches Polynom $s_n(t)$ (per Definition) immer die Form $s_n(t) = \sum_{k=-n}^{n} c_k e^{ik\omega t}$ hat. Addiert oder multipliziert man jetzt zwei verschiedene trigonometrische Polynome, so kommen wieder Summen von endlich vielen $e^{ik\omega t}$-Termen mit entsprechenden Koeffizienten $c_k$ heraus, wodurch man ein trigonometrisches Polynom erhält. Bei der Summe ist dies recht offensichtlich, beim Produkt schauen wir uns das genauer an: Sind $s_n(t) = \sum_{k=-n}^{n} c_k e^{ik\omega t}$ und $\tilde{s}_m(t) = \sum_{k=-m}^{m} d_k e^{ik\omega t}$ jeweils trigonometrische Polynome, so ist $s_n(t) \cdot \tilde{s}_m(t) = \sum_{k=-(m+n)}^{m+n} f_k e^{ik\omega t}$ mit geeigneten neuen Koeffizienten $f_k$. Beispielsweise ist $a e^{il\omega t} \cdot b e^{ip\omega t} = ab e^{il\omega t + ip\omega t} = ab e^{i(l+p)\omega t}$. Insbesondere ist die Summe endlich, so dass wir ein trigonometrisches Polynom haben. Damit können wir jetzt entscheiden, ob $g$ ein trigonometrisches Polynom ist: Da $\sin(t)$, $\cos(2t)$ und $e^{2it}$ jeweils trigonometrische Polynome mit Kreisfrequenz $\omega = 1$ sind, ist also $g(t) = (\sin(t) \cdot \sin(t)) \cdot \cos(2t) - ((\sin(t) \cdot \sin(t)) \cdot \sin(t)) \cdot e^{2it}$ auch ein trigonometrisches Polynom mit Kreisfrequenz $\omega = 1$. Hier haben wir benutzt, dass $\sin(t)$ eine ungerade Funktion ist, also dass gilt $\sin(-t) = - \sin(t)$.
***
[^2]

c) Ist die folgende Funktion ein trigonometrische Polynom:  $h(t) = \cos^3(t) + \sin^2(t) \cdot e^{2t}$
?
Die Funktion $h$ ist kein trigonometrisches Polynom: Da $e^{2t}$ wegen des 'fehlenden' $i$ nicht periodisch ist, ist $h$ nicht periodisch. Also lässt sich diese Funktion nicht als endliche Linearkombination von $e^{ik\omega t}$-Termen darstellen.
***
[^3]

d) Ist die folgende Funktion ein trigonometrische Polynom:  $s(t) = \sum_{k=-\infty, k \neq 0}^{\infty} \frac{1}{2ik} e^{ikt}$
?
Diese Funktion ist die sogenannte Sägezahnfunktion. Sie ist kein trigonometrisches Polynom, da sie unendliche viele trigonometrische Summanden hat. Man kann das auch daran erkennen, dass die Sägezahnfunktion unstetig ist, aber jedes trigonometrische Polynom stetig ist. Details dazu werden im Laufe der nächsten Vorlesungen besprochen.
***
[^4]
## Aufgabe Z 1.2: (Kleinste Periode)
a) Bestimmen Sie die kleinste Periode der Funktion. Ist die Funktion gerade oder ungerade: $f: \mathbb{R} \to \mathbb{R}$, $f(t) = \cos\left(\frac{7\pi}{2} t\right)$
?
Wir untersuchen zunächst die Funktion $f$. Gesucht ist die kleinste Zahl $T > 0$, sodass $f(t + T) = f(t)$ für alle $t \in \mathbb{R}$ gilt. Wir berechnen für $t \in \mathbb{R}$:
$f(t + T) = \cos\left( \frac{7\pi}{2} (t + T) \right) = \cos\left( \frac{7\pi}{2} t + \frac{7\pi}{2} T \right)$.
Die kleinste Periode von $\cos$ ist $2\pi$. Daher muss $\frac{7\pi}{2} T = 2\pi$ gelten und wir erhalten $T = \frac{4}{7}$.
Wegen $f(-t) = \cos\left(- \frac{7\pi}{2} t\right) = \cos\left( \frac{7\pi}{2} t\right) = f(t)$ ist $f$ gerade.
***
[^5]

b) Bestimmen Sie die kleinste Periode der Funktion. Ist die Funktion gerade oder ungerade: $g: \mathbb{R} \to \mathbb{R}$, $g(t) = \sin(13t)$
?
Für die Funktion $g$ gehen wir ähnlich vor. Auch $\sin$ ist $2\pi$-periodisch. Daher erhalten wir aus der Rechnung $g(t + T) = \sin(13 \cdot (t + T)) = \sin(13t + 13T)$ die Gleichung $13T = 2\pi$, also $T = \frac{2\pi}{13}$. Wegen $g(-t) = \sin(-13t) = - \sin(13t) = -g(t)$ ist die Funktion $g$ ungerade.
***
[^6]

c) Bestimmen Sie die kleinste Periode der Funktion. Ist die Funktion gerade oder ungerade: $h: \mathbb{R} \to \mathbb{R}$, $h(t) = \sin(2t) \cos(2t)$. 
?
Die direkte Berechnung von Perioden von Produkten von Funktionen ist schwierig. Daher benutzen wir Additionstheoreme und erhalten $h(t) = \sin(2 \cdot t) \cos(2 \cdot t) = \frac{1}{2} \sin(2 \cdot 2 \cdot t) = \frac{1}{2} \sin(4t)$. Wie für $g$ berechnet man nun $T = \frac{\pi}{2}$ und sieht, dass $h$ ungerade ist. Alternativ kann man auch direkt anhand der Produktdarstellung von $h$ sehen, dass die Funktion ungerade ist, denn: $h(-t) = \sin(-2t) \cos(-2t) = (-\sin(2t)) \cos(2t) = -h(t)$. In der Tat ist das Produkt einer geraden und einer ungeraden Funktion immer ungerade.
***
[^7]
# Hausaufgaben (bis 20.10. - 22.10.)
## Aufgabe H 1.1: (Berechnung einer Fourierreihe)
Bestimmen Sie die Fourierkoeffizienten der $2\pi$-periodischen Funktion $f : \mathbb{R} \to \mathbb{R}$, welche auf $[0, 2\pi)$ definiert ist als $f(t) := (t − \pi)^2$ für $t \in [0, 2\pi)$.
Wie lautet die Fourierreihe?
*Tipp: Berechnen Sie die Fourierkoeffizienten mit Hilfe der Definition aus der Vorlesung.*
?
Die Fourierkoeffizienten von $f$ sind wegen $T = 2\pi$ und $\omega = \frac{2\pi}{T} = 1$:
$$ c_k = \frac{1}{2\pi} \int_{0}^{2\pi} f(t)e^{-ikt} dt $$
Für $k = 0$ ergibt sich mit der Substitution $x := t - \pi$ und aus Symmetriegründen der Koeffizient $c_0$ zu:
$$ c_0 = \frac{1}{2\pi} \int_{0}^{2\pi} (t - \pi)^2 dt = \frac{1}{\pi} \int_{0}^{\pi} x^2 dx = \frac{\pi^2}{3} $$
Für alle $k \neq 0$ ermitteln wir eine Stammfunktion für den Integranden mit Hilfe der Formelsammlung (alternativ geht auch partielle Integration) und erhalten wieder unter Nutzung der Symmetrie:
$$ c_k = \frac{1}{2\pi} \int_{0}^{2\pi} (t - \pi)^2e^{-ikt} dt = \frac{1}{2\pi} \left[ \frac{ie^{-ikt}(k^2(t - \pi)^2 + 2ik(\pi - t) - 2)}{k^3} \right]_{t=0}^{2\pi} = \frac{2}{k^2} $$
Damit ergibt sich die Fourierreihe $S_f$ von $f$ zu:
$$ S_f(t) = \frac{\pi^2}{3} + 2 \sum_{k \in \mathbb{Z} \setminus \{0\}} \frac{e^{ikt}}{k^2} \quad \forall t \in \mathbb{R} $$
***
[^8]
## Aufgabe H 1.2: (Fourierreihen)
Wir betrachten die mittels
$$f(t) := \begin{cases} 0 & \text{für } t \in (-\pi, 0) \\ t & \text{für } t \in [0, \pi) \\ \frac{\pi}{2} & \text{für } t = \pi \end{cases}$$
erklärte $2\pi$-periodische Funktion.
a) Bestimmen Sie die Fourierkoeffizienten von $f$.
b) Konvergiert die Fourierreihe von $f$ punktweise gegen $f$? Wenn ja, gegen welchen Wert?
c) Ist die Fourierreihe von $f$ gleichmäßig konvergent?
*Hinweis: Sie dürfen in dieser Aufgabe bereits [[Konvergenz von Fourierreihen|Theorem 1.1.21]] benutzen.*
?
a) Es ist $c_0 = \frac{1}{2\pi} \int_{-\pi}^{\pi} f(t) dt = \frac{1}{2\pi} \int_{0}^{\pi} t dt = \frac{1}{2\pi} \cdot \frac{1}{2} t^2 \Big|_{0}^{\pi} = \frac{\pi}{4}$ und für $k \neq 0$ ergibt sich
$c_k = \frac{1}{2\pi} \int_{-\pi}^{\pi} f(t) e^{-ikt} dt = \frac{1}{2\pi} \int_{0}^{\pi} t e^{-ikt} dt$
$= \frac{1}{2\pi} \left[ \frac{1}{-ik} t e^{-ikt} \Big|_{0}^{\pi} - \int_{0}^{\pi} \frac{1}{-ik} e^{-ikt} dt \right]$
$= \frac{1}{2\pi} \left( \frac{1}{-ik} \pi e^{-ik\pi} + \frac{1}{k^2} e^{-ikt} \Big|_{0}^{\pi} \right)$
$= \frac{1}{2\pi} \left( \frac{1}{-ik} \pi \cdot (-1)^k + \frac{1}{k^2} ((-1)^k - 1) \right)$
$= \begin{cases} - \frac{1}{2ik} & \text{falls } k \text{ gerade,} \\ \frac{1}{2ik} - \frac{1}{\pi k^2} & \text{falls } k \text{ ungerade.} \end{cases}$
Interessanterweise ist in die Berechnung nicht eingeflossen, welchen konkreten Wert $f$ an der Stelle $t = \pi$ hat. Einzelne Funktionswerte haben keinen Einfluss auf die Fourierkoeffizienten.

b) Da die Funktion $f$ stückweise stetig differenzierbar ist, konvergiert die Fourierreihe von $f$ nach [[Konvergenz von Fourierreihen|Theorem 1.1.21]] punktweise, $\lim_{n\to\infty}(S_n f)(t) = \frac{f(t-) + f(t+)}{2}$. Man kann hier zudem überprüfen, dass $f(t) = \frac{f(t-) + f(t+)}{2}$ gilt. Das sieht man für $t \in (-\pi, \pi)$ recht schnell, da $f$ hier stetig ist, aber auch in der Sprungstelle $t = \pi$ ist dies erfüllt. Die Fourierreihe von $f$ konvergiert also punktweise gegen $f$.

c) Da die Funktion $f$ stückweise stetig differenzierbar ist, konvergiert ihre Fourierreihe in jedem abgeschlossenen Intervall, das keine Unstetigkeitsstelle von $f$ enthält, gleichmäßig gegen $f$. Die [[Komplexe Fourierpolynome|Partialsummen der Fourierreihe]], das sind die Summen $S_n f(t) = \sum_{k=-n}^{n} c_k e^{ikt}$, sind [[Trigonometrische Polynome]] und insbesondere stetig. Daher konvergiert die Fourierreihe von $f$ nicht gleichmäßig auf ganz $\mathbb{R}$ gegen $f$. Denn der Grenzwert einer gleichmäßig konvergenten Folge stetiger Funktionen ist stetig, $f$ aber nicht.
***
[^9]
## Aufgabe H 1.3: (Grundlegende Dinge bei Fourierreihen)
Entscheiden Sie über den Wahrheitsgehalt der folgenden Behauptungen. Geben Sie jeweils eine kurze Begründung an.

|     | wahr | falsch | Behauptung                                                                                                                                                                                                  |
| :-- | :--- | :----- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| a)  |      |        | Die Funktion $f : \mathbb{R} \to \mathbb{R}$ gegeben durch $f(t) := \sin (4t)$ ist $\frac{3\pi}{2}$-periodisch.                                                                                             |
| b)  |      |        | Für die $2\pi$-periodische Funktion $f : \mathbb{R} \to \mathbb{C}$, $f(t) := e^{-it} + \frac{3}{2} e^{4it}$ mit Fourierreihe $S_f$ gilt: $f(t) = S_f(t)$ für alle $t \in \mathbb{R}$.                      |
| c)  |      |        | Für eine $T$-periodische Funktion $f : \mathbb{R} \to \mathbb{C}$ lässt sich der $k$-te Fourierkoeffizient über $c_k = \frac{1}{T} \int_{-T/2}^{T/2} f(t)e^{-ik\omega t}dt$ berechnen.                      |
| d)  |      |        | Für eine $T$-periodische Funktion $f : \mathbb{R} \to \mathbb{C}$ ist die Fourier-Reihe $S_f(t)$ stetig.                                                                                                    |
| e)  |      |        | Die Funktion $f : \mathbb{R} \to \mathbb{R}$ gegeben durch $f(t) := \sin^2(t)$ besitzt die Fourierreihe $S_f(t)$ zur Periode $\pi$ mit $S_f(t) = \frac{1}{2} + \frac{1}{4} e^{-2it} + \frac{1}{4} e^{2it}$. |
| f)  |      |        | Die Stammfunktion $F : \mathbb{R} \to \mathbb{R}$, $F(t) := \int_0^t f(\tau) d\tau$ der $\pi$-periodischen Funktion $f : \mathbb{R} \to \mathbb{R}$, $f(\tau) := \sin^2(\tau)$ ist $\pi$-periodisch.        |
| g)  |      |        | Es sei $f : \mathbb{R} \to \mathbb{R}$ mit $f(t) := 2 \cos(-t + 2) + 3 \sin (-\frac{2}{9} t + 9)$. Die zur kleinsten Periode von $f$ zugehörige Kreisfrequenz ist $\omega = \frac{1}{9}$.                   |
?
a) Die Behauptung ist wahr: Für alle $t \in \mathbb{R}$ gilt $f(t + \frac{3\pi}{2}) = \sin(4t + 6\pi) = \sin(4t) = f(t)$.

b) Die Behauptung ist wahr: $f$ definiert ein trigonometrisches Polynom. Gemäß der Vorlesung gilt damit die Behauptung, denn jedes trigonometrische Polynom ist eine Fourierreihe, bei der alle bis auf endlich viele $c_k$ Null sind.

c) Die Behauptung ist korrekt. Sie folgt direkt aus der $T$-Periodizität der Integranden, denn auch $e^{ik\omega t}$ ist $T$-periodisch (nachrechnen!). In einigen Lehrbüchern wird auch diese Darstellung als Definition der Fourierkoeffizienten genutzt.

d) Die Behauptung ist falsch. Auch wenn die Fourier-Reihe $S_f(t) = \sum_{k \in \mathbb{Z}} c_k e^{ik\omega t}$ konvergiert, muss die Fourier-Reihe nicht stetig sein. Ein Gegenbeispiel ist die Fourier-Reihe der Sägezahnfunktion. Man beachte aber, dass für alle $n$ die $n$-ten Partialsummen $S_n f(t) = \sum_{k=-n}^{n} c_k e^{ik\omega t}$ jeweils stetig sind. Diese Eigenschaft kann allerdings bei Grenzübergang $n \to \infty$ verloren gehen, wenn $f$ nicht stetig ist.

e) Die Behauptung ist falsch: Für die stetige und stückweise stetig differenzierbare Funktion $f$ mit Fourierreihe $S_f$ gilt mit Theorem 1.1.21: $f(t) = S_f(t)$ für alle $t \in \mathbb{R}$. Gemäß der Euler-Formel ist $\sin t = \frac{i}{2}(e^{-it} - e^{it})$ und damit $S_f(t) = f(t) = \sin^2 t = \left( \frac{i}{2}(e^{-it} - e^{it}) \right)^2 = -\frac{1}{4}(e^{-2it} - 2 + e^{2it}) = \frac{1}{2} - \frac{1}{4}e^{-2it} - \frac{1}{4}e^{2it}$, entgegen der Behauptung.

f) Die Behauptung ist falsch: Beispielsweise gilt $F(0) = 0$, aber $F(0 + \pi) = \int_{0}^{\pi} \sin^2(\tau) d\tau > 0$. Wir werden später eine Bedingung kennen lernen, wann auch die Stammfunktion einer periodischen Funktion wieder periodisch ist.

g) Die Behauptung ist korrekt: Wir bestimmen zuerst die kleinste Periode von $f$. Dazu bestimmen wir die kleinsten Perioden der einzelnen Summanden:
*   $2 \cos(-t + 2)$ hat die kleinste Periode $2\pi$.
*   $3 \sin(-\frac{2}{9}t + 9)$ hat die kleinste Periode $9\pi$.
Also ist die kleinste Periode von $f$ gegeben durch $T = 18\pi$. Die zugehörige Kreisfrequenz ist $\omega = \frac{2\pi}{T} = \frac{1}{9}$.
***
[^10]
# Referenz
## Verknüpfung
- [[Komplexe Fourierpolynome]]
- [[Satz für partielle Integration|Partielle Integration]]
- [[Konvergenz von Fourierreihen]]
- [[Trigonometrische Polynome]]
- [[Komplexe Fourierkoeffizienten]] -> [[Vorlesung203920-20Teil20120-20Komplexe20Fourierkoeffizienten20und20Fourierpolynome.mp4|Video für komplexe Fourierkoeffizienten]]
- [[Sinus]]
- [[Cosinus]]
- [[Gerade Funktion]]
- [[Ungerade Funktion]]
- [[Additionstheoreme für Sinus und Cosinus]]
- [[Phasenverschiebung von Sinus]]
- [[Umrechnungsformeln zwischen reellen und komplexen Fourierkoeffizienten]]
- [[Rechenregeln für Potenzen von Sinus und Cosinus]]
- [[Periodische Funktion]]
- [[Sägezahnkurve]]
- [[Bestimmen der kleinsten Periode]]
- [[Euler-Formel|Eulerdarstellung]]
- [[Fourierreihe]]
- [[Approximation mit Fourierpolynomen im quadratischen Mittel]]
- [[Rechenregeln für Potenzen von Sinus und Cosinus]]
## Quellen
- [[tum_analysis3_Blatt01.pdf]] -> [[tum_analysis3_Blatt01_lsg.pdf]]
- [[tum_analysis3_ZÜ01-bearbeitung.pdf]]
- [[tum_Tutorium 1 - Analysis 3 (EI)_gruppe_3,4.pdf]]
- [[tum_analysis3_blatt01_bearbeitung-ben_kostka.pdf]]
<!--SR:!2025-05-06,4,270-->

[^1]: [[tum_analysis3_Blatt01_lsg.pdf#page=1]]

[^2]: [[tum_analysis3_Blatt01_lsg.pdf#page=1]]

[^3]: [[tum_analysis3_Blatt01_lsg.pdf#page=1]]

[^4]: [[tum_analysis3_Blatt01_lsg.pdf#page=1]]

[^5]: [[tum_analysis3_Blatt01_lsg.pdf#page=2]]

[^6]: [[tum_analysis3_Blatt01_lsg.pdf#page=2]]

[^7]: [[tum_analysis3_Blatt01_lsg.pdf#page=2]]

[^8]: [[tum_analysis3_Blatt01_lsg.pdf#page=3]]

[^9]: [[tum_analysis3_Blatt01_lsg.pdf#page=4]]

[^10]: [[tum_analysis3_Blatt01_lsg.pdf#page=5]]



