---
"created date:": 22.10.2025 10:54
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Fourierreihe]]"
  - "[[Integraltransformation]]"
  - "[[202510241010 - Hilbertraum|Hilbertraum]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Prä-Hilbertraum stückweise stetiger Funktionen
  - Definition 1.1.58
parent:
siblings:
child:
---
# Definition
Sei $T > 0$. Wir betrachten den komplexen [[Vektorraum]]
$$ \mathcal{V} := \{f : [0, T] \to \mathbb{C} \mid f \text{ stückweise stetig}\}, $$
wobei (Vektor)Addition und skalare Multiplikation hier punktweise definiert sind, also
$$ (f+g)(t) := f(t) + g(t) \quad \text{für alle } t \in \mathbb{R} \text{ und } f, g \in \mathcal{V} $$
$$ (\alpha f)(t) := \alpha f(t) \quad \text{für alle } \alpha \in \mathbb{C} \text{ und } f \in \mathcal{V} $$
Definiere zusätzlich
$$ \langle f, g \rangle := \frac{1}{T} \int_0^T f(t)\overline{g(t)}dt \quad \text{für } f, g \in \mathcal{V}. $$
Dann ist $\mathcal{V}$ mit $\langle \cdot, \cdot \rangle$ ein Prä-Hilbertraum („Prä“, da der Raum nicht vollständig ist)[^1].
Es kann gezeigt[^2] werden, dass Definition (1.1.58) die Eigenschaften eines [[202510241010 - Hilbertraum|Hilbertraum]]s erfüllt: z.B. folgt die [[Skalarprodukten - Positive Definitheit als Eigenschaft|Positive Definitheit]] des Skalarproduktes aus
$$ \langle f, f \rangle = \frac{1}{T} \int_0^T |f(t)|^2 dt \ge 0. $$
[^3]
# Beispiele


# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[Skalarprodukt für komplexe Zahlen]]
- [[Standardnorm|euklidische Norm]]
- [[202511080211 - Stückweise Stetigkeit|stückweise stetig]]
- [[202510241110 - Beispiel Hilbertraum in C]]
- [[Cauchy-Schwarzsche Ungleichung]]
- [[202510241110 - Beispiel Hilbertraum in C|Beispiel 1.1.57]]
## Quellen
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V8.pdf#page=3]]

[^1]: Es müssten zusätzlich einige Details behandelt werden, die wir hier nicht vertiefen wollen. Insbesondere ist $\mathcal{V}$ nicht vollständig, sondern die Vervollständigung von $\mathcal{V}$ ist der Hilbertraum $L^2(0,T)$ der quadratintegrierbaren Funktionen. Zudem müssen die Funktionswerte an Sprungstellen geeignet festgelegt werden (z.B. als Mittelwert $f(t) = (f(t^+) + f(t^-))/2$), um sichzustellen, dass $\|f-g\| = 0$ gleichbedeutend mit $f(t) = g(t)$ für alle $t$ ist.

[^2]: Wieder unter Berücksichtigung der hier nicht behandelten zusätzlichen Details.

[^3]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=26]]



