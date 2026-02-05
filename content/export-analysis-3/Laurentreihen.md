---
"created date:": 12.10.2025 21:48
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
tags:
  - definition
aliases:
  - Definition 2.9.1
parent:
siblings:
child:
---
# Definition
Eine Laurent-Reihe mit Entwicklungspunkt $z_0 \in \mathbb{C}$ ist eine Reihe der Form
$$ Q(z) = \sum_{k=-\infty}^{\infty} c_k (z - z_0)^k := H(z) + N(z) $$
Hier sind der Hauptteil $H(z)$ und der Nebenteil $N(z)$ der Laurent-Reihe definiert als
$$ H(z) = \sum_{k=1}^{\infty} c_{-k} (z-z_0)^{-k} $$
$$ N(z) = \sum_{k=0}^{\infty} c_k (z-z_0)^{k}. $$
Wir definieren die inneren und äußeren Konvergenzradien $r$ und $R$ von $Q(z)$ wie folgt:
$1/r$ ist der Konvergenzradius der Reihe $\sum_{k=1}^\infty c_{-k} z^k$
$R$ ist der Konvergenzradius von $N(z)$.
Wir nennen $1/r$ auch den Konvergenzradius des Hauptteils $H(z)$.
[^1]

# Beispiele


# Unterthemen
```dataview
LIST
WHERE mytags AND contains(mytags, [[]])
SORT file.ctime ASC
```

# Referenzen
## Verknüpfungen
- 
## Quellen
- 

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=91]]
