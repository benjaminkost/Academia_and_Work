---
"created date:": 22.10.2025 23:13
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
  - "[[202510201010 - Periodisches Faltungsprodukt|Faltung]]"
tags:
  - aufgaben
  - baby
  - flashcards
  - todo
  - Analysis3/Fourierreihe
  - Analysis3/Faltung
aliases:
  - Analysis 3 - Übung 3
parent:
siblings:
child:
questions: "[[202511082211 - Fragen zu Analysis Übung 3]]"
---
# Zentralübung (29.10.)

## Aufgabe Z 3.1: (Rechenregeln bei Fourierreihen)
a) Es bezeichne $\tilde{f}$ die $2\pi$-periodische Fortsetzung der Funktion $f : [0, 2\pi) \to \mathbb{R}$, $f(t) := 3 \sin(2t) + 2(\pi - t)$. Geben Sie alle nicht verschwindenden Fourierkoeffizienten $c_k$ der Fourierreihen-Darstellung von $\tilde{f}$ bei Periode $T = 2\pi$ an.

b) Geben Sie die Fourierreihen von $\tilde{f}(-t)$ und $\tilde{f}(t - 4)$ an.
?
### Lösung Z 3.1:
a) Es gilt $3 \sin(2t) = \frac{3 i e^{-2it} - i e^{2it}}{2}$, also hat dieser Teil die Fourierkoeffizienten $\hat{c}_2 = -\frac{3}{2}i = \frac{3}{2i}$, $\hat{c}_{-2} = \frac{3}{2}i = -\frac{3}{2i}$. Alle anderen Fourier-Koeffizienten sind null. Für den zweiten Teil ist $2(\pi - t) = 4 \cdot \frac{1}{2}(\pi - t) = 4s(t)$, wobei $s$ das Fundamentalbeispiel (die Sägezahnfunktion) ist, von dem wir die Fourier-Koeffizienten kennen. $4s(t)$ hat also die Fourier-Koeffizienten $\tilde{c}_0 = 0$, $\tilde{c}_k = \frac{4}{12ki} = \frac{2}{ki}$. Insgesamt hat $f$ also die Fourier-Koeffizienten $c_0 = 0$, $c_2 = \frac{5}{2i}$, $c_{-2} = -\frac{5}{2i}$, $c_k = \frac{2}{ki}$ für $k \in \mathbb{Z} \setminus \{-2, 0, 2\}$.

b) Die Rechenregel für Zeitumkehr ergibt für $f(-t)$ die Fourier-Koeffizienten $d_0 = c_0 = 0$, $d_2 = c_{-2} = -\frac{5}{2i}$, $d_{-2} = c_2 = \frac{5}{2i}$, $d_k = c_{-k} = -\frac{2}{ki}$ für $k \in \mathbb{Z} \setminus \{-2, 0, 2\}$. Insgesamt ergibt sich die Fourier-Reihe $S(t) = \frac{5}{2i} e^{-2it} - \frac{5}{2i} e^{2it} - \sum_{k=-\infty, k \notin \{-2,0,2\}}^{\infty} \frac{2}{ki} e^{ikt}$.
Die Rechenregel für eine Verschiebung im Zeitbereich sorgt für einen zusätzlichen Faktor $e^{-4ik}$, also $e_k = e^{-4ik}c_k$: $e_0 = 0$, $e_2 = e^{-8i}\frac{5}{2i}$, $e_{-2} = -e^{8i}\frac{5}{2i}$, $e_k = e^{-4ik}\frac{2}{ki}$ für $k \in \mathbb{Z} \setminus \{-2, 0, 2\}$. Insgesamt ergibt sich dann hier die Fourier-Reihe $S(t) = -\frac{5e^{8i}}{2i} e^{-2it} + \frac{5e^{-8i}}{2i} e^{2it} + \sum_{k=-\infty, k \notin \{-2,0,2\}}^{\infty} \frac{2e^{-4ik}}{ki} e^{ikt}$.
***
## Aufgabe Z 3.2: (Fourierreihe von Ableitung und Stammfunktion)
Wir betrachten die Funktion $f : \mathbb{R} \to \mathbb{R}$ mit $f(t) := \sum_{k=1}^{\infty} \frac{\sin kt}{k^3}$.

a) Bestimmen Sie für $k \in \mathbb{N}$ die Fourier-Koeffizienten $a_k$ und $b_k$ der Stammfunktion $F(t) := \int_{0}^{t} f(\tau) d\tau$.

b) Was lässt sich über den fehlenden Koeffizienten $a_0$ aussagen?

c) Berechnen Sie zudem die Fourier-Koeffizienten der Ableitung $f'(t)$. Kann man an den Fourier-Koeffizienten gewissen Symmetrien ablesen?

Hinweis: Sie dürfen ohne Begründung benutzen, dass $f$ stetig und $f'$ stückweise stetig auf $\mathbb{R}$ ist.
?
### Lösung Z 3.2:
#### a) 
Wir bestimmen die Fourier-Koeffizienten $a_k$ und $b_k$ der Stammfunktion $F(t) := \int_{0}^{t} f(\tau) d\tau$ in folgenden Schritten:
1. Ablesen der Fourier-Koeffizienten der Funktion $f$ in der cos-sin-Darstellung.
2. Bestimmung der Fourier-Koeffizienten $c_k$ der Funktion $f$.
3. Bestimmung der Fourier-Koeffizienten $d_k$ der Stammfunktion $F(t) := \int_{0}^{t} f(\tau) d\tau$ über die $c_k$.
4. Berechnung der Fourier-Koeffizienten $a_k$ und $b_k$ der Stammfunktion $F(t) := \int_{0}^{t} f(\tau) d\tau$ aus den $d_k$.

Wir interpretieren $f(t) = \sum_{k=1}^{\infty} \frac{\sin(kt)}{k^3}$ als Fourier-Reihe in cos-sin-Darstellung mit Koeffizienten $\tilde{a}_k = 0$ für alle $k \in \mathbb{N}_0$ und $\tilde{b}_k = \frac{1}{k^3}$ für alle $k \in \mathbb{N}$. Aus diesen Koeffizienten von $f$ in der cos-sin-Darstellung erhalten wir die Koeffizienten $c_k$ der zugehörigen komplexen Darstellung $f(t) = \sum_{k=-\infty}^{\infty} c_k e^{ikt}$ mit Hilfe der Umrechnungsformeln aus der Vorlesung:
$c_0 = \frac{\tilde{a}_0}{2} = 0$, $c_k = \frac{\tilde{a}_k - i\tilde{b}_k}{2} = -\frac{i}{2k^3}$, $c_{-k} = \frac{\tilde{a}_k + i\tilde{b}_k}{2} = \frac{i}{2k^3}$, wobei $k \in \mathbb{N}$.
Da $c_{-k} = -\frac{i}{2(-k)^3}$, können wir auch eine allgemeine Formel für $k \in \mathbb{Z} \setminus \{0\}$ angeben:
$c_0 = 0$, $c_k = -\frac{i}{2k^3}$ für $k \in \mathbb{Z} \setminus \{0\}$.
Wegen $c_0 = 0$ ist die Stammfunktion in der Tat wieder periodisch und lässt sich in eine Fourier-Reihe entwickeln. Für die Fourier-Koeffizienten der Stammfunktion $F(t) \equiv \sum_{k=-\infty}^{\infty} d_k e^{ikt}$ gilt im Fall $k \neq 0$ gemäß Vorlesung schlicht $d_k = \frac{c_k}{ik\omega}$ mit der Kreisfrequenz $\omega = 1$, also hierbei $d_k = -\frac{1}{2k^4}$ für alle $k \in \mathbb{Z} \setminus \{0\}$. Die zugehörige cos-sin-Darstellung der Fourier-Reihe erhält mit den Koeffizienten $a_k = d_k + d_{-k} = -\frac{1}{k^4}$ und $b_k = i(d_k - d_{-k}) = 0$ und für alle $k \in \mathbb{N}$ die gerade Cosinus-Form $F(t) = \frac{a_0}{2} - \sum_{k=1}^{\infty} \frac{\cos(kt)}{k^4}$ für alle $t \in \mathbb{R}$.
#### b) 
Aus der Vorlesung wissen wir, dass $a_0 \equiv 2d_0$ sich leider nur über das Integral $d_0 = -\frac{1}{2\pi} \int_{0}^{2\pi} tf(t) dt$ berechnen lässt, wobei mit $(d_k)_k$ wieder die komplexen Fourier-Koeffizienten von $F$ bezeichnet seien. Vertauschen wir dabei Summation und Integration (hier aus Konvergenzgründen möglich!), so sehen wir mittels partieller Integration:
$d_0 = -\frac{1}{2\pi} \sum_{k=1}^{\infty} \frac{1}{k^3} \int_{0}^{2\pi} t \sin(kt) dt = -\frac{1}{2\pi} \sum_{k=1}^{\infty} \frac{1}{k^3} \left( \underbrace{\left[ -\frac{t}{k} \cos(kt) \right]_{0}^{2\pi}}_{=-\frac{2\pi}{k}} + \underbrace{\frac{1}{k} \int_{0}^{2\pi} \cos(kt) dt}_{=0} \right) = \sum_{k=1}^{\infty} \frac{1}{k^4}$.
Mithilfe der sogenannten Riemannschen Zetafunktion, gegeben durch $\zeta(s) := \sum_{k=1}^{\infty} \frac{1}{k^s}$ für $s > 1$, erhalten wir insgesamt $d_0 = \zeta(4) = \frac{\pi^4}{90}$ (Formelsammlung). Damit erhalten wir die Darstellung $F(t) = \frac{\pi^4}{90} - \sum_{k=1}^{\infty} \frac{\cos(kt)}{k^4}$.
#### c) 
$f$ ist eine stetige Funktion und $f'$ ist stückweise stetig auf $\mathbb{R}$. Mit der Rechenregel für Ableitungen ergibt sich für die Fourier-Koeffizienten $e_k$ von $f'$:
$e_0 = ik\omega c_0 = 0$, $e_k = ik\omega c_k = \frac{1}{2k^2}$, $e_{-k} = -ik\omega c_{-k} = \frac{1}{2k^2} = e_k$ wobei $k \in \mathbb{N}$ und $\omega = 1$. Wir erkennen an den Koeffizienten, dass die Fourierreihe der Ableitungsfunktion eine gerade Funktion ist. In der Tat ist $f'(t) = \sum_{k=1}^{\infty} \frac{\cos(kt)}{k^2}$.
***
## Aufgabe Z 3.3: (Faltung mit Sägezahn)
Es sei $s : \mathbb{R} \to \mathbb{R}$ mit $s(t) := \frac{\pi-t}{2}$ für $t \in [0, 2\pi)$ die $2\pi$-periodisch fortgesetzte Sägezahnfunktion, das Fundamentalbeispiel der Vorlesung.

a) Zeigen Sie, dass die periodische Faltung $f * g$ $T$-periodisch ist, wenn $f$ und $g$ es sind. Berechnen Sie die periodische Faltung $(s * s)(t) := \frac{1}{2\pi} \int_{0}^{2\pi} s(t - \tau)s(\tau) d\tau$ für $t \in \mathbb{R}$ direkt.

b) Welcher Zusammenhang besteht zwischen den Fourier-Koeffizienten $c_k$ von $s$ und den Fourier-Koeffizienten $d_k$ von $s * s$? Welcher Zusammenhang besteht zwischen $s$ und $s * s$?
?
#### a)
Es seien $f, g : \mathbb{R} \to \mathbb{C}$ Funktionen mit Periode $T$. Dann ist die periodische Faltung von $f$ und $g$ wegen der Periodizität von $f$ ebenfalls $T$-periodisch:
$$ (f * g)(t + T) = \frac{1}{T} \int_0^T f(t + T - \tau)g(\tau) d\tau = \frac{1}{T} \int_0^T f(t - \tau)g(\tau) d\tau = (f * g)(t). $$
Die Bezeichnung „periodisch“ ist also gerechtfertigt. Da die Sägezahnfunktion $s$ $2\pi$-periodisch ist, genügt es deshalb, die Faltung für $t \in [0, 2\pi)$ zu berechnen. Für $t \in [-2\pi, 0)$ gilt $s(t) = - \frac{t+\pi}{2}$, so dass sich auf $[0, 2\pi)$ folgendes ergibt:
$$ (s * s)(t) = \frac{1}{2\pi} \int_0^{2\pi} s(t - \tau)s(\tau) d\tau = \frac{1}{2\pi} \left(\int_0^t s(t - \tau)s(\tau) d\tau + \int_t^{2\pi} s(t - \tau)s(\tau) d\tau \right) $$
$$ = \frac{1}{8\pi} \left(\int_0^t (\tau - t + \pi)(\pi - \tau) d\tau + \int_t^{2\pi} (\tau - t - \pi)(\pi - \tau) d\tau \right) $$
$$ = \frac{1}{8\pi} \left[ 2\pi^2t - \pi t^2 - \frac{2}{3} \pi^3 \right] = \frac{6\pi t - 3t^2 - 2\pi^2}{24} = \frac{\pi^2 - 3(t - \pi)^2}{24}. $$
Wir haben dabei genutzt, dass $t - \tau \geq 0$ falls $\tau \in [0, t]$ und $t - \tau \leq 0$ für $\tau \in [t, 2\pi]$ und daher das Integral entsprechend aufgeteilt, um für $s(t-\tau)$ jeweils die richtige Auswertungsvorschrift nutzen zu können. Die periodische Faltung $s * s$ ist dann die $2\pi$-periodische Fortsetzung dieser Funktion.

#### b)
Zusammenhang zwischen den $c_k$ und $d_k$:
Aus der Vorlesung sind die Fourierkoeffizienten $c_k$ der Sägezahnfunktion bekannt; es gilt $c_0 = 0$ und $c_k = \frac{1}{2ik}$ für $k \neq 0$. Außerdem ist aus der Vorlesung bekannt dass die Fourierkoeffizienten von $f * g$ sich als Produkt der Fourierkoeffizienten von $f$ und $g$ ergeben. In unserem Fall also $d_0 = 0$ und für $k \neq 0$:
$$ d_k = c_k^2 = \frac{1}{2ik} \frac{1}{2ik} = - \frac{1}{4k^2}. $$
Bemerkung: In Übereinstimmung mit der Theorie gilt $d_k = d_{-k}$, da $s*s$ eine gerade Funktion ist, wie man sich leicht überlegen kann.

**Zusammenhang zwischen $s$ und $s * s$:**
Auf $(0, 2\pi)$ gilt
$$ (s * s)'(t) \stackrel{a)}{=} \left( \frac{\pi^2 - 3(t - \pi)^2}{24} \right)' = - \frac{(t - \pi)}{4} = \frac{1}{2} s(t). $$
Wegen der Periodizität der beteiligten Funktionen gilt daher an allen Differenzierbarkeitsstellen von $s * s$ die Identität $s \equiv 2(s * s)'$.


Bemerkung: Neben dem Zusammenhang $d_k = c_k^2$ aufgrund der Faltung ergibt sich aus der Eigenschaft $s \equiv 2(s * s)'$ für die Fourier-Koeffizienten der weitere Zusammenhang $c_k = 2ikd_k$, dessen Gültigkeit man sofort bestätigt. Man beachte dabei, dass wir genutzt haben, dass $s * s$ nach Lemma 1.1.48 stetig ist.

***
# Hausaufgaben (bis 3.11. - 5.11.)
## Aufgabe H 3.1: (Verkettung von Rechenregeln, Fourierreihe von Stammfunktion)
a) Man bestimme die Fourierreihe $S_f$ der $2\pi$-periodischen Funktion $f$ in cos-sin-Darstellung, wobei $f(t) := \begin{cases} -t^2 & \text{für } -\pi < t < 0 \\ t^2 & \text{für } 0 < t < \pi \end{cases}$. Nutzen Sie dann die Umrechnungsformeln, um die Fourier-Koeffizienten $c_k$ zu bestimmen.
b) Wie ist $f$ an den Stellen $t = -\pi$ und $t = 0$ zu definieren, damit $S_f \equiv f$ auf $\mathbb{R}$ gilt?
c) Wie lautet die Fourierreihe von $g(t) := 2f'(-t)$?
d) Bestimmen Sie mit Hilfe der Rechenregeln die Fourierreihe von $F(t) := \int_{0}^{t} f(\tau) d\tau$.
?
### Lösung H 3.1
a) Die Funktion $f$ ist offensichtlich ungerade. Daher gilt $a_k = 0$ für alle $k \in \mathbb{N}_0$. Zudem gilt $T = 2\pi$ und $\omega = 1$. Für die $b_k$ ergibt sich mit der Formelsammlung:
$$ b_k = \frac{4}{T} \int_{0}^{T/2} f(t) \sin(k\omega t) dt = \frac{2}{\pi} \int_{0}^{\pi} t^2 \sin(kt) dt $$
$$ \stackrel{FS}{=} \frac{2}{\pi} \left[ \frac{2t}{k^2} \sin(kt) - \left( \frac{t^2}{k} - \frac{2}{k^3} \right) \cos(kt) \right]_{0}^{\pi} $$
$$ = \frac{2}{\pi} \left[ \left( -\frac{\pi^2}{k} + \frac{2}{k^3} \right) (-1)^k - \frac{2}{k^3} \right] = \begin{cases} -\frac{2\pi}{k} & \text{für } k \text{ gerade} \\ \frac{2\pi}{k} - \frac{8}{\pi k^3} & \text{für } k \text{ ungerade} \end{cases} $$
Insgesamt ergibt sich die cos-sin-Darstellung
$$ S_f(t) = \sum_{k=1}^{\infty} b_k \sin(kt) = 2\pi \sum_{k=1}^{\infty} \frac{(-1)^k - \sin(kt)}{k} - \frac{8}{\pi} \sum_{k=1}^{\infty} \frac{\sin((2k - 1)t)}{(2k - 1)^3} $$
Für die komplexe Darstellung nutzen wir die Umrechnungsformeln für die Koeffizienten und erhalten $c_k = -i \frac{b_k}{2}$ und $c_{-k} = i \frac{b_k}{2}$ für $k \in \mathbb{N}$ sowie $c_0 = 0$. Die komplexe Fourierreihe lautet daher $S_f(t) = \sum_{k=-\infty}^{\infty} c_k e^{ikt}$ mit
$$ c_0 = 0, $$
$$ c_{2k} = -i b_{2k}/2 = \pi i/(2k), $$
$$ c_{-2k} = -c_{2k}, $$
$$ c_{2k-1} = -i b_{2k-1}/2 = -\pi i/(2k - 1) + 4i/(\pi(2k - 1)^3) $$
$$ c_{-(2k-1)} = -c_{2k-1}, $$
wobei $k \in \mathbb{N}$.

b) Da $f$ stückweise stetig differenzierbar ist, konvergiert $S_f$ gegen $f$ an allen Stetigkeitsstellen und es gilt die Mittelwerteigenschaft $S_f(t) = \frac{f(t^+) + f(t^-)}{2}$. Die Funktion $f$ ist stetig auf $(-\pi, 0)$ und $(0, \pi)$, d. h. dort gilt ohnehin $S_f \equiv f$. Fraglich ist noch, wie $f(0)$ und $f(-\pi)$ zu definieren sind, damit $S_f \equiv f$ auf $\mathbb{R}$ erfüllt ist. Setzen wir $f(0) := 0$, so ist $f$ stetig in Null und daher gilt $S_f(0) = f(0) = 0$. Bei $t = -\pi$ existiert eine Sprungstelle, an der von $f(-\pi^-) = \pi^2$ zu $f(-\pi^+) = -\pi^2$ gesprungen wird. Definieren wir $f(-\pi) := \frac{f(-\pi^+) + f(-\pi^-)}{2} = 0$, so besitzt $f$ an der Stelle $t = -\pi$ ebenso wie die Fourierreihe die Mittelwerteigenschaft und daher gilt $f(-\pi) = S_f(-\pi)$, so dass schließlich die Fourier-Reihe überall gegen $f$ konvergiert.

c) $g(t) = 2f'(-t)$ entsteht aus $f$ durch die Rechenregeln:
a) Zeitumkehr: $f(-t) \stackrel{c}{\leftrightarrow} (c_{-k})_k$
b) Ableitung bei Sprungstellen: $f'(t) \stackrel{c}{\leftrightarrow} \left(ik\omega c_k - \frac{1}{T} \sum_{j=1}^N \Delta_j e^{-ik\omega t_j}\right)_k$
c) Multiplikation mit einer Konstanten: $\alpha f(t) \stackrel{c}{\leftrightarrow} (\alpha c_k)_k$
Man beachte, dass $f$ nicht stetig ist, weshalb man die Ableitungsregel bei Sprungstellen braucht. Nun muss man diese Regeln in der richtigen Reihenfolge anwenden:
1. Die Fourier-Koeffizienten von $h(t) := f'(t)$ sind mit $\omega = 1$
   $$ \left(ikc_k - \frac{1}{T} \sum_{j=1}^N \Delta_j e^{-ikt_j}\right)_k = \left(ikc_k - \frac{1}{2\pi} (f(\pi^+) - f(\pi^-))e^{-ik\pi}\right)_k = (ikc_k + \pi e^{-ik\pi})_k. $$
   Dabei haben wir genutzt, dass $f$ eine Sprungstelle bei $t_1 = \pi$ mit Sprung $\Delta_1 = f(\pi^+) - f(\pi^-) = -\pi^2 - \pi^2 = -2\pi^2$ hat.
2. Die Fourier-Koeffizienten von $\tilde{h}(t) := h(-t) = f'(-t)$ sind dann $(-ikc_{-k} + \pi e^{ik\pi})_k$.
3. Schließlich sind dann die Fourier-Koeffizienten von $g(t) = 2 \tilde{h}(t)$ dann $(-2ikc_{-k} + 2\pi e^{ik\pi})_k$.
Insgesamt ergibt sich also $g(t) = 2f'(-t) \stackrel{c}{\leftrightarrow} (-2ikc_{-k} + 2\pi e^{ik\pi}) = (-2ikc_{-k} + 2\pi(-1)^k) =: d_k$ bei gleicher Periode und Kreisfrequenz. Schließlich ist dann $S_g(t) = \sum_{k=-\infty}^{\infty} d_k e^{ikt}$, was man mittels Fallunterscheidungen mit Hilfe von a) noch aufschlüsseln könnte, worauf wir hier aber verzichten.
Bemerkung: Man könnte bei den Schritten 1 und 2 oben auch erst die Zeitumkehr machen und dann die Ableitung. Dann würde man $h(t) := f(-t)$ definieren und danach $\tilde{h}(t) := -h'(t) = -f'(-t)(-1) = f'(-t)$. Man beachte, dass wegen der inneren Ableitung auf das Minuszeichen in der Definition von $\tilde{h}$ nicht verzichtet werden kann (was man aber leicht vergessen kann). Die Koeffizienten werden dann wieder ebenso nach den Rechenregeln bestimmt (Nachrechnen! Dabei kann man nutzen, dass $e^{ik\pi} = e^{-ik\pi}$ für $k \in \mathbb{N}$).

d) Da $\int_0^{2\pi} f(t) dt = 0$ gilt, ist auch die Stammfunktion $2\pi$-periodisch und es gilt
$$ \int_0^t f(\tau) d\tau \stackrel{c}{\leftrightarrow} \begin{cases} \frac{c_k}{ik} & \text{für } k \neq 0, \\ -\frac{1}{2\pi} \int_0^{2\pi} tf(t) dt & \text{für } k = 0. \end{cases} $$
Für $k = 0$ ergibt sich im Detail:
$$ -\frac{1}{2\pi} \int_0^{2\pi} tf(t) dt = -\frac{1}{2\pi} \left(\int_0^{\pi} t^3 dt - \int_{\pi}^{2\pi} t(t - 2\pi)^2 dt \right) = \frac{\pi^3}{12}. $$
Die Fourierkoeffizienten von $F$ sind also gegeben durch $c_0^F = \frac{\pi^3}{12}$, $c_{2k}^F = \frac{\pi}{(2k)^2}$ für $k \in \mathbb{Z} \setminus \{0\}$ sowie $c_{2k-1}^F = -\frac{\pi}{(2k-1)^2} + \frac{4}{\pi(2k-1)^4}$ für $k \in \mathbb{Z}$.
Die Fourierreihe von $F$ ist nun gegeben durch
$$ S_F(t) = \frac{\pi^3}{12} + \sum_{k=-\infty, k \neq 0}^{\infty} \frac{\pi}{(2k)^2} e^{2ikt} + \sum_{k=-\infty}^{\infty} \left( -\frac{\pi}{(2k - 1)^2} + \frac{4}{\pi(2k - 1)^4} \right) e^{i(2k-1)t}. $$
Eine alternative Darstellung von $S_F$ lautet
$$ S_F(t) = \frac{\pi^3}{12} + \pi \sum_{n=-\infty, n \neq 0}^{\infty} \frac{(-1)^n}{n^2} e^{int} + \frac{4}{\pi} \sum_{k=-\infty}^{\infty} \frac{1}{(2k - 1)^4} e^{i(2k-1)t}. $$
***
[^1]
## Aufgabe H 3.2: („Praktikerformel“ für Treppenfunktionen)
Es sei $f : \mathbb{R} \to \mathbb{R}$ eine $2\pi$-periodische, zwischen den Stellen $0 = t_0 < t_1 < \dots < t_m < 2\pi$ konstante Funktion mit den Sprungwerten $s_n := f(t_n^+) - f(t_n^-)$, $n = 0, 1, \dots, m$. Dabei bezeichnet $f(t_n^+)$ den rechtsseitigen Grenzwert von $f$ in $t_n$ und $f(t_n^-)$ den linksseitigen Grenzwert von $f$ in $t_n$.
a) Rechnen Sie nach, dass für die Fourier-Koeffizienten $c_k$, $k \in \mathbb{Z} \setminus \{0\}$, von $f$ die folgende „Praktikerformel“ gilt:
$c_k = \frac{1}{2k\pi i} \sum_{n=0}^{m} s_n e^{-ikt_n}$.
b) Berechnen Sie für $m = 3$ die Fourier-Koeffizienten der cos-sin-Darstellung der Treppe mit $f(0^+) = 0$, $s_n = 1$ für $n \in \{1, 2, 3\}$ und konstanter Stufenlänge.
?
### Lösung H 3.2
a) Um die „Praktikerformel“ nachzuweisen, spalten wir den Koeffizienten $c_k = \frac{1}{2\pi} \int_0^{2\pi} f(t)e^{-ikt} dt$ für $k \neq 0$ in lauter Teilintegrale auf, in denen $f \equiv \text{const}$ gilt, wo wir dann zur Ausnutzung von $f' = 0$ partiell integrieren. Hierbei verwenden wir die Bezeichnung $t_{m+1} := 2\pi$. Wir erhalten durch das beschriebene Vorgehen in der Tat die angegebene Formel:
$$ c_k = \frac{1}{2\pi} \sum_{n=0}^m \int_{t_n}^{t_{n+1}} f(t)e^{-ikt} dt = -\frac{1}{2k\pi i} \sum_{n=0}^m \left[ f(t)e^{-ikt} \right]_{t_n^+}^{t_{n+1}^-} $$
$$ = \frac{1}{2k\pi i} \sum_{n=0}^m \left[ f(t_n^+)e^{-ikt_n} - f(t_{n+1}^-)e^{-ikt_{n+1}} \right] $$
$$ = \frac{1}{2k\pi i} \left[ f(0^+) + s_1e^{-ikt_1} + \dots + s_me^{-ikt_m} - \underbrace{f(2\pi^-)}_{=f(0^-)} \underbrace{e^{-2ik\pi}}_{=1} \right] $$
$$ = \frac{1}{2k\pi i} \left[ s_0 + s_1e^{-ikt_1} + \dots + s_me^{-ikt_m} \right] = \frac{1}{2k\pi i} \sum_{n=0}^m s_n e^{-ikt_n}. $$

b) Für die vierstufige Treppe ergibt sich hierbei $t_n = \frac{n\pi}{2}$ und wegen $s_n = 1$ für $n \in \{1, 2, 3\}$ erhalten wir $s_0 = -3$ (Skizze!). Die Praktikerformel nimmt hier also konkret die Gestalt
$$ c_k = \frac{1}{2k\pi i} \left( \sum_{n=1}^3 e^{-i \frac{kn\pi}{2}} - 3 \right) $$
für $k \neq 0$ an. Daraus ergeben sich für $k \in \mathbb{N}$ die Koeffizienten
$$ a_k = -\frac{1}{k\pi} \sum_{n=1}^3 \sin\left(\frac{kn\pi}{2}\right) \quad \text{und} \quad b_k = \frac{1}{k\pi} \left[ \left( \sum_{n=1}^3 \cos\left(\frac{kn\pi}{2}\right) \right) - 3 \right]. $$
Zunächst lassen sich hierin die $a_k$ zu $a_k = -\frac{1}{k\pi} \left( \sin\left(\frac{k\pi}{2}\right) + \sin\left(\frac{3k\pi}{2}\right) \right)$ vereinfachen, woraus wir für alle $k \in \mathbb{N}$ unmittelbar $a_k = 0$ ablesen. Für die $b_k$ erhalten wir
$$ b_k = \frac{1}{k\pi} \left[ -3 + (-1)^k + \cos\left(\frac{k\pi}{2}\right) + \cos\left(\frac{3k\pi}{2}\right) \right] = \begin{cases} 0 & \text{falls } k = 4j, \\ -\frac{4}{k\pi} & \text{falls } k = 2(2j - 1), \\ -\frac{4}{k\pi} & \text{falls } k = 2j - 1, \end{cases} $$
mit $j \in \mathbb{N}$. Zu berechnen bleibt noch das Integral für $a_0$, nämlich
$$ a_0 = 2c_0 = \frac{1}{\pi} \int_0^{2\pi} f(t) dt = \frac{0 + 1 + 2 + 3}{2} = 3. $$
Wir erhalten schließlich für alle $t \in \mathbb{R}$ die Fourierreihe
$$ S_f(t) = \frac{3}{2} - \frac{2}{\pi} \sum_{j=1}^{\infty} \frac{\sin(2(2j - 1)t) + 2 \sin((2j - 1)t)}{2j - 1}. $$
Bemerkung: Die Treppenfunktion $f$ ist genau in den $t_n$, $n \in \{1, 2, 3, 4\}$, unstetig. Da $f$ stückweise stetig differenzierbar ist, stimmt für alle $t \in [0, 2\pi)$ mit $t \neq t_n$, $n \in \{1, 2, 3, 4\}$, die Fourierreihe von $f$ mit der Funktion $f$ überein, d. h. es gilt $S_f(t) = f(t)$. In den Sprungstellen, also für $t = t_n$, $n \in \{1, 2, 3, 4\}$, hat $S_f$ bekanntlich die Mittelwert-Eigenschaft: $S_f(t_n) = \frac{f(t_n^+) + f(t_n^-)}{2}$. Dies erkennen wir auch durch Einsetzen in die Fourierreihe; für $n = 0$, also an der Sprungstelle $t = t_0 = 0$, gilt beispielsweise $S_f(0) = \frac{3}{2} = \frac{f(0^+) + f(0^-)}{2}$.
***
[^2]
## Aufgabe H 3.3: (Größenordnung der Fourierkoeffizienten)
Es sei $h : \mathbb{R} \to \mathbb{R}$ die ungerade, $2\pi$-periodische Funktion mit $h(t) = t^2 \cdot (t - \pi)^2$ für $t \in [0, \pi]$. Unten sehen Sie eine Skizze des Graphen von $h$.
Wie lauten die zu $h$ gehörigen Fourierkoeffizienten der Fourierreihe zu Periode $T = 2\pi$? Kreuzen Sie die richtige Antwort an und begründen Sie kurz Ihre Antwort ohne die Koeffizienten explizit zu berechnen.
*   $c_n = \begin{cases} 0, & n \text{ gerade} \\ \frac{8i \cdot (n^2\pi^2 - 12)}{n^5\pi}, & n \text{ ungerade} \end{cases}$
*   $c_n = \begin{cases} 0, & n \text{ gerade} \\ \frac{8i \cdot (n^2\pi^2 - 12)}{n^3\pi}, & n \text{ ungerade} \end{cases}$
*   $c_n = \begin{cases} 0, & n \text{ gerade} \\ \frac{8i \cdot (n^2\pi^2 - 12)}{n^4\pi}, & n \text{ ungerade} \end{cases}$
Hinweis: Nutzen Sie die Rechenregeln sowie den Zusammenhang zwischen der Größe der Fourier-Koeffizienten und der Glattheit der Funktion (wie oft ist die Funktion stetig differenzierbar?).
![[Bildschirmfoto 2025-10-29 um 11.39.11.png|400]]
?
### Lösung H 3.3
Die richtige Antwort ist
$$ c_n = \begin{cases} 0, & n \text{ gerade} \\ \frac{8i \cdot (n^2\pi^2 - 12)}{n^5\pi}, & n \text{ ungerade} \end{cases} $$
Da $h$ ungerade ist, muss laut Skriptum $c_n = -c_{-n}$ für alle natürlichen Zahlen $n$ gelten, was die dritte Antwortmöglichkeit eliminiert. Wir zeigen nun, dass sowohl $h$ als auch $h'$ stetig und zudem $h''$ stückweise stetig differenzierbar ist: Dass $h$, $h'$ und $h''$ jeweils stückweise stetig differenzierbar sind, folgt sofort daraus, dass $h$ auf $[0, \pi)$ ein Polynom ist. Die einzigen möglichen Unstetigkeitsstellen sind $t = 0$ und $t = \pi$ (und jeweils $2\pi$-Verschiebungen davon). Es bleibt die Stetigkeit von $h$ und $h'$ in diesen Punkten zu zeigen. Auf dem Intervall $(0, \pi)$ ist $h(t) = t^2 \cdot (t - \pi)^2 = t^4 - 2\pi t^3 + \pi^2 t^2$. Auf diesem Intervall gilt dann $h'(t) = 4t^3 - 6\pi t^2 + 2\pi^2 t$. Nun gilt
$h(0^+) = 0^2 \cdot (0 - \pi)^2 = 0 = -h(0^+) = h(0^-)$,
$h(\pi^-) = \pi^2 \cdot (\pi - \pi)^2 = 0 = -h(\pi^-) = h(\pi^+)$,
$h'(0^+) = 4 \cdot 0^3 - 6\pi \cdot 0^2 + 2\pi^2 \cdot 0 = 0 = h'(0^-)$,
$h'(\pi^-) = 4\pi^3 - 6\pi\pi^2 + 2\pi^2\pi = 0 = h'(\pi^+)$.
Also sind $h$ und $h'$ stetig und $h''$ stückweise stetig differenzierbar. Deswegen muss laut Skriptum $|c_n| \le \frac{M}{|n|^3}$ für eine reelle Zahl $M > 0$ und $n \neq 0$ gelten. Diese Eigenschaft besitzt die zweite Antwortmöglichkeit nicht (sie erfüllt nur $|c_n| \le \frac{M}{|n|}$), so dass nur die erste als einzig mögliche Antwort verbleibt. Übrigens ist $h''$ in $\pi$ nicht mehr stetig, denn auf $(0, \pi)$ ist $h''(t) = 12t^2 - 12\pi t + 2\pi^2$ und es ist $h''(\pi^-) = 12\pi^2 - 12\pi\pi + 2\pi^2 = 2\pi^2$. Da die zweite Ableitung von $h$ wieder eine ungerade Funktion ist, gilt dann aber $h''(\pi^+) = -h''(\pi^-) = -2\pi^2 \neq h''(\pi^-)$.
***
[^3]
# Ergänzende Hausaufgaben:
## Aufgabe E 3.1: (Verkettung von Rechenregeln, ehemalige Klausuraufgabe)
Gegeben sei die $2\pi$-periodische Funktion $f : \mathbb{R} \to \mathbb{R}$ mit $f(t) := \begin{cases} 1 & \text{für } 0 \le t < \pi \\ 0 & \text{für } \pi \le t < 2\pi \end{cases}$. Sie hat für alle $t \in \mathbb{R}$ die Fourierreihe $S_f(t) = \frac{1}{2} + \sum_{k=-\infty}^{\infty} \left( \frac{-i}{(2k+1)\pi} e^{i(2k+1)t} \right)$.
a) Bestimmen Sie $S_f(0)$, $S_f(1)$ sowie die cos-sin-Darstellung von $S_f$.
b) Die Fourierreihe $S_g$ zu $g(t) := 3f(4t - 1)$ unter Verwendung der Rechenregeln für Fourierreihen.
?
### Lösung E 3.1
a) Die Funktion $f$ ist stückweise stetig differenzierbar, daher stimmt $S_f$ an jeder Stetigkeitsstelle von $f$ mit $S_f$ überein; insbesondere gilt $S_f(1) = f(1) = 1$. Da $f$ stückweise stetig differenzierbar ist, besitzt $S_f$ außerdem auf ganz $\mathbb{R}$ die Mittelwerteigenschaft; insbesondere gilt $S_f(0) = \frac{f(0^+) + f(0^-)}{2} = \frac{1+0}{2} = \frac{1}{2}$. Die komplexen Fourier-Koeffizienten von $f$ lauten $c_0 = \frac{1}{2}$, $c_n = -\frac{i}{n\pi}$ für $n = 2k + 1$ mit $k \in \mathbb{Z}$, und $0$ sonst, d. h. $c_n = 0$ für $n = 2k$ mit $k \in \mathbb{Z} \setminus \{0\}$. Mithilfe der Umrechnungsformeln ergibt sich daraus unter Verwendung der für alle $n \in \mathbb{N}$ gültigen Identität $c_n = -c_{-n}$:
$a_0 = 2c_0 = 1$, $a_n = c_n + c_{-n} = 0$ für $n \in \mathbb{N}$
sowie $b_n = i(c_n - c_{-n}) = 2ic_n = \begin{cases} \frac{2}{n\pi} & \text{für } n = 2k + 1 \text{ mit } k \in \mathbb{N}_0, \\ 0 & \text{für } n = 2k \text{ mit } k \in \mathbb{N}. \end{cases}$
Die cos-sin-Darstellung von $S_f$ ist daher für alle $t \in \mathbb{R}$ gegeben durch
$$ S_f(t) = \frac{1}{2} + \frac{2}{\pi} \sum_{k=0}^{\infty} \frac{\sin((2k + 1)t)}{2k + 1} = \frac{1}{2} + \frac{2}{\pi} \sum_{k=1}^{\infty} \frac{\sin((2k - 1)t)}{2k - 1}. $$

b) Mittels der Rechenregeln für Fourierreihen erhalten wir für die komplexen Fourierkoeffizienten $(d_n)_{n \in \mathbb{Z}}$ der $2\pi/4 = \pi/2$-periodischen Funktion $g$ die Beziehung $d_n = 3e^{-in}c_n$. Da wir mehrere Rechenregeln anwenden müssen, fügen wir Hilfsfunktionen $h$ und $l$ ein, deren Fourierkoeffizienten wir mit $c_k^h$ und $c_k^l$ bezeichnen. Die Fourier-Koeffizienten von $g$ seien $c_k^g$. Wir können $g$ durch folgende Schritte als Verkettung von einzelnen Rechenregeln darstellen:
$h(t) := f(t - 1)$
$l(t) := h(4t) = f(4t - 1)$
$g(t) = 3l(t) = 3f(4t - 1)$
Wir haben damit $h$ als Verschiebung im Zeitbereich von $f$ dargestellt. $l$ wiederum ist eine Streckung der Zeitskala von $h$ und schließlich ist $g$ durch Linearität aus $l$ entstanden. Für die zugehörigen Fourier-Koeffizienten $c_k^h$, $c_k^l$ und $c_k^g$, Perioden $T_h$, $T_l$ und $T_g$ und Kreisfrequenzen $\omega_h$, $\omega_l$ und $\omega_g$ gilt dann:
$c_k^h = e^{-ik}c_k$, $T_h = T = 2\pi$, $\omega_h = \omega = 1$,
$c_k^l = c_k^h = e^{-ik\omega}c_k = e^{-ik}c_k$, $T_l = \frac{T_h}{4} = \frac{\pi}{2}$, $\omega_l = 4\omega_h = 4$,
$c_k^g = 3c_k^l = 3e^{-ik}c_k$, $T_g = T_l = \frac{\pi}{2}$, $\omega_g = \omega_l = 4$.
Insgesamt haben wir also die Beziehung $c_n^g = 3e^{-in}c_n$, wobei die Fourierkoeffizienten zur Periode $T_g = \frac{\pi}{2}$ gehören. Die komplexe Fourierreihe von $g$ lautet wegen $\omega_g = 4$ daher für alle $t \in \mathbb{R}$
$$ S_g(t) = \sum_{n=-\infty}^{\infty} d_n e^{4int} = 3 \sum_{n=-\infty}^{\infty} e^{-in}c_n e^{4int} = \frac{3}{2} + 3 \sum_{k=-\infty}^{\infty} e^{-i(2k+1)}c_{2k+1}e^{4i(2k+1)t} $$
$$ = \frac{3}{2} - \frac{3i}{\pi} \sum_{k=-\infty}^{\infty} \frac{e^{-i(2k+1)}}{2k + 1} e^{4i(2k+1)t}. $$
Bemerkung: Wir hätten oben auch eine andere Verkettung von einzelnen Rechenregeln anwenden können, um $g$ darzustellen:
$h(t) := f(4t)$
$l(t) := h(t - \frac{1}{4}) = f(4t - 1)$
$g(t) = 3l(t) = 3f(4t - 1)$
Man beachte, dass wir wegen der Definition von $h$ hier um $\frac{1}{4}$ verschieben mussten, um $f(4t - 1)$ zu bekommen. Für die Fourierkoeffizienten hätte sich dann ergeben:
$c_k^h = c_k$, $T_h = \frac{T}{4} = \frac{\pi}{2}$, $\omega_h = 4\omega = 4$,
$c_k^l = e^{-\frac{1}{4}ik\omega_h} c_k^h = e^{-ik}c_k$, $T_l = T_h = \frac{\pi}{2}$, $\omega_l = \omega_h = 4$,
$c_k^g = 3c_k^l = 3e^{-ik}c_k$, $T_g = T_l = \frac{\pi}{2}$, $\omega_g = \omega_l = 4$.
Wir kommen also zum gleichen Ergebnis wie oben. Man beachte, dass wir bei der zweiten Rechenregel eine andere Kreisfrequenz nutzen mussten als oben.
***
[^4]
## Aufgabe E 3.2: (Rechenregeln bei der Fourierreihe, ehemalige Klausuraufgabe)
Über $f(x) := \sum_{k \in \mathbb{Z} \setminus \{0\}} \frac{e^{ikx}}{k^5}$ wird die $2\pi$-periodische $C^2$-Funktion $f : \mathbb{R} \to \mathbb{C}$ erklärt. Man bestimme für die beiden Funktionen $g(x) := f(2x - 3)$ und $h(x) := g(-x) + f(4x)$ jeweils die Periode $T$, die Kreisfrequenz $\omega$ und die zugehörigen Fourier-Koeffizienten $c_k$. Geben Sie zudem die zugehörigen Fourierreihen $S_g(x)$ und $S_h(x)$ an.
?
### Lösung E 3.2
Die Ausgangsfunktion $f$ besitzt die Periode $T = 2\pi$, die Kreisfrequenz $\omega = 1$ und die Fourier-Koeffizienten $c_0 = 0$, $c_k = \frac{1}{k^5}$ für $k \neq 0$.

Für die Funktion $g$ gilt:
$$ g(x) = f(2x - 3) = \sum_{k \in \mathbb{Z} \setminus \{0\}} \frac{e^{ik(2x-3)}}{k^5} = \sum_{k \in \mathbb{Z} \setminus \{0\}} \frac{e^{-3ik}}{k^5} e^{2ikx} $$
Nun besitzt $g$ aufgrund der Streckung „$2x$“ also im Vergleich zu $f$ die halbe Periode $\hat{T} = \pi$ bzw. die doppelte Kreisfrequenz $\hat{\omega} = 2$. Ferner erzeugt die Verschiebung „$-3$“ einen zusätzlichen Faktor $e^{-3ik}$ in den Fourier-Koeffizienten. Diese können wir direkt ablesen und wir erhalten für $g$ die Fourier-Koeffizienten $\hat{c}_0 = 0$ und $\hat{c}_k = \frac{1}{k^5} e^{-3ik}$ für $k \neq 0$. Für die Darstellung der Fourier-Reihe $S_g$ ergibt sich daher
$$ S_g(x) = g(x) = \sum_{k \in \mathbb{Z} \setminus \{0\}} \frac{e^{-3ik}}{k^5} e^{2ikx}. $$
Wir betrachten nun die Funktion $h$. Es gilt:
$$ g(-x) = \sum_{k \in \mathbb{Z} \setminus \{0\}} \frac{e^{-3ik}}{k^5} e^{-2ikx} = \sum_{k \in \mathbb{Z} \setminus \{0\}} -\frac{e^{3ik}}{k^5} e^{2ikx} $$
$$ f(4x) = \sum_{k \in \mathbb{Z} \setminus \{0\}} \frac{e^{4ikx}}{k^5} $$
Die Funktion $g(-x)$ ist (ebenso wie $g$) $\pi$-periodisch, $f(4x)$ sogar $\frac{\pi}{2}$-periodisch. Damit besitzt die Funktion $h$ die Periode $\tilde{T} = \pi$ und die Kreisfrequenz $\tilde{\omega} = 2$. Um die zugehörigen Fourier-Koeffizienten $\tilde{c}_k$ von $h$ bestimmen zu können, benötigen wir die Fourier-Koeffizienten $d_k$ und $e_k$ in den zu $\tilde{\omega} = 2$ gehörigen Fourier-Reihen-Darstellungen von $g(-x)$ bzw. von $f(4x)$:
$$ g(-x) = \sum_{k \in \mathbb{Z}} d_k e^{2ikx}, \quad f(4x) = \sum_{k \in \mathbb{Z}} e_k e^{2ikx}. $$
Für $g(-x)$ können wir die Koeffizienten direkt ablesen: Es ist $d_0 = 0$ und $d_k = \hat{c}_{-k} = -\frac{1}{k^5} e^{3ik}$ für $k \neq 0$.
Um die Fourier-Reihe $f(4x) = \sum_{j \in \mathbb{Z} \setminus \{0\}} \frac{e^{4ijx}}{j^5}$ in der Form $\sum_{k \in \mathbb{Z}} e_k e^{2ikx}$ darzustellen, muss $e_0 = 0$, $e_k = \frac{1}{j^5} = \frac{1}{(k/2)^5} = \frac{32}{k^5}$ für gerades $k = 2j \neq 0$ sowie $e_k = 0$ für ungerades $k$ gelten.
Insgesamt erhalten wir die Fourier-Koeffizienten
$$ \tilde{c}_k = d_k + e_k = \begin{cases} 0 & \text{für } k = 0, \\ -\frac{1}{k^5} e^{3ik} + \frac{32}{k^5} & \text{für gerades } k \neq 0, \\ -\frac{1}{k^5} e^{3ik} & \text{für ungerades } k \end{cases} $$
der kombinierten Fourier-Reihe $S_h(x) \equiv \sum_{k \in \mathbb{Z}} \tilde{c}_k e^{2ikx}$.
***
[^5]
# Referenz
## Verknüpfung
### Z 3.1
- [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=11|Bemerkung 1.1.24]] -> in Obsidian umformen
- [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=7|Gleichung 1.7]] -> in Obsidian umformen
- [[202510171810 - Zeitumkehr von Fourierreihen|Zeitumkehr von Fourierreihen]]
- [[202510171810 - Verschiebung im Zeitbereich von Fourierreihen|Verschiebung von Fourierreihen]]
- [[202511072211 - Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen]]
### Z 3.2
- [[202510172010 - Lemma für das Fourierspektrums der Stammfunktion]]
- [[202510172010 - Lemma für Fourierspektrum der Ableitung]]
- [[Fourierkoeffizienten für gerade und ungerade Funktionen]]
### Z 3.3
- [[202510201010 - Periodisches Faltungsprodukt]]
- [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=7|Gleichung 1.7]] -> in Obsidian umformen
- [[202510201610 - Lemma für Glättungseigenschaft der Faltung]]
### H 3.1
- [[202511122211 - Integralgrenzen verschieben|Integralgrenzen verschieben]]
- [[Umrechnungsformeln zwischen reellen und komplexen Fourierkoeffizienten]]
- [[Komplexe Fourierpolynome]]
- [[Konvergenz von Fourierreihen]]
- [[202510172010 - Lemma für Fourierspektrum der Ableitung]]
- [[Fourierkoeffizienten für gerade und ungerade Funktionen]]
- [[202510171810 - Zeitumkehr von Fourierreihen|Zeitumkehr von Fourierreihen]]
- [[202510171810 - Linearität von Fourierreihen|Linearität von Fourierreihen]]
- [[202510172010 - Lemma für das Fourierspektrums der Stammfunktion]]
- [[202511072211 - Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen]]
### H 3.2
- [[202510172010 - Lemma für Fourierspektrum der Ableitung]]
- [[202510262010 - Diracsche Delta-Funktion|Diracsche Delta-Funktion]]
- [[Umrechnungsformeln zwischen reellen und komplexen Fourierkoeffizienten]]
### H 3.3
- [[202510180010 - Beschränktheit und Abklingverhalten der Fourierkoeffizienten]] (iii)
- [[202511131911 - Glattheit einer Funktion]]
## Quelle
- [[tum_analysis3_Blatt03.pdf]] -> [[tum_analysis3_Blatt03_lsg.pdf]] 
- [[tum_analysis3_ZÜ03-bearbeitung.pdf]]
- [[tum_analysis3_blatt03-bearbeitung-ben-kostka.pdf]]
- [[tum_analysis3_Tutorium 3 - Analysis 3 (EI).pdf]]

[^1]: [[tum_analysis3_Blatt03_lsg.pdf#page=5]]

[^2]: [[tum_analysis3_Blatt03_lsg.pdf#page=7]]

[^3]: [[tum_analysis3_Blatt03_lsg.pdf#page=9]]

[^4]: [[tum_analysis3_Blatt03_lsg.pdf#page=10]]

[^5]: [[tum_analysis3_Blatt03_lsg.pdf#page=12]]

