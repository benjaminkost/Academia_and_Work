---
"created date:": 29.10.2025 22:32
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Cauchy Integralformel]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - Lemma
aliases:
  - Deformierbarkeit des Integrationsweges
  - Lemma 2.7.1
parent:
siblings:
child:
proof:
  - "[[202511090811 - Beweis für Deformierbarkeit des Integrationsweges|Beweis für Deformierbarkeit des Integrationsweges]]"
---
# Lemma
Sei $U \subset \mathbb{C}$ offen, $z_0 \in U$ und $r > 0$, so dass $\overline{B_r(z_0)} \subset U$. Seien weiter $\alpha \in B_r(z_0)$ und $\epsilon > 0$ so dass $B_\epsilon(\alpha) \subset B_r(z_0)$ (dies ist erfüllt falls $0 < \epsilon < r - |z_0 - \alpha|$). Schließlich sei $f : U \setminus \{\alpha\} \to \mathbb{C}$ auf $U \setminus \{\alpha\}$ holomorph. Dann gilt
$$\oint_{\partial B_r(z_0)} f(z)dz = \oint_{\partial B_\epsilon(\alpha)} f(z)dz .$$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=83]]


