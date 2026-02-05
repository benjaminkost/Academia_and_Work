---
"created date:": 28.10.2025 19:12
mytags:
  - "[[202509221009 - Technische Universität München|Technische Universität München]]"
  - "[[Technische Universität München - Bachelor Elektrotechnik und Informationstechnologie|Bachelor Elektrotechnik und Informationstechnologie]]"
  - "[[202509220909 - Mathematik|Mathematik]]"
  - "[[WS 25 Analysis 3 (EI)]]"
  - "[[fragen]]"
tags:
  - 3-Semester
  - 1-Semester
  - baby
aliases:
  - Fragen zu Analysis Übung 2
parent:
siblings:
child:
exercise: "[[Analysis 3 - Übung 2]]"
---
# Betroffene Notes
```dataview
LIST 
FROM "6 - Atomic Notes"
WHERE contains(this.file.outlinks, file.link)
SORT file.ctime ASC
```
# Fragen
## Z 2.2
> [!question]- Kann man die Grenzen von dem Integral beliebig im 2$\pi$ schieben also von $[-\pi, \pi]$ zu $[0,2\pi]$?
> Ja, man dann die Grenzen so Verschieben $[a, a+T]$

> [!question]- Warum wird bei der Berechnung von den komplexen Fourierkoeffizienten in der Lösung der Vorfaktor $\frac{1}{T}$ weggelassen
> 
## Z 2.3
> [!question]- Warum kann man $\frac{1}{2}\int_{0}^4f(t) \cdot \cos\left( \frac{\pi}{2}kt \right) dt$ in $\int_{0}^2f(t) \cdot \cos\left( \frac{\pi}{2}kt \right) dt$ umwandeln
> > Die Transformation ist aufgrund der Eigenschaften der Funktion $f(t)$ und des Integranden möglich:
>
> 1.  **$f(t)$ ist eine gerade Funktion:** Eine Funktion ist gerade, wenn $f(-t) = f(t)$. Die Aufgabenstellung besagt, dass $f$ als stetige gerade Funktion fortgesetzt wird.
> 2.  **$\cos\left( \frac{\pi}{2}kt \right)$ ist eine gerade Funktion:** Die Kosinusfunktion ist immer eine gerade Funktion.
> 3.  **Produkt zweier gerader Funktionen:** Das Produkt zweier gerader Funktionen ist ebenfalls eine gerade Funktion. Daher ist der gesamte Integrand $g(t) = f(t) \cdot \cos\left( \frac{\pi}{2}kt \right)$ eine gerade Funktion.
> 4.  **Periodizität:** Die Funktion $f(t)$ ist 4-periodisch. Das bedeutet, dass das Integral über eine beliebige Periode von Länge 4 denselben Wert hat.
> 5.  **Integrale über gerade Funktionen:** Für eine gerade Funktion $g(t)$ gilt, dass das Integral über ein symmetrisches Intervall $[-a, a]$ gleich $2 \int_0^a g(t) dt$ ist.
>
> Da $g(t)$ eine gerade Funktion und 4-periodisch ist, können wir das Integral über eine Periode $[0, 4]$ wie folgt umschreiben:
> $$ \int_0^4 g(t) dt = \int_{-2}^2 g(t) dt $$
> (Da das Integral über jede volle Periode gleich ist, können wir die Periode von $[0, 4]$ auf $[-2, 2]$ verschieben, was ein symmetrisches Intervall ist.)
>
> Da $g(t)$ gerade ist, gilt für das symmetrische Intervall $[-2, 2]$:
> $$ \int_{-2}^2 g(t) dt = 2 \int_0^2 g(t) dt $$
> Kombiniert man diese beiden Schritte, erhält man:
> $$ \int_0^4 g(t) dt = 2 \int_0^2 g(t) dt $$
> Setzt man dies in den ursprünglichen Ausdruck ein:
> $$ \frac{1}{2}\int_{0}^4f(t) \cdot \cos\left( \frac{\pi}{2}kt \right) dt = \frac{1}{2} \int_0^4 g(t) dt = \frac{1}{2} \left( 2 \int_0^2 g(t) dt \right) = \int_0^2 g(t) dt $$
> $$ = \int_{0}^2f(t) \cdot \cos\left( \frac{\pi}{2}kt \right) dt $$
> Die Transformation ist also eine direkte Folge der Geradheit der Funktion $f(t)$ und der Periodizität.

## H 2.2
> [!question]- Ist die Gleichmäßige Konvergenz entsprechend [[Konvergenz von Fourierreihen|Theorem 1.1.21]] (ii) nur erfüllt, wenn die Funktion stetig ist
> Ja, für die gleichmäßige Konvergenz der Fourierreihe auf dem gesamten Definitionsbereich muss die Funktion $f$ stetig sein (zusätzlich zur stückweisen stetigen Differenzierbarkeit). Theorem 1.1.21 (ii) besagt, dass die Partialsummen auf jedem abgeschlossenen Intervall **ohne Sprungstellen** gleichmäßig gegen $f$ konvergieren. Wenn die Funktion Sprungstellen hat, kann die Fourierreihe auf keinem Intervall, das eine Sprungstelle enthält, gleichmäßig konvergieren.

# Referenz
## Verknüpfung
- 
## Quellen


