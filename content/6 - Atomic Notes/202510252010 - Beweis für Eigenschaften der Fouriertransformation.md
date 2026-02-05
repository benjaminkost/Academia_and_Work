---
"created date:": 22.10.2025 12:07
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[eigenschaften von fouriertransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Eigenschaften der Fouriertransformation
  - Beweis 1.2.11
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Beweis. Aussage (i) folgt wieder direkt aus der Linearität des Integrals und der Definition der Fouriertransformierten.
Für (ii) berechnen wir
$$ \widehat{\overline{f}}(\omega) = \int_{-\infty}^{\infty} \overline{f(t)} e^{-i\omega t} dt = \overline{\int_{-\infty}^{\infty} f(t) e^{i\omega t} dt} = \overline{\hat{f}(-\omega)} \quad \text{für alle } \omega \in \mathbb{R}. $$
Analog folgt (iii) mittels der Variablensubstitution $\tau = -t$: wir haben
$$ \int_{-\infty}^{\infty} f(-t)e^{-i\omega t} dt = -\int_{\infty}^{-\infty} f(\tau)e^{i\omega \tau} d\tau = \int_{-\infty}^{\infty} f(\tau)e^{i\omega \tau} d\tau = \hat{f}(-\omega) \quad \text{für alle } \omega \in \mathbb{R}. $$
Für Eigenschaft (iv) verwenden wir $e^{-i\omega(\tau - a)} = e^{-i\omega\tau}e^{i\omega a}$, also mit der Substitution $\tau = t+a$
$$ \int_{-\infty}^{\infty} f(t+a)e^{-i\omega t} dt = \int_{-\infty}^{\infty} f(\tau)e^{-i\omega(\tau - a)} d\tau = e^{i\omega a}\int_{-\infty}^{\infty} f(\tau)e^{-i\omega\tau} d\tau = e^{i\omega a}\hat{f}(\omega) \quad \text{für alle } \omega \in \mathbb{R}. $$
Eigenschaft (v) folgt aus
$$ \int_{-\infty}^{\infty} (e^{i\theta t}f(t))e^{-i\omega t} dt = \int_{-\infty}^{\infty} f(t)e^{-i(\omega - \theta)t} dt = \hat{f}(\omega-\theta) \quad \text{für alle } \omega \in \mathbb{R}. $$
Schließlich erhalten wir (vi) mit der Variablensubstitution $\tau = ct$ aus
$$ \int_{-\infty}^{\infty} f(ct)e^{-i\omega t} dt = \int_{-\infty}^{\infty} f(\tau)e^{-i\omega\tau/c} \frac{1}{|c|}d\tau = \frac{1}{|c|}\hat{f}(\omega/c) \quad \text{für alle } \omega \in \mathbb{R}. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=37]]


