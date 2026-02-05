---
"created date:": 22.10.2025 12:20
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[eigenschaften von fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Fouriertransformierte der Gaußschen Glockenkurve
  - Beweis 1.2.19
parent:
siblings:
child:
mathematical statement: "[[202510260710 - Fouriertransformierte der Gaußschen Glockenkurve|Fouriertransformierte der Gaußschen Glockenkurve]]"
---
# Beweis
Beweis. Nach Lemma 1.2.15 hat
$$ t \to f'(t) \quad \text{die Spektraldichte} \quad \omega \to (i\omega)\hat{f}(\omega). $$
Also hat
$$ t \to te^{-t^2/2} \quad \text{die Spektraldichte} \quad \omega \to -(i\omega)\hat{f}(\omega). \quad (1.44) $$
Lemma 1.2.17 angewandt auf $P(z) = z$ zeigt andererseits, dass die Funktion
$$ t \to te^{-t^2/2} \quad \text{die Spektraldichte} \quad \omega \to i\hat{f}'(\omega) \quad (1.45) $$
hat. Mit dem Umkehrsatz (d.h. Eindeutigkeit der Fouriertransformierten) folgt aus (1.44) und (1.45) dass
$$ \frac{d}{d\omega}\hat{f}(\omega) = -\omega \hat{f}(\omega) \quad \text{für alle } \omega \in \mathbb{R}. $$
Lösen dieser Differentialgleichung gibt
$$ \hat{f}(\omega) = \hat{f}(0)e^{-\omega^2/2} \quad \text{für alle } \omega \in \mathbb{R}. \quad (1.46) $$
Außerdem ist
$$ \hat{f}(0) = \int_{-\infty}^{\infty} e^{-t^2/2} dt = \sqrt{2}\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{2\pi} \quad \text{(bekannte Formel)}. \quad (1.47) $$
Aus (1.46) und (1.47) folgt
$$ \hat{f}(\omega) = \hat{f}(0)e^{-\omega^2} = \sqrt{2\pi}e^{-\omega^2/2} \quad \text{für alle } \omega \in \mathbb{R}, $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=40]]


