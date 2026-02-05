---
"created date:": 14.01.2025 18:05
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[202510261910 - Erweiterung der Funktionenklasse|Erweiterung der Funktionenklasse]]"
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[machine learning]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Heaviside Theta
  - Beispiel 1.2.33
  - Stufenfunktion
  - Heaviside Funktion
parent:
siblings:
child:
proof: "[[202510271510 - Begründung für Heaviside Theta]]"
---
# Beispiel
Die Funktion
$$
\theta(t) = 
\begin{cases} 
0 & t < 0 \\
1/2 & t = 0 \\
1 & t > 0 
\end{cases}
$$
heißt Heaviside Theta-Funktion. Ähnlich wie mit $\delta$-Folgen können wir
$$
\theta(t) = \lim_{n\to\infty} \theta_n(t) \quad \text{mit} \quad \theta_n(t) = \frac{1}{2}(\tanh(tn) + 1)
$$
als Grenzwert stetiger Funktionen auffassen. Eine alternative Funktionenfolge $\{\theta_n : \mathbb{R} \to \mathbb{R}\}_{n \in \mathbb{N}}$ mit $\theta(t) = \lim_{n\to\infty} \theta_n(t)$ für alle $t \in \mathbb{R}$ ist
$$
\theta_n(t) = \frac{1}{2}\text{sign}(t)e^{-|t|/n} + \frac{1}{2},
$$
siehe Abbildung 6. Die Fouriertransformierte von $\theta$ ist
$$
\hat{\theta}(\omega) = \pi\delta(\omega) + 
\begin{cases} 
0 & \text{für } \omega = 0 \\
1/(i\omega) & \text{für } \omega \neq 0.
\end{cases}
$$
![[Bildschirmfoto 2025-10-22 um 14.56.42.png|400]]


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



