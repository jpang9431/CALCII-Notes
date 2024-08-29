# Math 141

## Limit Definition of Derivative
$f\prime(x)=\lim_{h \to 0}{\frac{f(x+h)-f(x)}{h}}$

$f\prime(a)=\lim_{x \to a}{\frac{f(x)-f(a)}{x-a}}$

## Derivative Rules
|Name |Derivative |Result |
|-----|:------------:|:-------:|
|Constant|$\frac{d}{dx}[C]$|0|
|Power|$\frac{d}{dx}[x^n]$|$nx^{n-1}$|
|Exponential|$\frac{d}{dx}[a^u]$|$a^u*u\prime *ln(a)$
|Constant Multiply|$\frac{d}{dx}[C*f(x)]$|$C*f\prime(x)$|
|Multiply Functions|$\frac{d}{dx}[f(x)g(x)]$|$f\prime(x)g(x)+g\prime(x)f(x)$|
|Divide Functions|$\frac{d}{dx}[\frac{f(x)}{g(x)}]$|$\frac{f\prime(x)g(x)-g\prime(x)f(x)}{g(x)^2}$|
|Chain Rule|$\frac{d}{dx}[f(g(u))]$|$f\prime(g(u))*g\prime(u)*u\prime$|
|Logarithm|$\frac{d}{dx}$[log<sub>$a$</sub>$u$]|$\frac{u\prime}{uln(a)}$|


## Trigonometric Derivatives
|Name |Derivative |Result |
|-----|:------------:|:-------:|
|Sine|$\frac{d}{dx}[sin(u)]$|$cos(u)u\prime$|
|Cosine|$\frac{d}{dx}[cos(u)]$|$-sin(u)u\prime$
|Tangent|$\frac{d}{dx}[tan(u)]$|$sec^2(u)u\prime$|
|Cotangent|$\frac{d}{dx}[cot(u)]$|$-csc^2(u)u\prime$|
|Secant|$\frac{d}{dx}[sec(u)]$|$sec(u)tan(u)u\prime$|
|Cosecant|$\frac{d}{dx}[csc(u)]$|$-csc(u)cot(u)u\prime$|


## Inverse Trigonometric Derivatives
For any \primeco\prime version of the function multiply the result by -1
|Name |Derivative |Result |
|-----|:------------:|:-------:|
|Inverse Sine|$\frac{d}{dx}[sin^-1u]$|$\frac{u\prime}{\sqrt{1-u^2}}$|
|Inverse Tangent|$\frac{d}{dx}[tan^-1u]$|$\frac{u\prime}{1+u^2}$|
|Inverse Secant|$\frac{d}{dx}[sec^-1u]$|$\frac{u\prime}{\|u\|\sqrt{u^2-1}}$|

## Separable Differential Equation
If $\frac{dy}{dx}=f(y)*g(x)$ than $\frac{1}{f(y)}dy=g(x)dx$

If $\frac{dy}{dt} = ky$ where k is a constant than $|y|=Ce^{kt}$

If $f(x)=x+y$ then $f\prime(x)=1+\frac{dy}{dx}$

## Integral Rules
Fundamental Theorem of Calculus: $\int_a^b{f\prime(x)dx}=f(b)-f(a)$
|Name |Derivative |Result |
|-----|:------------:|:-------:|
|Constant|$\int Cdx$|$Cx$|
|Simple Function|$\int f(x)dx$|$f(x)+C$|
|Fraction|$\int \frac{1}{u} du$|$ln\|u\|+C$
|Exponential|$\int a^u du$|$\frac{a^u}{ln(a)u\prime}$|


