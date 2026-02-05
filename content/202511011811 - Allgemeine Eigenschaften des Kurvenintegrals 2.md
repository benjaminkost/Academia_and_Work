---
"created date:": 22.10.2025 20:56
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Lemma]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Allgemeine Eigenschaften des Kurvenintegrals
  - Lemma 2.5.6
parent:
siblings:
child:
proof:
---
# Lemma
Seien $\gamma : [a, b] \to \mathbb{R}$ ein Weg und $f, g : \text{im}(\gamma) \to \mathbb{C}$ stetig. Dann gilt:
(i) **Linearität**: Für alle $\alpha, \beta \in \mathbb{C}$ ist
$$ \int_\gamma (\alpha f(z) + \beta g(z))dz = \alpha \int_\gamma f(z)dz + \beta \int_\gamma g(z)dz $$
d.h. das Kurvenintegral ist linear.
(ii) **Abhängigkeit von der Orientierung**: ist $\gamma^*(t) := \gamma(b - (t - a))$ die Kurve $\gamma$ umgekehrt durchlaufen, dann gilt
$$ \int_{\gamma^*} f(z)dz = - \int_\gamma f(z)dz $$
(iii) **Standardabschätzung**: Es gilt
$$ \left| \int_\gamma f(z)dz \right| \le \max_{a\le t\le b} |f(\gamma(t))| \cdot L(\gamma) $$
Hier bezeichnet
$$ L(\gamma) = \int_a^b |\gamma'(t)| dt \quad (2.8) $$
die (Bogen)Länge von $\gamma$.
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=78]]


