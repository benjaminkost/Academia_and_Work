---
"created date:": 22.10.2025 20:30
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[satz]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510271210 - Potenzreihen in C|Potenzreihen in C]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Konvergenzeigenschaften von Potenzreihen
  - Theorem 2.3.2
parent:
siblings:
child:
proof:
---
# Satz
Sei $P(z)$ eine Potenzreihe mit Konvergenzradius $R \in [0, \infty]$. Dann gilt:
(i) $P(z)$ konvergiert (sogar absolut) für $z \in B_R(z_0) := \{z \in \mathbb{C} \mid |z - z_0| < R\}$.
(ii) $P(z)$ divergiert für $z \notin \overline{B_R(z_0)} := \{z \in \mathbb{C} \mid |z - z_0| \le R\}$.
(iii) Für jedes $0 \le r < R$ ist die Konvergenz auf $\overline{B_r(z_0)}$ gleichmässig. Insbesondere ist $P(z)$ eine stetige Funktion auf $B_R(z_0)$.
(iv) Es gilt
$$ R = \lim_{k\to\infty} \left|\frac{a_k}{a_{k+1}}\right| $$
falls dies (im eigentlichen oder uneigentlichen Sinne) existiert.
[^1]

# Beispiele


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

[^1]: [[tum_KoenigUlbrich-Analysis3EI-WS2526-skript.pdf#page=73


