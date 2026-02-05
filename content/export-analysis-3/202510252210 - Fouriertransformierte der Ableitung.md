---
"created date:": 22.10.2025 12:09
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
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Fouriertransformierte der Ableitung
  - Lemma 1.2.13
parent:
siblings:
child:
proof: "[[202510252310 - Beweis für Fouriertransformierte der Ableitung]]"
---
# Lemma
Sei $f \in L^1(\mathbb{R})$ stückweise stetig mit endlich vielen Sprungstellen $t_1 < t_2 < \dots < t_N$ und dazwischen stetig differenzierbar mit $f' \in L^1(\mathbb{R})$ (wobei $f'(t)$ nur außerhalb der Sprungstellen $t_j$ von $f$ definiert ist). Dann hat $f'$ die Spektraldichte
$$ \widehat{f'}(\omega) = i\omega \hat{f}(\omega) - \sum_{k=1}^N (f(t_k^+) - f(t_k^-))e^{-i\omega t_k} \quad \text{für alle } \omega \in \mathbb{R}. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=38]]


