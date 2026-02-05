---
"created date:": 29.10.2025 22:27
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
  - Lemma
aliases:
  - Existenz von Stammfunktionen in einfach zusammenhängenden Gebieten
  - Gleichung 2.11
  - Lemma 2.6.6
parent:
siblings:
child:
proof:
  - "[[202511090611 - Beweis für Existenz von Stammfunktionen in einfach zusammenhängenden Gebieten|Beweis für Existenz von Stammfunktionen in einfach zusammenhängenden Gebieten]]"
---
# Lemma
Sei $U \subset \mathbb{C}$ ein einfach zusammenhängendes Gebiet und $z_0 \in U$ beliebig (aber fix). Sei weiter $f : U \to \mathbb{C}$ holomorph auf $U$. Wir definieren die Funktion
$$F(z) := \int_\gamma f(\zeta)d\zeta , \quad (2.11)$$
wobei $\gamma : [a, b] \to U$ eine beliebige Kurve mit $\gamma(a) = z_0$ und $\gamma(b) = z$ ist. Dann ist $F$ eine Stammfunktion von $f$ auf $U$, d.h.
$$F'(z) = f(z) \quad \text{für alle } z \in U .$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=82]]


