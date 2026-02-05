---
"created date:": 22.10.2025 11:37
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[satz]]"
  - "[[Integraltransformation]]"
  - "[[3 - Tags/motivation|motivation]]"
  - "[[202510250510 - Motivation für Fouriertransformation auf R]]"
  - "[[Orthogonalreihen]]"
  - "[[202510250610 - Fouriertransformation|Fouriertransformation]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Motivation für Fouriertransformation auf R
  - Motivation 1.2.1
parent:
siblings:
child:
proof:
---
# Motivation
Ziel der Fouriertransformation auf $\mathbb{R}$ ist es, nicht-periodische Funktionen im Frequenzraum zu analysieren; dies wird als harmonische Analysis bezeichnet. Die zugrundeliegende Idee ist, eine allgemeine Funktion $f : \mathbb{R} \to \mathbb{C}$ als T-periodische Funktion zu betrachten mit $T \to \infty$.

Genauer: Sei $T>0$ und $f_T: \mathbb{R} \to \mathbb{C}$ die T-periodische Fortsetzung der Einschränkung $f|_{(-T/2, T/2)}$. Im Folgenden werden wir (statt $\omega$)
$$ \Delta \omega := \frac{2\pi}{T} $$
für die Kreisfrequenz schreiben und wir setzen $\omega_k := k\Delta\omega$ für $k \in \mathbb{Z}$. Dann ist der k-te Fourierkoeffizient von $f_T$
$$ c_k = \frac{1}{T} \int_0^T f_T(t) e^{-ik\Delta\omega t} dt = \frac{1}{T} \int_{-T/2}^{T/2} f(t) e^{-i\omega_k t} dt \quad(1.35) $$
und es gilt
$$ f(t) = S_f(t) = \sum_{k \in \mathbb{Z}} c_k e^{ik\Delta\omega t} \quad \text{für } t \in (-T/2, T/2). \quad(1.36) $$
Definieren wir die Funktion $F_T: \mathbb{R} \to \mathbb{C}$ durch
$$ F_T(\omega) := \int_{-T/2}^{T/2} f(t) e^{-i\omega t} dt, $$
lassen sich (1.35) und (1.36) schreiben als
$$ c_k = \frac{1}{T} F_T(\omega_k) = \frac{\Delta\omega}{2\pi} F_T(\omega_k) $$
$$ f(t) = \frac{1}{2\pi} \sum_{k \in \mathbb{Z}} \Delta\omega F_T(\omega_k) e^{i\omega_k t} \quad \text{für } t \in (-T/2, T/2). \quad (1.37) $$
Die rechte Seite von (1.37) kann als Riemannsumme des Integrals
$$ \frac{1}{2\pi} \int_{-\infty}^{\infty} F_T(\omega) e^{i\omega t} d\omega $$
interpretiert werden. Weil $\Delta\omega \to 0$ für $T \to \infty$ erhalten wir (unter geeigneten Voraussetzungen an $f$) im Grenzwert $T \to \infty$
$$ f(t) = \frac{1}{2\pi} \int_{-\infty}^{\infty} F(\omega) e^{i\omega t} d\omega \quad \text{wobei } F(\omega) := \lim_{T \to \infty} F_T(\omega). $$
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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=32]]


