---
"created date:": 24.10.2025 09:00
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Orthogonalreihen]]"
  - "[[Integraltransformation]]"
  - "[[Fourierreihe]]"
  - "[[eigenschaften von fourierreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - beispiele
  - baby
aliases:
  - Beispiel Stammfunktion der Sägezahnfunktion
  - Beispiel 1.1.39
parent:
siblings:
child:
mathematical statement:
---
# Beispiel
Betrachte wieder die 2π-periodische Sägezahnfunktion $f$ von [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=7|Beispiel 1.1.8]] In [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=8|Beispiel 1.1.13]]  hatten wir gezeigt, dass der $k$-te Fourierkoeffizient von $f$ gleich
$$ c_k = \begin{cases} \frac{1}{2ik} & \text{für } k \neq 0 \\ 0 & \text{für } k = 0 \end{cases} $$
ist. Insbesondere erfüllt $f$ die Bedingung [[202510172010 - Lemma für das Fourierspektrums der Stammfunktion|Gleichung 1.16]] (wegen $c_0 = 0$). Nach [[202510172010 - Lemma für das Fourierspektrums der Stammfunktion|Lemma 1.1.36(ii)]] ist das Fourierspektrum $\{d_k\}_{k \in \mathbb{Z}}$ von $F(t) = \int_0^t f(s) ds$ gegeben durch $d_k = \frac{c_k}{ik\omega} = -\frac{1}{2k^2}$ für $k \in \mathbb{Z} \setminus \{0\}$. Für $k=0$ berechnen wir
$$ d_0 = -\frac{1}{2\pi} \int_0^{2\pi} t f(t) dt = -\frac{1}{2\pi} \int_0^{2\pi} t \cdot 2(\pi - t) dt = -\frac{1}{4\pi} \left[ \frac{\pi t^2}{2} - \frac{t^3}{3} \right]_0^{2\pi} = -\frac{1}{4\pi} \left( \frac{2\pi^3}{2} - \frac{8\pi^3}{3} \right) = \frac{\pi^2}{6} $$
Da $F$ reellwertig ist, können wir [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=12|Lemma 1.1.26]] benutzen, um eine $\cos$-$\sin$-Reihe zu erhalten: wir haben $a_k = 2 \text{Re}(d_k) = \begin{cases} -\frac{1}{k^2} & \text{für } k \in \mathbb{N} \\ \frac{\pi^2}{3} & \text{für } k = 0 \end{cases}$, $b_k = -2 \text{Im}(d_k) = 0$ für alle $k \in \mathbb{N}$, also ist die Fourierreihe von $F$ gegeben durch
$$ S_F(t) = \frac{a_0}{2} + \sum_{k=1}^\infty (a_k \cos(kt) + b_k \sin(kt)) = \frac{\pi^2}{6} - \sum_{k=1}^\infty \frac{1}{k^2} \cos(kt) $$
Nach [[Konvergenz von Fourierreihen|Theorem 1.1.21]] und weil $F$ stetig differenzierbar ist, gilt $S_F(t) = F(t)$ für alle $t \in \mathbb{R}$. Insbesondere gilt dies für $t=0$ und wir erhalten $S_F(0) = F(0) = 0$ oder $\frac{\pi^2}{6} = \sum_{k=1}^\infty \frac{1}{k^2}$. Allgemeiner können wir auch das Fourierspektrum von Funktionen betrachten, die nur stückweise stetig differenzierbar sind.[^1]


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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=17]]



