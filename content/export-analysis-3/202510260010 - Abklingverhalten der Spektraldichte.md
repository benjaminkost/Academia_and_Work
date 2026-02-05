---
"created date:": 22.10.2025 12:11
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
  - Abklingverhalten der Spektraldichte
  - Lemma 1.2.14
parent:
siblings:
child:
proof: "[[202510260110 - Beweis für Abklingverhalten der Spektraldichte]]"
---
# Lemma
Sei $f \in L^1(\mathbb{R})$.

(i) Sei $f$ stückweise stetig mit endlich vielen Sprungstellen $t_1 < \dots < t_N$ und dazwischen stetig differenzierbar. Weiter sei $f' \in L^1(\mathbb{R})$ (wobei $f'$ nur außerhalb der Sprungstellen definiert ist). Dann gibt es eine Konstante $C > 0$ so dass
$$ |\hat{f}(\omega)| \le \frac{C}{|\omega|} \quad \text{für } \omega \neq 0, \quad (1.43) $$
also $\hat{f}(\omega) = O(1/|\omega|)$ für $|\omega| \to \infty$.

(ii) Sei $m \in \mathbb{N}$ und $f, f', \dots, f^{(m-2)}$ stetig. Sei weiter $f^{(m-1)}$ stückweise stetig mit endlich vielen Sprungstellen $t_1 < \dots < t_N$ und dazwischen sei $f^{(m-1)}$ stetig differenzierbar. Es gelte $f', \dots, f^{(m)} \in L^1(\mathbb{R})$. Dann gibt es eine Konstante $C > 0$ so dass
$$ |\hat{f}(\omega)| \le \frac{C}{|\omega|^m} \quad \text{für alle } \omega \neq 0. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=39]]


