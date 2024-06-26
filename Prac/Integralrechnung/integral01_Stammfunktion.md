# Integral einer Funktion

Bei der Integral Rechnung betrachtn wir die sog. *Stammfunktion* einer Funktion. 
Die Funktion ist die Ableitung der Stammfunktion. 
Deswegen spricht man beim Integrieren von Funktionen auch vom *aufleiten*. 
Es ist schlicht die Umkehroperation zum Ableiten/Differenzieren von Funktionen.

Anstelle von $\frac{d}{dx}f(x)=f'(x)$ zum differenzieren/ableiten schreiben wir beim integrieren einer Funktion $\int{f(x) dx}=F(x)$

## Bestimmmtes und unbestimmtes Integral

Es gibt zwei Arten von Integralen:

1. Das *unbestimme Integral* gibt alle möglichen Stammfunktionen wieder.
2. Das *bestimmte Integral* gibt an, welche Fläche die Funktion mit der x-Achse einschließt.
Dabei werden immer Grenzen angegeben, zwischen denen integriert wird.

Zur Berechnung des bestimmten Integrals ist das unbestimmte Integral nötig. Allgemein wird das Integral von $a$ nach $b$ einer Funktion $f(x)$ berechnet als $$\int_{a}^{b}{f(x) dx} = F(b)-F(a)$$

## Beispiel
Die Funktion $f(x)=x^2$ hat das unbestimmte Integral $\int{x^2 dx}= \frac{1}{3} x^3 +c$. Dabei ist $c$ eine beliebige Zahl, die beim differenzieren/ableiten nach $x$ zu $0$ wird und daher für die Hauptfunktion $f(x)$ nicht relevant ist.

Das bestimme Integral von $x=-1$ bis $x=2$ wird geschrieben als $\int_{-1}^{2}{x^2 dx}$ und wird wie folgt berechnet:
$$\int_{-1}^{2}{x^2 dx} = [\frac{1}{3}x^3]_{-1}^{2}= \frac{1}{3} \cdot (2)^3 - \frac{1}{3} \cdot (-1)^3 = \frac{8}{3} + \frac{1}{3} = 3$$

## Übung

### Ü1. Ordne die Funktionen ihren Stammfunktionen zu:

| Funktion|            | Stammfunktion              |
|---               |---|---                         |
|A: $f(x)= 2x-1$   |   |X: $F(x)=\frac34 x^4-2x^2+1$|
|B: $f(x)=3x^3-4x$ |   |Y: $F(x)=2x^3 - 4x+7$       |
|C: $f(x)=2x+5$    |   |Z: $F(X)=x^2+5x$            |
|D: $f(x)=6x^2-4$  |   |Q: $F(x)=x^2-x$             |

### Ü2. Bestimme eine Stammfunktion zu den folgenden Funktionen

 a) $f_a(x)= 3x^2-3x+3$  
 b) $f_b(x)= -x^3+6x^2-1$  
 c) $f_c(x)= -3(x+2)^2$  
 d) $f_d(x)= 2\cos(2x)$

 ### Ü3. Bestimme das Integral in den angegebenen Grenzen

 a) $\int_{-1}^{2} x^2 dx$  
 b) $\int_{1}^{2}{0{,}6x^3-x}\ dx$
