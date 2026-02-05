---
"created date:": 17.10.2025 15:15
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
  - "[[eigenschaften von fourierreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen
  - Lemma 1.1.40
parent:
siblings:
child:
proof: "[[202510172310 - Beweis für Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen]]"
---
# Lemma
Sei $f : \mathbb{R} \to \mathbb{C}$ T-periodisch mit Fourierspektrum $\{c_k\}_{k\in\mathbb{Z}}$. Sei $f$ stückweise stetig, habe auf $[0, T)$ die Sprungstellen $0 \le t_1 < \dots < t_N < T$ und sei dazwischen stetig differenzierbar (das ist etwas schwächer als stückweise stetige Differenzierbarkeit). Setze
$$\Delta_j = f(t_j^+) - f(t_j^-).$$
Sei $f'$ die Ableitung (definiert nur außerhalb der Sprungstellen, also auf $[0, T]\setminus\{t_1, \dots, t_N\}$, und periodisch fortgesetzt). Das Fourierspektrum $\{d_k\}_{k\in\mathbb{Z}}$ der Funktion
$$t \to f'(t) \quad \text{ist} \quad d_k = ik\omega c_k - \frac{1}{T} \sum_{j=1}^N \Delta_j e^{-ik\omega t_j} \quad \text{für alle } k \in \mathbb{Z}.$$
[^1]

# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510210410 - Bemerkung 1.1.42 für Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=17]]



