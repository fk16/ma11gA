# Ableitungsregeln

## Summenregel
$$\frac{d}{dx} \(f(x)+g(x)\)= f'(x)+g'(x)$$

|Funktion| Ableitung |
|---|---|
|$f(x)=x^2+3x$|$f'(x)=2x+3 $|
|$g(x)=\sin(x)+x^2$|$g'(x)=\cos(x)+2x$|
|$y(x)=\ln(x)+\cos(x)$|$y'(x)=\frac1x - \sin(x)$|
|$z(x)=\exp(x)+3x+\sin(x)$|$z'(x)=\exp(x)+3+\cos(x) $|

## Produktregel
$$\frac{d}{dx}\(u(x)\cdot v(x)\) = u'(x)\cdot v(x) + u(x)\cdot v'(x)$$

|Funktion| Ableitung |
|---|---|
|$f(x)=x^2\sin(x)$|$f'(x)=2x\sin(x)+x^2\cos(x)$|
|$g(x)=\exp(x)\cdot\cos(x)$|$g'(x)=\exp(x)\cdot\cos(x)-\exp(x)\cdot\sin(x) $|
|$y(x)=\sin(x)\cdot\cos(x)$|$y'(x)=\cos(x)\cdot \cos(x)-\sin(x)\sin(x)= \cos(x)^2 - \sin(x)^2$|
|$z(x)=-\cos(x)\cdot 2x^3\cdot \ln(x)$|$z'(x)=\sin(x)\cdot 2x^3 - \cos(x)\cdot 6x $|

## Kettenregel
$$\frac{d}{dx} f(g(x)) = f'(g(x))\cdot g'(x)$$

|Funktion| Ableitung |
|---|---|
|$f(x)=\cos(4x^3)$|$f'(x)=-12x^2\sin(4x^3)$|
|$g(x)=\sin(\cos(x))$|$g'(x)=-\sin(x)\cdot \cos(\cos(x))$|
|$y(x)= \exp(3x^2-4x)$|$y'(x)=(6x-4)\cdot \exp(3x^2-4x)$|
|$z(x) =\sin(\ln(x))$|$z'(x)=\frac1x\cdot \cos(\ln(x))$|

## Quotientenregel
$$\frac{d}{dx} \frac{f(x)}{g(x)}= \frac{f'(x)}{g(x)} - \frac{f(x)\cdot g'(x)}{g(x)^2}$$

|Funktion| Ableitung |
|---|---|
|$f(x)= \frac{\sin(x)}{x^2}$|$f'(x)=\frac{\cos(x)}{x^2}-\frac{\sin(x)\cdot 2x}{(x^2)^2}=\frac{\cos(x)}{x^2}-\frac{\sin(x)\cdot 2x}{x^4}$|
|$g(x)=\frac{x^3}{x^2+1}$|$g'(x)=\frac{3x^2}{x^2+1}-\frac{x^3\cdot 2x}{x^2+1)^2}=\frac{3x^2}{x^2+1}-\frac{2x^4}{x^4+2x^2+1} $|
|$y(x)=\frac{\sin(x)}{\cos(x)}=tan(x)$|$y'(x)=\frac{\cos(x)}{\cos(x)}-\frac{\sin(x)\cdot (-\sin(x))}{\cos(x^2)}= 1+tan(x)^2 $|
|$z(x)=\frac{\cos(x)}{\exp(x)}$|$z'(x)=\frac{-\sin(x)}{\exp(x)}-\frac{\cos(x)\cdot \exp(x)}{\exp(x)^2} =\frac{-\sin(x)}{\exp(x)}-\frac{\cos(x)}{\exp(x)}$|
