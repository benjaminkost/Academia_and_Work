---
"created date:": "03.11.2025 19:32"
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
tags:
  - aufgaben
  - baby
  - flashcards
aliases:
  - "Generelle Fragen" 
parent: 
siblings: 
child:
---
# Fragen und Antworten
Bzgl. [[202511080211 - Stückweise Stetigkeit|Stückweise Stetigkeit]]: Was ist ein beispiel einer nicht stückweisen stetigen funktion
?
Eine Funktion, die **nicht** stückweise stetig ist, hat typischerweise eine der folgenden Eigenschaften (oder beides):

1.  Sie hat **unendlich viele Unstetigkeiten** in jedem noch so kleinen Intervall.
2.  Ihre Unstetigkeiten sind **keine Sprungstellen**, d.h. die links- und rechtsseitigen Grenzwerte existieren nicht (oder sind unendlich).

Ein klassisches Beispiel für eine Funktion, die nicht stückweise stetig ist, ist die **Dirichlet-Funktion**:

$$
f(x) =
\begin{cases}
1, & \text{falls } x \in \mathbb{Q} \text{ (rational)} \\
0, & \text{falls } x \notin \mathbb{Q} \text{ (irrational)}
\end{cases}
$$

**Warum ist diese Funktion nicht stückweise stetig?**

*   **Unendlich viele Unstetigkeiten:** In jedem beliebigen Intervall $(a, b)$ gibt es unendlich viele rationale und unendlich viele irrationale Zahlen. Das bedeutet, dass die Funktion an jeder einzelnen Stelle dieses Intervalls unstetig ist, da man sich von jeder rationalen Zahl beliebig nahe an eine irrationale Zahl annähern kann (und umgekehrt), und die Funktion dort ihren Wert von 1 auf 0 ändert. Eine stückweise stetige Funktion darf aber nur endlich viele Unstetigkeiten pro Intervall haben.
*   **Keine Sprungstellen:** An keiner der Unstetigkeitsstellen existieren endliche links- und rechtsseitige Grenzwerte, die übereinstimmen müssten, um eine Sprungstelle zu definieren.

Ein weiteres Beispiel wäre eine Funktion, die an einer Stelle unendlich stark ansteigt oder abfällt, wie z.B. $f(x) = 1/x$ für $x \neq 0$ (und $f(0)$ nicht definiert). Diese hat zwar nur eine Unstetigkeit in jedem Intervall, aber diese Unstetigkeit ist keine Sprungstelle, da der Grenzwert unendlich ist.
***

# Referenz
## Verknüpfung
- 
## Quellen

