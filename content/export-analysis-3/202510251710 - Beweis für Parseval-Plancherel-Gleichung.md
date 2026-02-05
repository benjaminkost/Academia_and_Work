---
"created date:": 22.10.2025 12:02
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Integraltransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[202510261710 - Produktregel für die Faltung|Produktregel für die Faltung]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Beweis für Parseval-Plancherel-Gleichung
  - Theorem 1.2.9
parent:
siblings:
child:
mathematical statement: "[[202510251610 - Parseval-Plancherel-Gleichung|Parseval-Plancherel-Gleichung]]"
---
# Beweis
Als Anwendung von [[202510261510 - Faltungssatz|Lemma 1.2.26]] geben wir einen Beweis der Parseval-Plancherel-Gleichung (1.41), also
$$ \frac{1}{2\pi} \int_{-\infty}^{\infty} |\hat{f}(\omega)|^2 d\omega = \int_{-\infty}^{\infty} |f(t)|^2 dt. $$
Beweis. Sei $f \in L^1(\mathbb{R}) \cap L^2(\mathbb{R})$ gegeben. Wir setzen
$g(t) := \overline{f(-t)}$ für $t \in \mathbb{R}$.
Dann gilt
$$ (g*f)(0) = \int_{-\infty}^{\infty} g(-s)f(s)ds = \int_{-\infty}^{\infty} \overline{f(s)}f(s)ds = \int_{-\infty}^{\infty} |f(s)|^2 ds. \quad (1.50) $$
Setzen wir $h(t) := f(-t)$, dann ist $g=\bar{h}$ und die Fouriertransformierte von $g$ ist
$$ \hat{g}(\omega) = \overline{\hat{h}(-\omega)} \quad \text{nach Lemma 1.2.11 (ii)} $$
$$ = \overline{\hat{f}(\omega)} \quad \text{nach Lemma 1.2.11 (iii)}, $$
also mit Lemma 1.2.26
$$ \widehat{g*f}(\omega) = \hat{g}(\omega)\hat{f}(\omega) = |\hat{f}(\omega)|^2 \quad \text{für alle } \omega \in \mathbb{R}. $$
Mit dem Umkehrsatz erhalten wir
$$ (g*f)(t) = \frac{1}{2\pi}\int_{-\infty}^{\infty} |\hat{f}(\omega)|^2 e^{i\omega t}d\omega. $$
Auswerten dieser Formel bei $t=0$ und Vergleichen mit (1.50) gibt die Behauptung.
[^2]

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
[^1]: [[tum_KoenigUlbrich-Analysis3EI-WS2526-skript.pdf#page=42



