---
"created date:": 24.10.2025 09:27
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Beschränktheit und Abklingverhalten der Fourierkoeffizienten
  - Beweis 1.1.41
  - Gleichung 1.20
  - Gleichung 1.19
parent:
siblings:
child:
mathematical statement: "[[202510180010 - Beschränktheit und Abklingverhalten der Fourierkoeffizienten|Beschränktheit und Abklingverhalten der Fourierkoeffizienten]]"
---
# Beweis
Ist $f$ stückweise stetig mit endlich vielen Sprungstellen auf $[0, T]$, dann ist $f$ beschränkt, d.h. es existiert eine Konstante $C > 0$ so dass
$$|f(t)| \le C \quad \text{für alle } t \in [0, T].$$
Damit folgt
$$|c_k| = \left| \frac{1}{T} \int_0^T f(t)e^{-ik\omega t} dt \right| \le \frac{1}{T} \int_0^T |f(t)| dt \le C,$$
für jedes $k \in \mathbb{Z}$, also (i).

Betrachte (ii). Aus [[202511072211 - Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen|Lemma 1.1.40]] folgt
$$d_k = ik\omega c_k - \frac{1}{T} \sum_{j=1}^N \Delta_j e^{-ik\omega t_j}$$
und damit (wegen der Annahme [[202510180010 - Beschränktheit und Abklingverhalten der Fourierkoeffizienten|Gleichung 1.18]])
$$|c_k| = \frac{1}{|ik\omega|} \left| d_k + \frac{1}{T} \sum_{j=1}^N \Delta_j e^{-ik\omega t_j} \right|$$
$$\le \frac{1}{|k|\omega} \left( |d_k| + \frac{1}{T} \sum_{j=1}^N |\Delta_j| \right) =: \frac{C}{|k|}.$$
Für den Beweis von (iii) sei $c_k^{(\ell)}$ der k-te Fourierkoeffizient der $\ell$-ten Ableitung $f^{(\ell)}$. Dann gilt nach [[202510172010 - Lemma für Fourierspektrum der Ableitung|Lemma 1.1.36(i)]]
$$c_k^{(1)} = ik\omega c_k$$
$$c_k^{(2)} = ik\omega c_k^{(1)} = -k^2\omega^2 c_k$$
$$\vdots$$
$$c_k^{(m-1)} = ik\omega c_k^{(m-2)} = \dots = (ik\omega)^{m-1}c_k. \quad (1.19)$$
Außerdem gilt mit [[202511072211 - Fourierspektrum der Ableitung stückweise stetig differenzierbarer Funktionen mit Sprungstellen|Lemma 1.1.40]]
$$c_k^{(m)} = ik\omega c_k^{(m-1)} - \frac{1}{T} \sum_{j=1}^N \Delta_j^{(m-1)} e^{-ik\omega t_j}, \quad (1.20)$$
wobei $\{t_j\}_{j=1}^T$ die Sprungstellen von $f^{(m-1)}$ sind und
$$\Delta_j^{(m-1)} = f^{(m-1)}(t_j^+) - f^{(m-1)}(t_j^-).$$
Einsetzen von (1.20) in (1.19) und Auflösen nach $c_k$ liefert für $k \neq 0$
$$c_k = \frac{1}{(ik\omega)^m} \left( c_k^{(m)} + \frac{1}{T} \sum_{j=1}^N \Delta_j^{(m-1)} e^{-ik\omega t_j} \right).$$
Die Behauptung folgt nun daraus, dass (wegen (i)) die $c_k^{(m)}$ beschränkt sind weil $f^{(m)}$ stückweise stetig ist.
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


