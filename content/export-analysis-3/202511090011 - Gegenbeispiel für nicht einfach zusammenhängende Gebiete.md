---
"created date:": 29.10.2025 22:18
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202511021711 - Integralsatz von Cauchy|Integralsatz von Cauchy]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - beispiele
aliases:
  - Gegenbeispiel für nicht einfach zusammenhängende Gebiete
  - Beispiel 2.6.3
parent:
siblings:
child:
---
# Beispiel
Die Funktion $z \mapsto 1/z$ ist auf $\mathbb{C}^\times$ komplex differenzierbar (bei 0 ist sie nicht definiert). Wir haben in [[202511011511 - Das Fundamentalintegral|Lemma 2.5.4]] (mit $z_0 = 0$ und $r > 0$ beliebig) berechnet, dass
$$\oint_{|z|=r} \frac{1}{z} dz = 2\pi i \neq 0 .$$
Dies widerspricht [[202511021711 - Integralsatz von Cauchy|Theorem 2.6.1]] nicht, weil $\mathbb{C}^\times$ nicht einfach zusammenhängend ist.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=81]]


