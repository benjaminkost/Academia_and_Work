---
"created date:": 22.10.2025 11:04
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510241010 - Hilbertraum|Hilbertraum]]"
  - "[[beweise]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Lemma für Satz des Pythagoras und Besselsche Ungleichung
  - Beweis 1.1.62
  - Gleichung 1.30
parent:
siblings:
child:
mathematical statement: "[[202510241610 - Satz des Pythagoras und Besselsche Ungleichung|Satz des Pythagoras und Besselsche Ungleichung]]"
---
# Beweis
Behauptung (i) folgt direkt aus der Definition eines Orthonormalsystems. Um die Idee zu illustrieren, zeigen wir zuerst dass für orthonormale $u, v \in \mathcal{H}$ (also $\|u \|=1, \|v\|=1$ und $\langle u,v \rangle = 0$) und $\alpha, \beta \in \mathbb{C}$ gilt
$$ \| \alpha u + \beta v \|^2 = |\alpha|^2 + |\beta|^2. $$
Tatsächlich ist
$$ \| \alpha u + \beta v \|^2 = \langle \alpha u + \beta v, \alpha u + \beta v \rangle = \alpha\bar{\alpha}\langle u, u \rangle + \alpha\bar{\beta}\langle u, v \rangle + \beta\bar{\alpha}\langle v, u \rangle + \beta\bar{\beta}\langle v, v \rangle = |\alpha|^2 + |\beta|^2. $$
Ganz analog erhalten wir
$$ \left\| \sum_{k=-n}^n \gamma_k e_k \right\|^2 = \left\langle \sum_{j=-n}^n \gamma_j e_j, \sum_{k=-n}^n \gamma_k e_k \right\rangle = \sum_{j=-n}^n \sum_{k=-n}^n \gamma_j \bar{\gamma_k} \langle e_j, e_k \rangle = \sum_{k=-n}^n |\gamma_k|^2. $$
Für (ii) verwenden wir, dass die Norm nichtnegativ (und daher reellwertig) ist und erhalten
$$ 0 \le \left\| f - \sum_{j \in \Omega} \langle e_j, f \rangle e_j \right\|^2 = \left\langle f - \sum_{j \in \Omega} \langle e_j, f \rangle e_j, f - \sum_{k \in \Omega} \langle e_k, f \rangle e_k \right\rangle $$
$$ = \langle f, f \rangle - \sum_{k \in \Omega} \overline{\langle e_k, f \rangle} \langle f, e_k \rangle - \sum_{j \in \Omega} \langle e_j, f \rangle \overline{\langle e_j, f \rangle} + \sum_{j,k \in \Omega} \langle e_j, f \rangle \overline{\langle e_k, f \rangle} \langle e_j, e_k \rangle $$
$$ = \|f\|^2 - \sum_{j \in \Omega} |\langle e_j, f \rangle|^2. $$
Für Behauptung (iii) zeigen wir zuerst
$$ \langle (f - S_f^n), S_f^n \rangle = 0, \quad (1.30) $$
denn
$$ \langle (f - S_f^n), S_f^n \rangle = \sum_{k=-n}^n \bar{c_k} \langle (f - S_f^n), e_k \rangle = \sum_{k=-n}^n \bar{c_k} (\langle f, e_k \rangle - \langle S_f^n, e_k \rangle) = 0 $$
denn $\langle f, e_k \rangle = \langle S_f^n, e_k \rangle = c_k$ für $k \in \{-n, \dots, n\}$. Aus der Identität (1.30) folgt
$$ \|f\|^2 = \langle f, f \rangle = \langle f - S_f^n + S_f^n, f - S_f^n + S_f^n \rangle $$
$$ = \langle f - S_f^n, f - S_f^n \rangle + \langle f - S_f^n, S_f^n \rangle + \langle S_f^n, f - S_f^n \rangle + \langle S_f^n, S_f^n \rangle $$
$$ = \|f - S_f^n\|^2 + \|S_f^n\|^2 $$
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
- [[Skalarprodukt]]
- [[Norm]]
## Quellen
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V8.pdf]]
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V9.pdf]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=28]]


