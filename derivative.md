---
aliases: [differentiation, differentiate, derivatives]
---
# a derivative of a function gives us another function which determines the slope of the orignal function
## Differentiation is linear
For any functions $f$ and $g$ and any real numbers $a$ and $b$, the derivative of the function $h(x) = af(x) + bg(x)$ with respect to $x$ is: $h'(x) = a f'(x) + b g'(x)$
## derivatives have individual rules...
### Elementary rules of differentiation
- [[constant term rule|constant term rule]]
- [[product rule|product rule]]
- [[chain rule|chain rule]]
- [[inverse function rule]]
- [[power rule]]
- [[reciprocal rule]]
- [[quotient rule]]
### Derivatives of trigonometric functions

---
### Other rules of differentiation
- [[generalized power rule]]

===Logarithmic derivatives===

The [[logarithmic derivative]] is another way of stating the rule for differentiating the [[logarithm]] of a function (using the chain rule):
:$ (\ln f)= \frac{f}{f} \quad$ wherever {{Mvar|f}} is positive.

[[Logarithmic differentiation]] is a technique which uses logarithms and its differentiation rules to simplify certain expressions before actually applying the derivative.{{cn|date=October 2021}}

Logarithms can be used to remove exponents, convert products into sums, and convert division into subtraction — each of which may lead to a simplified expression for taking derivatives.

{| style="width:100%; background:transparent; margin-left:2em;"
|width=50%|$ (\sin x) = \cos x = \frac{e^{ix} +
 e^{-ix}}{2} $
|width=50%|$ (\arcsin x) = { 1 \over \sqrt{1 - x^2}} $
|-
|$ (\cos x) = -\sin x = \frac{e^{-ix} -
 e^{ix}}{2i} $
|$ (\arccos x) = -{1 \over \sqrt{1 - x^2}} $
|-
|$ (\tan x) = \sec^2 x = { 1 \over \cos^2 x} = 1 + \tan^2 x $
|$ (\arctan x) = { 1 \over 1 + x^2} $
|-
|$ (\cot x) = -\csc^2 x = -{ 1 \over \sin^2 x} = -1 - \cot^2 x$
|$ (\operatorname{arccot} x) = {1 \over -1 - x^2} $
|-
|$ (\sec x) = \sec{x}\tan{x} $
|$ (\operatorname{arcsec} x) = { 1 \over |x|\sqrt{x^2 - 1}} $
|-
|$ (\csc x) = -\csc{x}\cot{x} $
|$ (\operatorname{arccsc} x) = -{1 \over |x|\sqrt{x^2 - 1}} $
|}
The derivatives in the table above is for when the range of the inverse secant is $[0,\pi]\!$ and when the range of the inverse cosecant is $\left[-\frac{\pi}{2},\frac{\pi}{2}\right]\!$.

It is common to additionally define an [[Atan2|inverse tangent function with two arguments]], $\arctan(y,x)\!$.  Its value lies in the range $[-\pi,\pi]\!$ and reflects the quadrant of the point $(x,y)\!$.  For the first and fourth quadrant (i.e. $x > 0\!$) one has $\arctan(y, x>0) = \arctan(y/x)\!$.  Its partial derivatives are
{| style="width:100%; background:transparent; margin-left:2em;"
| width="100%" |$ \frac{\partial \arctan(y,x)}{\partial y} = \frac{x}{x^2 + y^2}$, and $ \frac{\partial \arctan(y,x)}{\partial x} = \frac{-y}{x^2 + y^2}.$
|}

==Derivatives of hyperbolic functions==
{| style="width:100%; background:transparent; margin-left:2em;"
|width=50%|$( \sinh x )= \cosh x = \frac{e^x +
 e^{-x}}{2}$
| width="50%" |$(\operatorname{arsinh}x) = { 1 \over \sqrt{1 + x^2}}$
|-
|$(\cosh x )= \sinh x = \frac{e^x - e^{-x}}{2}$
|$(\operatorname{arcosh}x) = {\frac {1}{\sqrt{x^2-1}}}$
|-
|$(\tanh x )= {\operatorname{sech}^2x} = { 1 \over \cosh^2 x} = 1 - \tanh^2 x$
|$(\operatorname{artanh}x) = { 1 \over 1 - x^2}$
|-
|$(\coth x ) = -\operatorname{csch}^2x = -{ 1 \over \sinh^2 x} = 1 - \coth^2 x$
|$(\operatorname{arcoth}x) = { 1 \over 1 - x^2}$
|-
|$(\operatorname{sech} x) = -\operatorname{sech}{x}\tanh{x}$
|$(\operatorname{arsech}x) = -{1 \over x\sqrt{1 - x^2}}$
|-
|$(\operatorname{csch}x) = -\operatorname{csch}{x}\coth{x}$
|$(\operatorname{arcsch}x) = -{1 \over |x|\sqrt{1 + x^2}}$
|}
See [[Hyperbolic functions#Derivatives|Hyperbolic functions]] for restrictions on these derivatives.

==Derivatives of special functions==
;[[Gamma function]] $\quad \Gamma(x) = \int_0^\infty t^{x-1} e^{-t}\, dt$
:$\begin{align}
\Gamma(x) & = \int_0^\infty t^{x-1} e^{-t} \ln t\,dt \\
& = \Gamma(x) \left(\sum_{n=1}^\infty \left(\ln\left(1 + \dfrac{1}{n}\right) - \dfrac{1}{x + n}\right) - \dfrac{1}{x}\right) \\
& = \Gamma(x) \psi(x)
\end{align}$ {{pb}} with $\psi(x)$ being the [[digamma function]], expressed by the parenthesized expression to the right of $\Gamma(x)$ in the line above.
;[[Riemann Zeta function]]$\quad\zeta(x) =\sum_{n=1}^\infty\frac{1}{n^x}$
:$\begin{align}\zeta(x) & = -\sum_{n=1}^\infty \frac{\ln n}{n^x}
=-\frac{\ln 2}{2^x} - \frac{\ln 3}{3^x} - \frac{\ln 4}{4^x} - \cdots \\
& = -\sum_{p \text{ prime}} \frac{p^{-x} \ln p}{(1-p^{-x})^2}\prod_{q \text{ prime}, q \neq p} \frac{1}{1-q^{-x}} \end{align}$

==Derivatives of integrals==

{{main|Differentiation under the integral sign}}

Suppose that it is required to differentiate with respect to x the function

:$F(x)=\int_{a(x)}^{b(x)}f(x,t)\,dt,$

where the functions $f(x,t)$ and $\frac{\partial}{\partial x}\,f(x,t)$ are both continuous in both $t$ and $x$ in some region of the $(t,x)$ plane, including $a(x)\leq t\leq b(x),$ $x_0\leq x\leq x_1$, and the functions $a(x)$ and $b(x)$ are both continuous and both have continuous derivatives for $x_0\leq x\leq x_1$.  Then for $\,x_0\leq x\leq x_1$:

:$ F(x) = f(x,b(x))\,b(x) - f(x,a(x))\,a(x) + \int_{a(x)}^{b(x)} \frac{\partial}{\partial x}\, f(x,t)\; dt\,. $

This formula is the general form of the [[Leibniz integral rule]] and can be derived using the 
[[fundamental theorem of calculus]].

==Derivatives to nth order==
Some rules exist for computing the {{Mvar|n}}-th derivative of functions, where {{Mvar|n}} is a positive integer.  These include:

===Faà di Brunos formula===
{{main|Faà di Brunos formula}}
If {{Mvar|f}} and {{Mvar|g}} are {{Mvar|n}}-times differentiable, then

:$  \frac{d^n}{d x^n} [f(g(x))]= n! \sum_{\{k_m\}}^{} f^{(r)}(g(x)) \prod_{m=1}^n \frac{1}{k_m!} \left(g^{(m)}(x) \right)^{k_m}$

where $ r = \sum_{m=1}^{n-1} k_m$ and the set $ \{k_m\}$ consists of all non-negative integer solutions of the Diophantine equation $ \sum_{m=1}^{n} m k_m = n$.

===General Leibniz rule===
{{main|General Leibniz rule}}
If {{Mvar|f}} and {{Mvar|g}} are {{Mvar|n}}-times differentiable, then

$$ \frac{d^n}{dx^n}[f(x)g(x)] = \sum_{k=0}^{n} \binom{n}{k} \frac{d^{n-k}}{d x^{n-k}} f(x) \frac{d^k}{d x^{k} g(x)}$$

