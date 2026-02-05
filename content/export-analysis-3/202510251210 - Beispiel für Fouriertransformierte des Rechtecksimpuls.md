---
"created date:": 22.10.2025 11:45
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - definition
  - baby
aliases:
  - Beispiel für Fouriertransformierte des Rechtecksimpuls
  - Beispiel 1.2.6
parent:
siblings:
child:
---
# Beispiel
Als Beispiel betrachten wir den Rechtecksimpuls
$$ r(t) := \begin{cases} 1 & \text{für } t \in [-1, 1] \\ 0 & \text{sonst} \end{cases}. $$
Seine Spektraldichte ist
$$ \hat{r}(\omega) = \int_{-1}^1 e^{-i\omega t} dt = \left[ \frac{1}{(-i\omega)} e^{-i\omega t} \right]_{t=-1}^1 = \frac{2\sin(\omega)}{\omega} \quad \text{für } \omega \neq 0, $$
und
$$ \hat{r}(0) = \int_{-1}^1 1 dt = 2. $$
Offenbar ist $\hat{r}$ stetig bei 0 (dies folgt auch aus Lemma 1.2.5).
Die inverse Fouriertransformierte der Funktion[^2] $\hat{r}$ ist
$$ \check{\hat{r}}(t) = \frac{2}{2\pi} \int_{-\infty}^{\infty} \frac{\sin(\omega)}{\omega} e^{i\omega t} d\omega = \frac{2}{2\pi} \int_{-\infty}^{\infty} \frac{\sin(\omega) \cos(\omega t)}{\omega} d\omega + \frac{2i}{2\pi} \int_{-\infty}^{\infty} \frac{\sin(\omega)\sin(\omega t)}{\omega} d\omega. $$
Es gilt $\int_{-\infty}^{\infty} \frac{\sin(\omega) \sin(\omega t)}{\omega} d\omega = 0$ weil der Integrand ungerade ist. Für das erste Integral erhalten wir mit der Identität
$$ 2\sin(x)\cos(y) = \sin(x+y)+\sin(x-y) $$
angewandt auf $x = \omega$ und $y = t\omega$ den Ausdruck
$$ \frac{1}{\pi} \int_{-\infty}^{\infty} \frac{\sin(\omega) \cos(\omega t)}{\omega} d\omega = \frac{1}{2\pi} \int_{-\infty}^{\infty} \frac{\sin[\omega(1-t)] + \sin[\omega(1+t)]}{\omega} d\omega = \begin{cases} 1 & |t| < 1 \\ 1/2 & |t| = 1 \\ 0 & |t| > 1 \end{cases}, $$
denn das sogenannte Dirichlet-Integral ist
$$ \int_{-\infty}^{\infty} \frac{\sin(a\omega)}{\omega} d\omega = \int_{-\infty}^{\infty} \frac{\sin(as)}{as} d(as) = \begin{cases} \pi & \text{für } a > 0 \\ 0 & \text{für } a = 0 \\ -\pi & \text{für } a < 0. \end{cases} $$
Bis auf die Sprungstellen ist also $\check{\hat{r}}$ gleich $r$, und an den Sprungstellen $t \in \{\pm1\}$ gilt $\frac{1}{2}(r(t^-) + r(t^+)) = \check{\hat{r}}(t)$.
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

[^1]: [[tum_KoenigUlbrich-Analysis3EI-WS2526-skript.pdf#page=35

[^2]: Die Funktion $\hat{r}$ ist zwar nicht absolut integrierbar; in diesem Fall läßt sich aber trotzdem die inverse Fouriertransformierte problemlos berechnen.




