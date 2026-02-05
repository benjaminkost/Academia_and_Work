---
"created date:": 22.10.2025 14:30
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Dirac-Folgen und Grenzwertverhalten
parent:
siblings:
child:
mathematical statement: "[[202510270110 - Dirac-Folgen und Grenzwertverhalten|Dirac-Folgen und Grenzwertverhalten]]"
---
# Beweis
Beweis. Sei $c > 0$ beliebig. Dann ist
$$ g_c(t) := \frac{1}{\pi}\frac{c}{c^2+t^2} = \frac{1}{2\pi}\left(\frac{1}{c-it} + \frac{1}{c+it}\right). $$
Es gilt
$$ \int_0^{\infty} e^{-c\omega}e^{i\omega t}d\omega = \int_0^{\infty} e^{(-c+it)\omega}d\omega = \left[\frac{e^{(-c+it)\omega}}{-c+it}\right]_{\omega=0}^{\infty} = \frac{1}{c-it} $$
sowie
$$ \int_{-\infty}^0 e^{c\omega}e^{i\omega t}d\omega = \left[\frac{e^{(c+it)\omega}}{c+it}\right]_{\omega=-\infty}^0 = \frac{1}{c+it} $$
also
$$ \frac{1}{2\pi}\int_{-\infty}^{\infty} e^{-c|\omega|}e^{i\omega t}d\omega = g_c(t). $$
Aus dem Umkehrsatz folgt daraus, dass
$$ \hat{g_c}(\omega) = e^{-c|\omega|} \quad \text{für alle } \omega \in \mathbb{R}, $$
also
$$ \hat{\delta_n}(\omega) = \widehat{g_{1/n}}(\omega) = e^{-|\omega|/n} \quad \text{für alle } \omega \in \mathbb{R}. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=46]]


