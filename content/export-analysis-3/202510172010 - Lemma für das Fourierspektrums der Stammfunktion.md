---
"created date:": 17.10.2025 13:42
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[Lemma]]"
  - "[[eigenschaften von fourierreihen]]"
  - "[[analysis 3 formelblatt]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Lemma für das Fourierspektrums der Stammfunktion
  - Gleichung 1.16
  - Lemma 1.1.36(ii)
parent:
siblings:
child:
proof: "[[202510172110 - Beweis für Stammfunktionen als Transformation des Fourierspektrums]]"
---
# Definition
Sei ${f : \mathbb{R} \to \mathbb{C}}$ T-periodisch mit [[202511121311 - Fourierspektrum|Fourierspektrum]] ${\{c_k\}_{k\in\mathbb{Z}}}$.

(ii) Ist ${f}$ stückweise stetig und
${c_0 = \frac{1}{T} \int_0^T f(t) dt = 0}$. (1.16)

Dann gilt: Das Fourierspektrum ${\{d_k\}_{k\in\mathbb{Z}}}$ der Funktion
${t \to F(t) := \int_0^t f(s)ds}$ ist ${d_k = \begin{cases} -\frac{1}{T} \int_0^T tf(t)dt & \text{für } k=0 \\ \frac{c_k}{ik\omega} & \text{sonst.} \end{cases}}$.[^1]
# Beispiele


# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202510210310 - Bemerkung 1.1.38 für das Fourierspektrums der Stammfunktion]]
- [[202510172010 - Lemma für Fourierspektrum der Ableitung|Lemma für Fourierspektrum der Ableitung]]
## Quellen
[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=16]]



