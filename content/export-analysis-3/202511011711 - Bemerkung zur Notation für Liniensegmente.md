---
"created date:": 22.10.2025 20:56
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
tags:
  - 3-Semester
  - 1-Semester
  - bemerkung
  - baby
aliases:
  - Bemerkung zur Notation für Liniensegmente
  - Bemerkung 2.5.5
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Sei $U \subset \mathbb{C}$ offen und $f : U \to \mathbb{C}$. Seien weiter $z_0, z_1 \in U$ so, dass
$$ z_0 + t(z_1 - z_0) \in U \quad \text{für alle } t \in [0, 1]. $$
Mit anderen Worten verläuft das "gerade" Verbindungsstück zwischen $z_0$ und $z_1$ innerhalb von $U$. Dann ist $\gamma : [0, 1] \to U$ definiert durch
$$ \gamma(t) := z_0 + t(z_1 - z_0) $$
eine Kurve in $U$. Wir schreiben
$$ \int_\gamma f(z)dz =: \int_{[z_0, z_1]} f(z)dz. $$
Offenbar gilt $\int_{[z_0, z_1]} f(z)dz = \int_0^1 f(z_0 + t(z_1 - z_0))(z_1 - z_0)dt$.

[[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=77]]

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



