---
"created date:": 22.10.2025 11:38
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - definition
  - baby
aliases:
  - Fouriertransformation
  - Definition 1.2.1
parent:
siblings:
child:
---
# Definition
Sei $f : \mathbb{R} \to \mathbb{C}$ gegeben.

(i) Die Fouriertransformierte von $f$ ist
$$ \hat{f} : \mathbb{R} \to \mathbb{C} $$
$$ \omega \to \hat{f}(\omega) := \int_{-\infty}^{\infty} f(t)e^{-i\omega t} dt. $$
Die Funktion $\omega \to \hat{f}(\omega)$ heißt kontinuierliches Spektrum oder Spektraldichte von $f$.

(ii) Die inverse Fouriertransformierte von $f$ ist
$$ \check{f} : \mathbb{R} \to \mathbb{C} $$
$$ t \to \check{f}(t) := \frac{1}{2\pi} \int_{-\infty}^{\infty} f(\omega)e^{i\omega t} d\omega. $$
[^1]

# Oberthema
```dataview
LIST
WHERE contains(mytags, [[]])
SORT file.name ASC
```

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=33]]




