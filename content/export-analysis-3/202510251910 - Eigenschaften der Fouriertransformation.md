---
"created date:": 22.10.2025 14:35
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[eigenschaften von fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[202510270510 - Laplace-Transformation|Laplace-Transformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Eigenschaften der Fouriertransformation
  - Lemma 1.2.11
parent:
siblings:
child:
proof: "[[202510252010 - Beweis für Eigenschaften der Fouriertransformation]]"
---
# Lemma
Es gelten folgende Rechenregeln für die Fouriertransformation.
Seien $f, g \in L^1(\mathbb{R})$, $\alpha, \beta \in \mathbb{C}$ und $a, \theta, c \in \mathbb{R}$ beliebig. Dann gilt

(i) (Linearität)
$$ \widehat{(\alpha f + \beta g)}(\omega) = \alpha \hat{f}(\omega) + \beta\hat{g}(\omega) \quad \text{für alle } \omega \in \mathbb{R}. $$
(ii) (Komplexkonjugation) Die Spektraldichte der Funktion $t \to \overline{f(t)} := \overline{f(t)}$ ist $\widehat{\overline{f}}(\omega) = \overline{\hat{f}(-\omega)}$ für alle $\omega \in \mathbb{R}$.
(iii) (Zeitumkehr) Die Spektraldichte der Funktion $t \to f(-t)$ ist $\omega \to \hat{f}(-\omega)$.
(iv) (Verschiebung im Zeitbereich) Sei $a \in \mathbb{R}$ beliebig. Die Spektraldichte der Funktion $t \to f_a(t) := f(t+a)$ ist $\hat{f_a}(\omega) = \hat{f}(\omega)e^{i\omega a}$.
(v) (Verschiebung im Spektralbereich=Amplitudenmodulation) Sei $\theta \in \mathbb{R}$ beliebig. Die Spektraldichte der Funktion $t \to f_{\theta}(t) := e^{i\theta t}f(t)$ ist $\hat{f_{\theta}}(\omega) = \hat{f}(\omega - \theta)$.
(vi) (Skalierung) Sei $c \neq 0$. Die Spektraldichte der Funktion $t \to f_c(t) := f(ct)$ ist $\hat{f_c}(\omega) = \frac{1}{|c|}\hat{f}(\omega/c)$.

Beachte, dass (vi) anders ist als bei Fourierreihen, deren Spektrum unter Skalierung invariant bleibt.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=36]]



