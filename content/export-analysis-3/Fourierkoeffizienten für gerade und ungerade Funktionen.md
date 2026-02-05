---
"created date:": 29.01.2025 12:41
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[Approximation mit Fourierpolynomen im quadratischen Mittel]]"
  - "[[Analina I - Klausur-Formelzettel]]"
  - "[[analina_I_problemfeld]]"
  - "[[reelle fourieranalyse]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
tags:
  - 3-Semester
  - 1-Semester
  - vl-2
  - baby
aliases:
  - cos(kωt)
  - sin(kωt)
  - Lemma 1.1.31
parent:
siblings:
child:
---
# Definition
## Beobachtungen
1.  Für alle $\omega \in \mathbb{R}$ und alle $k \in \mathbb{N}$ ist
    a) $\cos(k\omega t)$ eine gerade Funktion.
    b) $\sin(k\omega t)$ eine ungerade Funktion.
2.  Seien $g : \mathbb{R} \to \mathbb{R}$ eine gerade Funktion und $u : \mathbb{R} \to \mathbb{R}$ eine ungerade Funktion. Dann gilt:
    a) Ist $f$ gerade, so ist $f \cdot g$ gerade und $f \cdot u$ ungerade.
    b) Ist $f$ ungerade, so ist $f \cdot g$ ungerade und $f \cdot u$ gerade.
3.  Sei $g$ eine gerade und $u$ eine ungerade Funktion. Dann gilt
    a) $\int_{-a}^{a} u(t) dt = 0$,
    b) $\int_{-a}^{a} g(t) dt = 2 \int_{0}^{a} g(t) dt$.
4.  Ist $f$ T-periodisch, so können wir statt über $[0, T]$ über ein beliebiges anderes Intervall der Länge $T$ integrieren. In Zeichen: Für jedes $a \in \mathbb{R}$ gilt $\int_{0}^{T} f(t) dt = \int_{a}^{a+T} f(t) dt$.
    Speziell für $a = -\frac{T}{2}$ ist $\int_{0}^{T} f(t) dt = \int_{-\frac{T}{2}}^{\frac{T}{2}} f(t) dt$.
## Schlussfolgerung
Sei $f : \mathbb{R} \to \mathbb{R}$ eine $T$-periodische Funktion und $\omega = \frac{2\pi}{T} > 0$.

1.  Ist $f$ **ungerade**, so gilt für alle $k \in \mathbb{N}$
    $a_k = 0$ und $b_k = \frac{4}{T} \int_{0}^{\frac{T}{2}} f(t) \sin(k\omega t) dt$.
2.  Ist $f$ eine **gerade** Funktion, so gilt für alle $k \in \mathbb{N}$
    $a_k = \frac{4}{T} \int_{0}^{\frac{T}{2}} f(t) \cos(k\omega t) dt$ und $b_k = 0$.
# Beweis
![[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=4]]
![[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=5]]
# Beispiele
![[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=1]]
![[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=2]]
![[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=3]]

# Referenz
## Verknüpfung
- [[Gerade Funktion]]
- [[Ungerade Funktion]]
- [[Rechenregeln der Integration]]
- [[Substitutionsregel 1. Version]]
- [[Eigenschaften von Sinus und Cosinus]]
## Quellen
- [[VL-38-Folien-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf#page=5]]
- [[VL-38-E-Kreide-Ana1-LinA-Winkert-Approximation-im-quadratischen-Mittel.pdf]]
- [[Vorlesung203820-20Teil20120-20Fourierkoeffizienten20fr20gerade20und20ungerade20Funktionen.mp4]]
- [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=13]]
## Übungsaufgaben


