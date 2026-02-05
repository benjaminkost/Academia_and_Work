---
"created date:": 29.10.2025 23:52
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[202510271010 - Komplexe Analysis|Komplexe Analysis]]"
  - "[[202510301110 - Isolierte Singularität|Isolierte Singularität]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
  - definition
aliases:
  - Klassifikation isolierter Singularitäten
  - Definition 2.10.2
parent:
siblings:
child:
---
# Definition
Sei $U \subset \mathbb{C}$ offen und $f : U \to \mathbb{C}$ holomorph. Eine isolierte Singularität $z_0 \notin U$ von $f$ heißt
**hebbar** falls eine holomorphe Funktion $\tilde{f} : U \cup \{z_0\} \to \mathbb{C}$ existiert, so dass $f \equiv \tilde{f}|_U$ die Einschränkung von $\tilde{f}$ auf $U$ ist.
**ein Pol** falls $z_0$ nicht hebbar ist, aber ein $m \in \mathbb{N}$ existiert, so dass $z_0$ eine hebbare Singularität der Funktion $z \mapsto (z - z_0)^m f(z)$ ist. Das kleinste solche $m \in \mathbb{N}$ wird Ordnung des Pols genannt.
**wesentlich** falls sie weder hebbar noch ein Pol ist.
[^1]

# Beispiele


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

[^1]: [[tum_analysis3_EI_KoenigUlbrich-WS2526-skript.pdf#page=95]]


