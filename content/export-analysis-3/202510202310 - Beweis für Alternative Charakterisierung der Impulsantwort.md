---
"created date:": 20.10.2025 09:56
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-3
  - baby
aliases:
  - Beweis für Alternative Charakterisierung der Impulsantwort
  - Beweis 1.1.52
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Es genügt zu zeigen, dass die Fourierkoeffizienten $\{d_k\}_{k\in\mathbb{Z}}$ von $h$ gleich $d_k = 1/P(ik\omega)$ sind. Aus (ii) und [[202510172010 - Lemma für Fourierspektrum der Ableitung|Lemma 1.1.36(i)]] folgt: 

$h^{(s)}$ hat das Fourierspektrum $\{(ik\omega)^s d_k\}_{k\in\mathbb{Z}}$ für jedes $0 \le s \le m-1$.

Mit ([[202510202210 - Lemma für Alternative Charakterisierung der Impulsantwort|Gleichung 1.26]]) und [[202511072211 - Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen|Lemma 1.1.40]] folgt außerdem:
$h^{(m)}$ das Fourierspektrum $\{(ik\omega)^m d_k - \frac{1}{T} \cdot \frac{T}{a_m} e^{-ik\omega 0}\}_{k \in \mathbb{Z}} = \{(ik\omega)^m d_k - \frac{1}{a_m}\}_{k \in \mathbb{Z}}$.

Mit der Definition $L[h] = a_m h^{(m)} + a_{m-1} h^{(m-1)} + \cdots + a_0 h$ schließen wir: 

$L[h]$ hat [[202511121311 - Fourierspektrum|Fourierspektrum]] $\{b_k\}_{k \in \mathbb{Z}}$ wobei $b_k = a_m \left( (ik\omega)^m d_k - \frac{1}{a_m} \right) + a_{m-1}(ik\omega)^{m-1}d_k + \cdots + a_0 d_k = d_k P(ik\omega) - 1$. 

Andererseits wissen wir aus ([[202510202210 - Lemma für Alternative Charakterisierung der Impulsantwort|Gleichung 1.25]]) dass $L[h] = 0$ ist und jeder Fourierkoeffizient der konstanten Funktion $t \mapsto 0$ verschwindet. Somit ist $b_k = 0$, also $d_k = 1/P(ik\omega)$ für jedes $k \in \mathbb{Z}$, wie behauptet.[^1]

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=23]]



