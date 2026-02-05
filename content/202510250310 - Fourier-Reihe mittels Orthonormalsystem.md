---
"created date:": 22.10.2025 11:27
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510250310 - Fourier-Reihe mittels Orthonormalsystem|Fourier-Reihe mittels Orthonormalsystem]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Fourier-Reihe mittels Orthonormalsystem
parent:
siblings:
child:
---
# Definition
Aus der Vollständigkeit des Orthonormalsystems $\{t \to e_k(t) = e^{ik\omega t}\}_{k \in \mathbb{Z}}$ (Lemma 1.1.67) und Theorem 1.1.68 schließen wir, dass für jede stückweise stetige T-periodische Funktion $f : \mathbb{R} \to \mathbb{C}$ mit Fourierspektrum $\{c_k\}_{k \in \mathbb{Z}}$ gilt
$$ \lim_{n \to \infty} \frac{1}{T} \int_0^T \left| f(t) - \sum_{k=-n}^n c_k e^{ik\omega t} \right|^2 dt \to 0 \quad \text{für } n \to \infty, \quad (1.34) $$
denn die linke Seite ist gleich $\lim_{n \to \infty} \| f - S_f^n \|^2$. Wir bezeichnen (1.34) als Konvergenz der Fourierreihe im quadratischen Mittel. Die Fourierkoeffizienten erfüllen die Parseval-Bessel-Gleichung
$$ \sum_{k \in \mathbb{Z}} |c_k|^2 = \frac{1}{T} \int_0^T |f(t)|^2 dt $$
wegen der Parseval-Identität und $c_k = \langle e_k, f \rangle$. Außerdem gilt folgende Eindeutigkeitseigenschaft der Fourierreihe: sind $f, g$ stetig mit identischen Fourierkoeffizienten, dann gilt $f(t) = g(t)$ für alle $t \in \mathbb{R}$. Dies folgt aus der Vollständigkeit des Orthonormalsystems und der Annahme, die impliziert, dass $\langle e_k, f-g \rangle = 0$ für alle $k \in \mathbb{Z}$.
[^1]

# Beispiele


# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510250410 - Punktweise Konvergenz]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=32]]



