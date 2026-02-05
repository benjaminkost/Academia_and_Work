---
"created date:": 22.10.2025 20:53
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[Komplexe Kurvenintegrale]]"
tags:
  - 3-Semester
  - 1-Semester
  - bemerkung
  - baby
aliases:
  - Bemerkung Notation für Kreiswege
  - Bemerkung 2.5.3
parent:
siblings:
child:
mathematical statement:
---
# Bemerkungen
Seien $z_0 \in \mathbb{C}$ und $r > 0$. Oft betrachten wir die Kurve
$$ \gamma(t) = z_0 + re^{it} \quad \text{für } t \in [0, 2\pi]. $$
[^1]
Diese durchläuft einen Kreis mit Mittelpunkt $z_0$ und Radius $r$ (also den Rand $\partial B_r(z_0)$ der Kreisscheibe $B_r(z_0)$) im Gegenuhrzeigersinn. Sei weiter $f : \partial B_r(z_0) \to \mathbb{C}$ eine stetige Funktion. Wir werden in diesem Fall die Notationen
$$ \oint_\gamma f(z)dz = \int_\gamma f(z)dz = \int_{\partial B_r(z_0)} f(z)dz = \int_{|z-z_0|=r} f(z)dz $$
für das Kurvenintegral verwenden.
Allgemeiner: Ist $\gamma : [a, b] \to \mathbb{C}$ eine einfach geschlossene Kurve, dann zerlegt $\gamma$ die komplexe Ebene in zwei Gebiete, ein beschränktes Inneres und ein unbeschränktes Äusseres. Angenommen, das Innere wird von $\gamma$ so durchlaufen, dass es im Durchlaufsinn links liegt. Dann sagen wir dass $\gamma$ das Innere im positiven Sinn durchläuft und schreiben für entsprechende Kurvenintegrale
$$ \oint_\gamma f(z)dz \quad \text{statt} \quad \int_\gamma f(z)dz. $$
[^2]

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

[^1]: [[tum_KoenigUlbrich-Analysis3EI-WS2526-skript.pdf#page=76

[^2]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=77]]



