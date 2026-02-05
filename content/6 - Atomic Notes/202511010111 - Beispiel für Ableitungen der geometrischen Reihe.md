---
"created date:": 22.10.2025 20:33
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510271210 - Potenzreihen in C|Potenzreihen in C]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Beispiel für Ableitungen der geometrischen Reihe
  - Beispiel 2.3.7
parent:
siblings:
child:
---
# Beispiel
Wir betrachten nochmals die geometrische Reihe aus Beispiel 2.3.3. Ihre Ableitung ist
$$ P'(z) = \sum_{k=1}^{\infty} k z^{k-1}. $$
Andererseits ist die Ableitung von $f(z) = \frac{1}{1-z}$ gleich $f'(z) = \frac{1}{(1-z)^2}$. Damit erhalten wir die Potenzreihendarstellung
$$ \frac{1}{(1-z)^2} = \sum_{k=1}^{\infty} k z^{k-1} \quad (|z| < 1). \quad (2.7) $$
Unabhängige Nachprüfung von (2.7). Es gilt (die verwendete Formel für das Produkt absolut konvergenter Reihen heißt Cauchy-Produktformel):
$$ \frac{1}{(1-z)^2} = \left(\sum_{l=0}^{\infty} z^l\right) \left(\sum_{m=0}^{\infty} z^m\right) = \sum_{l,m \ge 0} z^{l+m} = \sum_{k=0}^{\infty} \sum_{l,m\ge 0, l+m=k} z^k = \sum_{k=0}^{\infty} \sum_{l=0}^{k} z^k = \sum_{k=0}^{\infty} (k+1)z^k = \sum_{k=1}^{\infty} k z^{k-1}. $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=74]]



