---
"created date:": 22.10.2025 20:32
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510271210 - Potenzreihen in C|Potenzreihen in C]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis für Holomorphie, Ableitung und Stammfunktion von Potenzreihen
  - Beweis 2.3.6
parent:
siblings:
child:
mathematical statement: "[[202510312310 - Holomorphie, Ableitung und Stammfunktion von Potenzreihen|Holomorphie, Ableitung und Stammfunktion von Potenzreihen]]"
---
# Beweis
Wir zeigen zuerst, dass $P(z)$ und $Q(z)$ denselben Konvergenzradius $R_P = R_Q$ besitzen. Sei $\tilde{Q}(z) := \sum_{k=1}^\infty k a_k(z - z_0)^k$ und $R_{\tilde{Q}}$ der Konvergenzradius dieser Potenzreihe. Wegen $Q(z) = (z - z_0)^{-1}\tilde{Q}(z)$ für $z \ne z_0$ und $Q(z_0) = a_1$ gilt $R_Q = R_{\tilde{Q}}$. Wir berechnen weiter
$$ R_{\tilde{Q}}^{-1} = \limsup_{k\to\infty} |k a_k|^{1/k} = \limsup_{k\to\infty} k^{1/k} |a_k|^{1/k} = \lim_{k\to\infty} k^{1/k} \cdot \limsup_{k\to\infty} |a_k|^{1/k} = R_P^{-1}. $$
Wegen gleichmäßiger Konvergenz von $P(z)$ und $Q(z)$ auf $B_R(z_0)$ kann gliedweise differenziert werden; damit folgt (i). Behauptung (ii) folgt dann durch Vertauschen von $(P, Q)$ mit $(T, P)$.
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


