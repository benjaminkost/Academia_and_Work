---
"created date:": 24.10.2025 09:26
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Lemma]]"
  - "[[eigenschaften von fourierreihen]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Beschränktheit und Abklingverhalten der Fourierkoeffizienten
  - Lemma 1.1.41
  - Gleichung 1.18
parent:
siblings:
child:
proof:
  - "[[202511080311 - Beweis für Beschränktheit und Abklingverhalten der Fourierkoeffizienten|Beweis für Beschränktheit und Abklingverhalten der Fourierkoeffizienten]]"
in own words: "[[202511132011 - Beschränktheit und Abklingverhalten der Fourierkoeffizienten in eigenen Worten]]"
---
# Lemma
Sei $f : \mathbb{R} \to \mathbb{C}$ eine T-periodische Funktion und $\{c_k\}_{k\in\mathbb{Z}}$ das [[202511121311 - Fourierspektrum|Fourierspektrum]] von $f$.

(i) Sei stückweise stetig mit höchstens endlich vielen Sprungstellen $0 \le t_1 < \dots < t_N < T$ auf $[0, T]$. Dann sind die [[Fourierkoeffizient]]en [[Beschränkte Menge|beschränkt]], d.h. es gibt eine Konstante so dass
$$|c_k| \le C \quad \text{für alle } k \in \mathbb{Z}.$$

(ii) Angenommen $f$ sei [[202511080211 - Stückweise Stetigkeit|stückweise stetig]] mit endlich vielen [[Sprungstelle]]n $0 \le t_1 < \dots < t_N < T$, und dazwischen stetig [[6 - Atomic Notes/Differenzierbarkeit|differenzierbar]]. Weiter seien die Fourierkoeffizienten $\{d_k\}_{k\in\mathbb{Z}}$ von $f'$ beschränkt, d.h. es existiert eine Konstante $M > 0$ so dass
$$|d_k| \le M \quad \text{für alle } k \in \mathbb{Z}\setminus\{0\}. $$
(1.18)

Dann gibt es eine Konstante $C > 0$ so dass
$$|c_k| \le \frac{C}{|k|} \quad \text{für alle } k \in \mathbb{Z}\setminus\{0\}.$$
(iii) Sei $f$ stetig mit stetigen Ableitungen $f', f'', \dots, f^{(m-2)}$. Sei weiter $f^{(m-1)}$ stückweise stetig differenzierbar. Dann gibt es eine Konstante $C > 0$ so dass
$$|c_k| \le \frac{C}{|k|^m} \quad \text{für alle } k \in \mathbb{Z}\setminus\{0\}.$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=18]]



