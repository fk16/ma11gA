# Ableitungen  

## Polynomfunktionen

Polynome sind relativ leicht abzuleiten. Man braucht nur die Potenzregel sowie die Summenregel. 

Aus $a\cdot x^n$ wird so $a\cdot n\cdot x^{n-1}$ und in Summen/Differenzen wird jeder Summand einzeln abgeleitet. 

Konstanten fallen in der Ableitung einfach weg, weil jede Konstante *theoretisch* den Faktor x^0 aufweist ($x^0 = 1$). Aus $k\cdot x^0$ wird $k\cdot 0\cdot x^{-1}$ und durch den Faktor $0$ kann dieser Term einfach weggelassen werden.

|Funktion | Ableitung |
|-----| -----|
| $f(x) = 2x^3 - 5x^2 + 3x - 1$|      $f'(x)=6x^2-10x+3$|
| $g(x) = 4x^4 + 7x^3 - 2x^2 + 9  $|      $g'(x)=16x^3+21x^2-4x$|
|$h(x) = x^5 - 3x^4 + 6x^2 - 8 $|      $h'(x)=5x^4-12x^3+12x$|
| $p(x) = 3x^2 + 4x + 1     $|      $p'(x)=6x+4$|


## Exponentialfunktionen

|Funktion | Ableitung |
|-----|-----|
|$y(x) = \exp{(2x)}$ | $y'(x)=2\exp{(2x)}$|
|$z(x) = 5\cdot \exp{(3x)}$|$z'(x)=15\exp(3x) $|
|$w(x) = \exp{(-x)}$|$w'(x)=-\exp(-x) $|
|$v(x) = 2\cdot \exp{(4x^2)}$|$v'(x)=2\cdot 8x\cdot \exp(4x^2)=16x\cdot\exp(4x^2) $|

## Logarithmusfunktionen

|Funktion | Ableitung |
|-----|-----|
|$l(x) = \ln(2x + 1)$   |$l'(x)= 2\cdot\frac{1}{2x+1}=\frac{2}{2x+1}$|
|$m(x) = \ln(3x^2 + 5)$ |$m'(x)= 6x\cdot\frac{1}{3x^2+5}=\frac{6x}{3x^2+5}$|
|$n(x) = \ln(4x - 2)$   |$n'(x)= \frac{4}{4x-2}$|
|$p(x) = \ln(x^2 + 3)$  |$p'(x)= \frac{2x}{x^2+3}$|

## Trigonometrische Funktionen

|Funktion | Ableitung |
|-----| -----|
|$s(x) = \sin(2x)$   |$s'(x)= 2\cos(2x)$|
|$c(x) = \cos(3x^2)$ |$c'(x)=-6x\cdot \sin(3x^2) $|
|$t(x) = \tan(4x)=\frac{\sin(4x)}{\cos(4x)}$   |$t'(x)=4\cdot \frac{\cos(4x)}{\cos(4x)}+\sin(4x)\cdot 4\cdot (-\sin(4x))\cdot \frac{1}{\cos(4x)^2} =4\cdot\(1-\tan(4x)^2\)$|
|$a(x) = \sin(5x+1)$ |$a'(x)= 5\cdot \cos(5x+1)$|
  
## Gebrochen rationale Funktionen

|Funktion | Ableitung |
|-----| -----|
|$q(x)=x^{\frac12}+3$ |$q'(x)=\frac12 \cdot x^{-\frac12} $|
|$u(x)=\(x-4\)^{-\frac23}$ |$u'(x)= -\frac23 \cdot (x-4)^{-\frac{5}{3}}$|
|$k(x)=\sqrt{x^3-2x}$ |$k'(x)= \(3x^2-2\)\cdot \frac12\cdot \frac{1}{\sqrt{x^3-2x}} $|
|$o(x)=4x^{0,4}+3x^{-0,2}$|$o'(x)= 1,6x^{-0,6} -0,6x^{-1,2}$|
