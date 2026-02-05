---
"created date:": 20.10.2025 10:01
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510201810 - Lineare zeitinvariante Übertragungssysteme|Lineare zeitinvariante Übertragungssysteme]]"
  - "[[Fourierreihe]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - vl-3
  - baby
aliases:
  - Resonanz für Alternative Charakterisierung der Impulsantwort
parent:
siblings:
child:
mathematical statement:
---
# Resonanz
Ist ([[202510202210 - Lemma für Alternative Charakterisierung der Impulsantwort|Gleichung 1.24]]) nicht erfüllt, also gilt 
$$P (ikω) = 0$$ für gewisse $k \in \mathbb{Z}$
, sprechen wir von **Resonanz**. In diesem Fall gibt es keine Lösung $h$ der Bedingungen *(i)* und *(ii)* von [[202510202210 - Lemma für Alternative Charakterisierung der Impulsantwort|Lemma 1.1.52]].

Im Resonanzfall:
- gibt es $T$-periodische Inputs $x$, die in nicht $T$-periodischen Outputs $y$ resultieren.
- ist die Lösung nicht eindeutig: zu gewissen $T$-periodischen Inputs $x$ gibt es mehrere $T$-periodische Outputs $y$, die $L[y] = x$ erfüllen.[^1]

# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[202511121411 - Beispiel für Resonanzfall]]
## Quellen
- [[tum_analysis3_Ulbrich-Ana3EI-WS2526-V7.pdf#page=8]]

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=25]]




