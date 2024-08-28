<style>
td,th,p {
  font-size: 20px
}
h1{
    font-size: 70px
}
h2{
    font-size:40px
}
</style>

<h1 style="text-align: center;">Math 141</h1>

## Limit Definition of Derivative
$f'(x)=\lim_{h \to 0}{\frac{f(x+h)-f(x)}{h}}$\
$f'(a)=\lim_{x \to a}{\frac{f(x)-f(a)}{x-a}}$

## Derivative Rules
|Name |Derivative |Result |
|-----|:------------:|:-------:|
|Constant|$\frac{d}{dx}[C]$|0|
|Power|$\frac{d}{dx}[x^n]$|$nx^{n-1}$|
|Exponential|$\frac{d}{dx}[a^u]$|$a^u*u'*ln(a)$
|Constant Multiply|$\frac{d}{dx}[C*f(x)]$|$C*f'(x)$|
|Multiply Functions|$\frac{d}{dx}[f(x)g(x)]$|$f'(x)g(x)+g'(x)f(x)$|
|Divide Functions|$\frac{d}{dx}[\frac{f(x)}{g(x)}]$|$\frac{f'(x)g(x)-g'(x)f(x)}{g(x)^2}$|
|Chain Rule|$\frac{d}{dx}[f(g(u))]$|$f'(g(u))*g'(u)*u'$|
|Logarithm|$\frac{d}{dx}$[$log$<sub>$a$</sub>$u$]|$\frac{u'}{uln(a)}$|


## Trigonometric Derivatives
|Name |Derivative |Result |
|-----|:------------:|:-------:|
|Sine|$\frac{d}{dx}[sin(u)]$|$cos(u)u'$|
|Cosine|$\frac{d}{dx}[cos(u)]$|$-sin(u)u'$
|Tangent|$\frac{d}{dx}[tan(u)]$|$sec^2(u)u'$|
|Cotangent|$\frac{d}{dx}[cot(u)]$|$-csc^2(u)u'$|
|Secant|$\frac{d}{dx}[sec(u)]$|$sec(u)tan(u)u'$|
|Cosecant|$\frac{d}{dx}[csc(u)]$|$-csc(u)cot(u)u'$|


## Inverse Trigonometric Derivatives
For any 'co' version of the function multiply the result by -1
|Name |Derivative |Result |
|-----|:------------:|:-------:|
|Inverse Sine|$\frac{d}{dx}[sin^-1u]$|$\frac{u'}{\sqrt{1-u^2}}$|
|Inverse Tangent|$\frac{d}{dx}[tan^-1u]$|$\frac{u'}{1+u^2}$|
|Inverse Secant|$\frac{d}{dx}[sec^-1u]$|$\frac{u'}{\|u\|\sqrt{u^2-1}}$|

## Integral Rules
Fundamental Theorem of Calculus: $\int_a^b{f'(x)dx}=f(b)-f(a)$
|Name |Derivative |Result |
|-----|:------------:|:-------:|
