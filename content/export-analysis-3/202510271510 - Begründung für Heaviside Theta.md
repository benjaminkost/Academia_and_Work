---
"created date:": 22.10.2025 14:57
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510261910 - Erweiterung der Funktionenklasse|Erweiterung der Funktionenklasse]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Begründung für Heaviside Theta
  - Begründung 1.2.33
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Wir berechnen zuerst (für $c > 0$) die Spektraldichte der Funktion $g_c(t) := \frac{1}{2}\text{sign}(t)e^{-c|t|}$. Es gilt analog wie oben
$$
\begin{align*}
\hat{g_c}(\omega) &= -\frac{1}{2} \int_{-\infty}^{0} e^{ct}e^{-i\omega t} dt + \frac{1}{2} \int_{0}^{\infty} e^{-ct}e^{-i\omega t} dt \\
&= \frac{1}{2} \left( \frac{-1}{c - i\omega} + \frac{1}{c + i\omega} \right) \\
&= -\frac{i\omega}{c^2 + \omega^2}
\end{align*}
$$
und damit
$$
\hat{\theta_n}(\omega) = \widehat{g_{1/n}}(\omega) + \frac{1}{2}\hat{1}(\omega) = \pi\delta(\omega) - \frac{i\omega}{1/n^2 + \omega^2} \to \pi\delta(\omega) + 
\begin{cases} 
0 & \omega = 0 \\
1/(i\omega) & \text{sonst},
\end{cases}
$$
für $n \to \infty$, wie behauptet.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=47]]
	


