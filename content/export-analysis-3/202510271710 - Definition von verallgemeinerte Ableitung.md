---
"created date:": 22.10.2025 15:12
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Integraltransformation]]"
  - "[[Orthogonalreihen]]"
  - "[[202510270310 - Oberthema für verallgemeinerte Ableitungen|Verallgemeinerte Ableitungen]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Definition 1.2.34
  - Definition von verallgemeinerte Ableitung
parent:
siblings:
child:
---
# Definition
Sei $f : \mathbb{R} \to \mathbb{C}$ mit folgenden Eigenschaften:
(i) $f'(t)$ existiert für alle $t \notin \{t_1 < \dots < t_N \}$, also in allen außer endlich vielen Punkten.
(ii) Die einseitigen Grenzwerte $f(t_j^+)$ und $f(t_j^-)$ existieren für alle $j \in \{1, \dots, N\}$.

Dann ist die verallgemeinerte Ableitung $Df$ von $f$ definiert als
$$
Df(t) = f'(t) + \sum_{j=1}^{N} \left( f(t_j^+) - f(t_j^-) \right) \delta(t-t_j),
$$
wobei wir hier $f'(t) = 0$ für $t \in \{t_1, \dots, t_N\}$ setzen.
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
- 
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=48]]



