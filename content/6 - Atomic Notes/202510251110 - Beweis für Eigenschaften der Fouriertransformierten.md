---
"created date:": 22.10.2025 11:44
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[beweise]]"
  - "[[Integraltransformation]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
  - "[[Orthogonalreihen]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - baby
aliases:
  - Beweis für Eigenschaften der Fouriertransformierten
  - Beweis 1.2.5
parent:
siblings:
child:
mathematical statement:
---
# Beweis
Beweis. Die Ungleichungen (1.38) folgen unmittelbar aus
$$ |\hat{f}(\omega)| \le \left| \int_{-\infty}^{\infty} f(t) e^{-i\omega t} dt \right| \le \int_{-\infty}^{\infty} |f(t)| dt = \|f\|_1. $$
sowie analoger Argumentation für $\check{f}(t)$.
Um die gleichmäßige Stetigkeit von $\hat{f}$ zu zeigen stellen wir fest, dass $\|f\|_1 < \infty$ impliziert, dass
$$ \lim_{T \to \infty} \left( \int_T^{\infty} |f(t)| dt + \int_{-\infty}^{-T} |f(t)| dt \right) = 0. $$
Daher existiert zu jedem $\epsilon > 0$ ein $T_\epsilon$ so dass
$$ \int_T^{\infty} |f(t)| dt + \int_{-\infty}^{-T} |f(t)| dt < \epsilon/4 \quad \text{für alle } T > T_\epsilon. \quad (1.39) $$
Sei jetzt $\epsilon > 0$ vorgegeben und $T = T_\epsilon$. Wir zeigen, dass
$$ |\hat{f}(\omega_1) - \hat{f}(\omega_2)| < \epsilon \quad \text{falls } |\omega_1 - \omega_2| < \frac{\epsilon}{2} \cdot \frac{1}{T \cdot \|f\|_1}, $$
was bedeutet, dass $\hat{f}$ gleichmäßig stetig ist. Dies folgt aus
$$ |\hat{f}(\omega_1) - \hat{f}(\omega_2)| = \left| \int_{-\infty}^{\infty} f(t) (e^{-i\omega_1 t} - e^{-i\omega_2 t}) dt \right| $$
$$ \le \int_{-T}^T |f(t)| \cdot |e^{-i\omega_1 t} - e^{-i\omega_2 t}| dt + \int_T^{\infty} |f(t)| \cdot |e^{-i\omega_1 t} - e^{-i\omega_2 t}| dt + \int_{-\infty}^{-T} |f(t)| \cdot |e^{-i\omega_1 t} - e^{-i\omega_2 t}| dt. $$
Mit (1.39) und der Abschätzung $|e^{-i\omega_1 t} - e^{-i\omega_2 t}| \le 2$ folgern wir daraus
$$ |\hat{f}(\omega_1) - \hat{f}(\omega_2)| \le \int_{-T}^T |f(t)| \cdot |e^{-i\omega_1 t} - e^{-i\omega_2 t}| dt + \frac{\epsilon}{2}. \quad (1.40) $$
Es gilt
$$ e^{-i\omega_1 t} - e^{-i\omega_2 t} = e^{-i\frac{t}{2}(\omega_1 + \omega_2)}(e^{-i\frac{t}{2}(\omega_1 - \omega_2)} - e^{i\frac{t}{2}(\omega_1 - \omega_2)}) = -2i e^{-i\frac{t}{2}(\omega_1 + \omega_2)} \sin\left(\frac{t}{2}(\omega_1 - \omega_2)\right), $$
also
$$ |e^{-i\omega_1 t} - e^{-i\omega_2 t}| = 2\left|\sin\left(\frac{t}{2}(\omega_1 - \omega_2)\right)\right| \le 2 \frac{|t|}{2} |\omega_1 - \omega_2| = |t| |\omega_1 - \omega_2| \le T |\omega_1 - \omega_2|. $$
Einsetzen in (1.40) liefert
$$ |\hat{f}(\omega_1) - \hat{f}(\omega_2)| \le T \cdot |\omega_1 - \omega_2| \cdot \int_{-T}^T |f(t)| dt + \frac{\epsilon}{2} < \epsilon \quad \text{falls } |\omega_1 - \omega_2| < \frac{\epsilon}{2} \cdot \frac{1}{T \cdot \|f\|_1}. $$
Die gleichmäßige Stetigkeit von $\check{f}$ wird analog bewiesen.
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

[^1]: [[tum_KoenigUlbrich-Analysis3EI-WS2526-skript.pdf#page=34



