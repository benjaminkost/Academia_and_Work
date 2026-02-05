---
"created date:": 17.10.2025 15:07
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
  - "[[beweise]]"
  - "[[eigenschaften von fourierreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - Beweis 1.1.36
  - Beweis für Fourierspektrum der Ableitung
parent:
siblings:
child:
mathematical statement: "[[202510172010 - Lemma für Fourierspektrum der Ableitung]]"
---
# Beweis
Der 0-te Fourierkoeffizient der Ableitung ${f'}$ ist$${
\begin{aligned}
\frac{1}{T} \int_0^T f'(t)dt &= \frac{1}{T} [f(T^-) - f(0^+)] && \text{Hauptsatz der Integralrechnung} \\
&= \frac{1}{T} [f(0^-) - f(0^+)] && \text{Periodizität } f \\
&= 0 && \text{Stetigkeit von } f.
\end{aligned}
}$$Für ${k \in \mathbb{Z}\setminus\{0\}}$ erhalten wir mit partieller Integration$${
\begin{aligned}
\frac{1}{T} \int_0^T f'(t)e^{-ik\omega t} dt &= \frac{1}{T} [f(t)e^{-ik\omega t}]_{t=0^+}^{T^-} + ik\omega \frac{1}{T} \int_0^T f(t)e^{-ik\omega t} dt \\
&= 0 + ik\omega \frac{1}{T} \int_0^T f(t)e^{-ik\omega t} dt && \text{weil } f \text{ stetig und T-periodisch ist} \\
&= ik\omega c_k.
\end{aligned}
}$$
[^1] ^8745e6
# Beispiele


# Übungsaufgaben
```dataview
LIST FROM [[]]
WHERE contains(mytags, [[aufgaben]])
SORT file.name ASC
```
# Referenz
## Verknüpfung
- [[Hauptsatz der Differential- und Integralrechnung]]
- [[6 - Atomic Notes/Stetigkeit|Stetigkeit]]
## Quellen

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=16]]



