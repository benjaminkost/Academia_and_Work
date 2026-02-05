---
"created date:": 20.10.2025 09:47
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
  - "[[202510201010 - Periodisches Faltungsprodukt|Das periodische Faltungsprodukt]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Beweis 1.1.49
  - Beweis für Glättungseigenschaft der Faltung
parent:
siblings:
child:
mathematical statement: "[[202510201610 - Lemma für Glättungseigenschaft der Faltung|Lemma für Glättungseigenschaft der Faltung]]"
---
# Beweis
Der k-te Fourierkoeffizient der Faltung $f * g$ ist (mit Vertauschung der Integrationsreihenfolge):
$$
\frac{1}{T} \int_0^T \left( \frac{1}{T} \int_0^T f(t-s)g(s)ds \right) e^{-ik\omega t} dt = \frac{1}{T} \int_0^T \left( \frac{1}{T} \int_0^T f(t-s)e^{-ik\omega t} dt \right) g(s) ds
$$
Der innere Ausdruck $r_k(s) := \frac{1}{T} \int_0^T f(t-s)e^{-ik\omega t} dt$ ist der k-te Fourierkoeffizient der Funktion $t \to f(t-s)$. Nach [[202510171810 - Verschiebung im Zeitbereich von Fourierreihen|Lemma 1.1.32(iv)]] gilt also $r_k(s) = e^{-ik\omega s} c_k$. Einsetzen liefert:
$$
\frac{1}{T} \int_0^T (e^{-ik\omega s} c_k) g(s) ds = c_k \left( \frac{1}{T} \int_0^T g(s) e^{-ik\omega s} ds \right) = c_k d_k
$$
für jedes $k \in \mathbb{Z}$, wie behauptet.[^1]


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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=21]]


