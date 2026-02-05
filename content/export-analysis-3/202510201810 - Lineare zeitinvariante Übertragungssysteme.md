---
"created date:": 20.10.2025 09:48
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[202510201810 - Lineare zeitinvariante Übertragungssysteme|Lineare zeitinvariante Übertragungssysteme]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Lineare zeitinvariante Übertragungssysteme
  - LTI-Systeme
  - Gleichung 1.22
  - Impulsantwort
  - Frequenzgang
  - Differentialoperator
parent:
siblings:
child:
mathematical statement:
---
# Definition
In der Signal- und Regelungstechnik beschreiben wir oft Systeme, bei denen zwischen dem Eingangssignal $x(t)$ und der Ausgangsgröße $y(t)$ die Beziehung 
$$y(t) = (h * x)(t)  \space \text{für alle} \space t \in \mathbb{R} $$
besteht. Das Verhalten des Systems (für alle möglichen Eingangssignale) ist also vollständig durch eine Funktion $h$ beschrieben. Wir nennen ein derartiges System ein LTI-System.

Die Funktion $h : \mathbb{R} \to \mathbb{C}$ bezeichnen wir als **Impulsantwort**.

Für $T$-periodische Systeme ist $h$ $T$-periodisch, und wir sprechen von der sogenannten $T$-periodischen Impulsantwort
$$ h_T(t) = \sum_{k \in \mathbb{Z}} d_k e^{ik\omega t} $$
Die Fourierkoeffizienten $\{d_k\}_{k \in \mathbb{Z}}$ werden als **Frequenzgang** des Systems bezeichnet.

Im Folgenden seien $a_0, \dots, a_m \in \mathbb{C}$ und $L$ der Differentialoperator
$$ L[y](t) := a_m y^{(m)}(t) + \dots + a_1 y'(t) + a_0 y(t) $$
für $y : \mathbb{R} \to \mathbb{C}$ $m$-mal differenzierbar. Sei
$$ P(z) = a_m z^m + \dots + a_1 z + a_0 \quad (1.22) $$
das zugehörige charakteristische Polynom.[^1]
# Unterthemen
```dataview
LIST 
WHERE contains(mytags, [[]]) AND !contains(mytags, [[aufgaben]])
SORT file.name ASC
```
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=22]]



