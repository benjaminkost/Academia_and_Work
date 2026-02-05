---
"created date:": 22.10.2025 11:23
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510241010 - Hilbertraum|Hilbertraum]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Äquivalente Bedingungen für Vollständigkeit
  - Beweis 1.1.68
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Beweis. (i)⇒ (ii): Wir zeigen zuerst die Existenz des Grenzwertes $\lim_{n \to \infty} \sum_{k=-n}^n \langle e_k, f \rangle \cdot e_k$. Dazu sei $S_f^n = \sum_{k=-n}^n \langle e_k, f \rangle \cdot e_k$ die n-te Partialsumme. Sei oEdA $n \ge m$. Dann gilt
$$ \| S_f^n - S_f^m \|^2 = \left\| \sum_{k=m+1}^n (\langle e_k, f \rangle \cdot e_k + \langle e_{-k}, f \rangle \cdot e_{-k}) \right\|^2 $$
$$ = \sum_{k=m+1}^n (|\langle e_k, f \rangle|^2 + |\langle e_{-k}, f \rangle|^2) \le \sum_{k=m+1}^{\infty} (|\langle e_k, f \rangle|^2 + |\langle e_{-k}, f \rangle|^2) $$
weil $\{e_n\}_{n \in \mathbb{Z}}$ orthonormal sind. Wegen der Besselschen Ungleichung (siehe Bemerkung 1.1.63) folgt
$$ \| S_f^n - S_f^m \| \to 0 \quad \text{für } m \to \infty. $$
Also ist $\{S_f^n\}_{n \in \mathbb{N}}$ eine Cauchyfolge und daher konvergent (weil ein Hilbertraum vollständig ist), wie behauptet.
Sei jetzt $S = \lim_{n \to \infty} S_f^n$ der Grenzwert. Dann gilt (wegen der Stetigkeit des Skalarproduktes)
$$ \langle e_j, S - f \rangle = \lim_{n \to \infty} \langle e_j, S_f^n - f \rangle = \lim_{n \to \infty} \sum_{k=-n}^n \langle e_j, \langle e_k, f \rangle \cdot e_k \rangle - \langle e_j, f \rangle $$
$$ = \langle e_j, f \rangle - \langle e_j, f \rangle = 0, \quad \text{für jedes } j \in \mathbb{Z}, $$
also $S - f = 0$ wegen der Vollständigkeit von $\{e_k\}_{k \in \mathbb{Z}}$.

(ii)⇒(iii): Weil die Folge $\{S_f^n\}_{n \in \mathbb{N}}$ nach Annahme gegen $f$ konvergiert, gilt wegen der Stetigkeit der Norm
$$ \|f\|^2 = \lim_{n \to \infty} \|S_f^n\|^2 = \lim_{n \to \infty} \left\| \sum_{k=-n}^n \langle e_k, f \rangle \cdot e_k \right\|^2 $$
$$ = \lim_{n \to \infty} \sum_{k=-n}^n |\langle e_k, f \rangle|^2 = \sum_{k \in \mathbb{Z}} |\langle e_k, f \rangle|^2 $$
wie behauptet.

(iii)⇒(i) Sei $f \in \mathcal{H}$ beliebig mit $\langle e_k, f \rangle = 0$ für alle $k \in \mathbb{Z}$. Dann gilt nach (iii)
$$ \|f\|^2 = \sum_{k \in \mathbb{Z}} |\langle e_k, f \rangle|^2 = 0, $$
also $f=0$ weil die Norm $\|\cdot\|$ positiv definit ist. Dies zeigt, dass das Orthonormalsystem $\{e_k\}_{k \in \mathbb{Z}}$ vollständig ist.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=31]]


