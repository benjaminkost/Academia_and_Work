---
"created date:": 24.01.2025 12:00
mytags:
  - "[[Technische Universität Berlin - Bachelor Elektrotechnik]]"
  - "[[WiSe 2024 - Analysis I und Lineare Algebra für Ingenieurwissenschaften]]"
  - "[[vektorräume mit skalarprodukt 1]]"
  - "[[Lineare Algebra]]"
  - "[[Analina I - Klausur-Formelzettel]]"
  - "[[analina_I_problemfeld]]"
  - "[[SoSe 2025 - Vorkurs Mathematik für EI|SoSe 2025 - Vorkurs Mathematik für EI]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[Fourierreihe]]"
tags:
  - 3-Semester
  - 1-Semester
  - definition
  - vl-3
  - baby
aliases:
parent:
siblings:
  - "[[Skalarprodukt - Linearität im ersten Argument]]"
child:
  - "[[Standardskalarprodukt]]"
  - "[[L2-Skalarprodukt]]"
---
# Definition
Sei $V$ ein [[Vektorraum]] über $K$. Eine Abbildung $\langle\cdot, \cdot\rangle : V \times V \to K$ heißt ein **Skalarprodukt** auf $V$, falls für alle $u, v, w \in V$, $\lambda \in K$ gilt:

1.  **Linearität im ersten Argument:**
    *   $\langle u + v, w \rangle = \langle u, w \rangle + \langle v, w \rangle$
    *   $\langle \lambda v, w \rangle = \lambda\langle v, w \rangle$
2.  **Symmetrie:**
    *   $\langle v, w \rangle = \overline{\langle w, v \rangle}$
3.  **Positive Definitheit:**
    *   $\langle v, v \rangle \ge 0$
    *   $\langle v, v \rangle = 0$ genau dann, wenn $v = 0$.

Ist $K = \mathbb{R}$, so heißt ein Vektorraum $V$ mit Skalarprodukt ein [[Euklidischer Vektorraum]]. Ist $K = \mathbb{C}$, so nennt man $V$ einen [[Unitären Vektorraum]].
# Bemerkungen
1.  Für das zweite Argument eines Skalarprodukts gilt:
    *   $\langle v, u + w \rangle = \overline{\langle u + w, v \rangle} = \overline{\langle u, v \rangle + \langle w, v \rangle} = \overline{\langle u, v \rangle} + \overline{\langle w, v \rangle} = \langle v, u \rangle + \langle v, w \rangle$
    *   $\langle v, \lambda w \rangle = \overline{\langle \lambda w, v \rangle} = \overline{\lambda\langle w, v \rangle} = \overline{\lambda}\overline{\langle w, v \rangle} = \overline{\lambda}\langle v, w \rangle$
    
    Für $K = \mathbb{R}$ ist $\overline{\lambda} = \lambda$ und das Skalarprodukt ist auch linear im zweiten Argument. Ist $K = \mathbb{C}$, so ist das Skalarprodukt nicht linear im zweiten Argument, da Skalare komplex konjugiert aus dem zweiten Argument "herausgezogen" werden. Man sagt, das Skalarprodukt ist **semilinear** oder **antilinear** im zweiten Argument.
2.  In einem reellen Vektorraum mit Skalarprodukt ist $\langle w, v \rangle \in \mathbb{R}$, so dass man das komplex Konjugieren bei der Symmetrie weglassen kann: $\langle v, w \rangle = \langle w, v \rangle$.

# Visualisierung
![[tum_vmfei_Kapitel_3.pdf#page=3]]
# Beispiele
![[VL-35-E-Kreide-Ana1-LinA-Winkert-Vektorräume-mit-Skalarprodukt-1.pdf#page=4]]
![[VL-35-E-Kreide-Ana1-LinA-Winkert-Vektorräume-mit-Skalarprodukt-1.pdf#page=5]]
![[VL-35-E-Kreide-Ana1-LinA-Winkert-Vektorräume-mit-Skalarprodukt-1.pdf#page=6]]

# Referenz
## Verknüpfung
- [[Symmetrie von Vektoren im Skalarprodukt]]
- [[Skalarprodukt - Linearität im ersten Argument]]
- [[Skalarprodukten - Positive Definitheit als Eigenschaft]]
- [[Komplex Konjugierte Zahl]]
- [[Definition Adjungierte]]
- [[Standardskalarprodukt]]
## Quellen
- [[Vorlesung203520-20Teil20220-20Vektorrume20mit20Skalarprodukt.mp4]]
- [[VL-35-Folien-Ana1-LinA-Winkert-Vektorräume-mit-Skalarprodukt-1.pdf#page=4]]
- [[VL-35-E-Kreide-Ana1-LinA-Winkert-Vektorräume-mit-Skalarprodukt-1.pdf]]
- [[tum_vmfei_Kapitel_3.pdf#page=3]]
- [[tum_vmfei_VL3-mitschriften.pdf]]
## Übungsaufgaben



