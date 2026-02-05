---
"created date:": 17.10.2025 15:28
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[eigenschaften von fourierreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Beweis für Beschränktheit und Abklingverhalten der Fourierkoeffizienten
parent:
siblings:
child:
---
# Beweis
 Ist ${f}$ stückweise stetig mit endlich vielen Sprungstellen auf ${[0, T]}$, dann ist ${f}$ beschränkt, d.h. es existiert eine Konstante ${C > 0}$ so dass
${|f(t)| \le C \quad \text{für alle } t \in [0, T].}$
Damit folgt
${|c_k| = \left| \frac{1}{T} \int_0^T f(t)e^{-ik\omega t} dt \right| \le \frac{1}{T} \int_0^T |f(t)| dt \le C,}$
für jedes ${k \in \mathbb{Z}}$, also (i).
Betrachte (ii). Aus Lemma 1.1.40 folgt
${d_k = ik\omega c_k - \frac{1}{T} \sum_{j=1}^N \Delta_j e^{-ik\omega t_j}}$
und damit (wegen der Annahme (1.18))
${|c_k| = \frac{1}{|ik\omega|} \cdot \left| d_k + \frac{1}{T} \sum_{j=1}^N \Delta_j e^{-ik\omega t_j} \right| \le \frac{1}{|k|\omega} \left( |d_k| + \frac{1}{T} \sum_{j=1}^N |\Delta_j| \right) =: \frac{C}{|k|}.}$
Für den Beweis von (iii) sei ${c_k^{(\ell)}}$ der k-te Fourierkoeffizient der ${\ell}$-ten Ableitung ${f^{(\ell)}}$. Dann gilt nach Lemma 1.1.36
$${
\begin{aligned}
c_k^{(1)} &= ik\omega c_k \\
c_k^{(2)} &= ik\omega c_k^{(1)} = -k^2\omega^2 c_k \\
\vdots \\
c_k^{(m-1)} &= ik\omega c_k^{(m-2)} = \ldots = (ik\omega)^{m-1}c_k. \quad (1.19)
\end{aligned}
}$$
Außerdem gilt mit Lemma 1.1.40
${c_k^{(m)} = ik\omega c_k^{(m-1)} - \frac{1}{T} \sum_{j=1}^N \Delta_j^{(m-1)} e^{-ik\omega t_j}, \quad (1.20)}$
wobei ${\{t_j\}_{j=1}^T}$ die Sprungstellen von ${f^{(m-1)}}$ sind und
${\Delta_j^{(m-1)} = f^{(m-1)}(t_j^+) - f^{(m-1)}(t_j^-).}$
Einsetzen von (1.20) in (1.19) und Auflösen nach ${c_k}$ liefert für ${k \ne 0}$
${c_k = \frac{1}{(ik\omega)^m} \left( c_k^{(m)} + \frac{1}{T} \sum_{j=1}^N \Delta_j^{(m-1)} e^{-ik\omega t_j} \right).}$
Die Behauptung folgt nun daraus, dass (wegen (i)) die ${c_k^{(m)}}$ beschränkt sind weil ${f^{(m)}}$ stückweise stetig ist. ☐

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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=19]]



