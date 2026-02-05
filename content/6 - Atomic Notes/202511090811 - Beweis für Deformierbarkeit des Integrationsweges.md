---
"created date:": 29.10.2025 22:33
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
  - beweise
aliases:
  - Beweis für Deformierbarkeit des Integrationsweges
  - Beweis 2.7.1
parent:
siblings:
child:
mathematical statement: "[[202511090711 - Deformierbarkeit des Integrationsweges|Deformierbarkeit des Integrationsweges]]"
---
# Beweis
(Beweisidee, siehe Abbildung 9). Sei $\gamma_1 = \partial B_r(z_0)$ und $\gamma_2 = \partial B_\epsilon(\alpha)$. Wir verbinden $\gamma_1$ und $\gamma_2$ durch zwei Kurvenstücke $\nu_1, \nu_2$. Durchlaufen wir jetzt sukzessive $\gamma_1, \nu_1$, dann $\gamma_2^*$ und dann $\nu_2^*$, erhalten wir eine geschlossene Kurve $\gamma$ in $U \setminus \{\alpha\}$ die nullhomotop ist. Man kann die Kurve $\gamma$ nun beliebig gut durch eine geschlossene Kurven approximieren, die in einem einfach zusammenhängenden Teilgebiet von $U \setminus \{\alpha\}$ verläuft (also nullhomotop ist). Wendet man also die Integralformel von Cauchy auf einer geschachtelten Familien von einfach zusammenhängenden Teilgebieten von $U \setminus \{\alpha\}$ und darin verlaufenden geschlossenen Kurven, die $\gamma$ zunehmend besser approximieren, so sieht man dann leicht:
$$\begin{aligned}0 &= \oint_\gamma f(z)dz \\&= \int_{\gamma_1} f(z)dz + \int_{\nu_1} f(z)dz + \int_{\gamma_2^*} f(z)dz + \int_{\nu_2^*} f(z)dz \\&= \int_{\gamma_1} f(z)dz + \int_{\nu_1} f(z)dz - \int_{\gamma_2} f(z)dz - \int_{\nu_2} f(z)dz .\end{aligned}$$
Wählen wir jetzt $\nu_1$ und $\nu_2$ wie in Abbildung 9, d.h. jeweils dasselbe Liniensegment in umgekehrter Richtung durchlaufen, dann gilt
$$\int_{\nu_1} f(z)dz = - \int_{\nu_2} f(z)dz$$
und die Behauptung folgt.
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


