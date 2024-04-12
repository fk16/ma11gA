# Ableitungsregeln

## Summenregel
Die Ableitung der Summe zweier Funktionen ist die Summe der Ableitungen der einzelnen Funktionen.
$$\frac{d}{dx} \(f(x)+g(x)\)= f'(x)+g'(x)$$

### Beispiel zur Summenregel
$$\frac{d}{dx}\(x^3+4x-\sin(x)\)=3x^2+4-\cos(x)$$

### Übungen zur Summenregel
Bilde jeweils die erste Ableitung.

  1. $x^2+3x$
  2. $\sin(x)+x^2$
  3. $\ln(x)+\cos(x)$
  4. $\exp(x)+3x+sin(x)$

## Produktregel
Die Ableitung eines Produktes von Funktionen ist die Summe aus dem Produkt der Ableitung der einen Funktion mit der anderen Funktion und dem Produkt der ersten Funktion mit der Ableitung der zweiten Funktion.
$$\frac{d}{dx}\(u(x)\cdot v(x)\) = u'(x)\cdot v(x) + u(x)\cdot v'(x)$$

### Beispiel zur Produktregel
$$ \frac{d}{dx}\(x^2 \cdot \sin(x)\) = 2x\sin(x) + x^2\cdot cos(x)$$

Hinweis: Hier ist $u(x)=x^2$ und $v(x)=\sin(x)$.

### Übung zur Produktregel

  1. $f(x)=x^2\sin(x)$
  2. $g(x)=\exp(x)\cdot\cos(x)$
  3. $y(x)=\sin(x)\cdot\cos(x)$
  4. $z(x)=-\cos(x)\cdot 2x^3\cdot \ln(x)$

## Kettenregel
Die Ableitung einer Verkettung von Funktionen ist das Produkt aus innerer und äußerer Ableitung.

$$\frac{d}{dx} f(g(x)) = f'(g(x))\cdot g'(x)$$

### Beispiel zur Kettenregel

$$\frac{d}{dx}\sin(x^2) = \cos(x^2)\cdot 2x$$

### Übung zur Kettenregel
  1. $f(x)=\cos(4x^3)$
  2. $g(x)=\sin(\cos(x))$
  3. $y(x)= \exp(3x^2-4x)$
  4. $z(x) =\sin(\ln(x))$

## Quotientenregel
Die Ableitung des Quotienten von Funktionen ist die Differenz des Quotienten der Ableitung des Zählers und der Funktion im Nenner zum Quotienten aus dem Produkt der Funktion im Zähler mit der Ableitung der Funktion im Nenner zum Quadrat der Funktion im Nenner.

$$\frac{d}{dx} \frac{f(x)}{g(x)}= \frac{f'(x)}{g(x)} - \frac{f(x)\cdot g'(x)}{g(x)^2}$$

### Beispiel zur Quotientenregel

$$\frac{d}{dx}\frac{x^3}{\sin(x)}= \frac{3x^2}{\sin(x)} - \frac{x^3\cdot\cos(x)}{\sin(x)^2}$$

### Übung zur Quotientenregel

  1. $f(x)= \frac{\sin(x)}{x^2}$
  2. $g(x)=\frac{x^3}{x^2+1}$
  3. $y(x)=\frac{\sin(x)}{\cos(x)}$
  4. $z(x)=\frac{\cos(x)}{\exp(x)}$









