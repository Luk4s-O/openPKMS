---
aliases: [differentiation, differentiate, derivatives]
---
# gives us the slope of a function
## Differentiation is linear
For any functions $f$ and $g$ and any real numbers $a$ and $b$, the derivative of the function $h(x) = af(x) + bg(x)$ with respect to $x$ is: $h(x) = a f(x) + b g(x)$
## derivatives have individual rules...
### Elementary rules of differentiation
#### Constant Term Rule
For any value of $c$, where $c \in \mathbb{R}$, for any value of $x \in \mathbb{R}$, $\frac{d}{dx} \left( c \right)= 0$


In Leibniz's [[derivative notation]] this is written as:
$$\frac{d(af+bg)}{dx}  = a\frac{df}{dx} +b\frac{dg}{dx}.$$

Special cases include:
* The constant factor rule $(af) = af$
* The sum rule $(f + g) = f + g$
* The subtraction rule $(f - g) = f - g.$

#### product rule
For the functions $f$ and $g$, the derivative of the function $h(x) = f(x) g(x)$ with respect to $x$ is
$$h(x) = (fg)(x) = f(x) g(x) + f(x) g(x)$$
In Leibniz's notation this is written
$$\frac{d(fg)}{dx} = \frac{df}{dx} g + f \frac{dg}{dx}$$

#### chain rule

The derivative of the function $h(x) = f(g(x))$ is
$$h(x) = f(g(x))\cdot g(x)$$

In Leibniz's [[derivative notation]], this is written as:
$$\frac{d}{dx}h(x) = \left.\frac{d}{dz}f(z)\right|_{z=g(x)}\cdot \frac{d}{dx}g(x)$$
often abridged to
$$\frac{dh(x)}{dx} = \frac{df(g(x))}{dg(x)} \cdot \frac{dg(x)}{dx}$$
#### inverse function rule
If the function $f$ has an [[inverse function]] {{Mvar|g}}, meaning that $g(f(x)) = x$ and $f(g(y)) = y,$ then
$g = \frac{1}{f\circ g}.$

In Leibniz notation, this is written as
$$\frac{dx}{dy} = \frac{1}{\frac{dy}{dx}}$$
#### power rule
If $$f(x) = x^r$$for any real number $r \neq 0,$ then 
$$f(x) = rx^{r-1}$$

When $r = 1,$ this becomes the special case that if $f(x) = x,$ then $f(x) = 1.$

Combining the power rule with the sum and constant multiple rules permits the computation of the derivative of any [[polynomial]].

#### reciprocal rule
The derivative of $$h(x)=\frac{1}{f(x)}$$for any (nonvanishing) function $f$ is:

$$h(x) = -\frac{f(x)}{(f(x))^2}$$wherever $f$ is non-zero.

In [[Leibniz's notation]], this is written

$$ \frac{d(\frac{1}{f})}{dx} = -\frac{1}{f^2}\frac{df}{dx}$$
The reciprocal rule can be derived either from the quotient rule, or from the combination of power rule and chain rule.

#### The quotient rule
If $f$ and $g$ are functions, then:
$$\left(\frac{f}{g}\right) = \frac{fg - gf}{g^2}$$ wherever $g$ is nonzero.
This can be derived from the product rule and the reciprocal rule.

#### Generalized power rule

{{main|Power rule}}

The elementary power rule generalizes considerably. The most general power rule is the functional power rule: for any functions $f$ and $g$
$$(f^g) = \left(e^{g\ln f}\right) = f^g\left(f{g \over f} + g\ln f\right)\quad$$
wherever both sides are well defined.

Special cases
* If $f(x)=x^a!$, then $f(x)=ax^{a-1}$ when $a$ is any non-zero real number and $x$ is positive.
* The reciprocal rule may be derived as the special case where g(x)=-1\!$.

== Derivatives of exponential and logarithmic functions ==

:$ \frac{d}{dx}\left(c^{ax}\right) = {ac^{ax} \ln c } ,\qquad c > 0$
the equation above is true for all {{Mvar|c}}, but the derivative for <math display="inline">c<0$ yields a complex number.

:$ \frac{d}{dx}\left(e^{ax}\right) = ae^{ax}$

:$ \frac{d}{dx}\left( \log_c x\right) = {1 \over x \ln c} , \qquad c > 1$

the equation above is also true for all {{Mvar|c}}, but yields a complex number if <math display="inline">c<0\!$.

:$ \frac{d}{dx}\left( \ln x\right)  = {1 \over x} ,\qquad x > 0.$

:$ \frac{d}{dx}\left( \ln |x|\right) = {1 \over x} ,\qquad x \neq 0.$

:$ \frac{d}{dx}\left( W(x)\right) = {1 \over {x+e^{W(x)}}} ,\qquad x > -{1 \over e}.\qquad$where $W(x)$ is the [[Lambert W function]]

:$ \frac{d}{dx}\left( x^x \right) = x^x(1+\ln x).$

:$ \frac{d}{dx}\left( f(x)^{ g(x) } \right ) = g(x)f(x)^{g(x)-1} \frac{df}{dx} + f(x)^{g(x)}\ln{( f(x) )}\frac{dg}{dx}, \qquad \text{if }f(x) > 0, \text{ and if } \frac{df}{dx} \text{ and } \frac{dg}{dx} \text{ exist.}$

:$ \frac{d}{dx}\left( f_{1}(x)^{f_{2}(x)^{\left ( ... \right )^{f_{n}(x)}}} \right ) = \left [\sum\limits_{k=1}^{n} \frac{\partial }{\partial x_{k}} \left( f_{1}(x_1)^{f_{2}(x_2)^{\left ( ... \right )^{f_{n}(x_n)}}} \right ) \right ] \biggr\vert_{x_1 = x_2 = ... =x_n = x}, \text{ if } f_{i<n}(x) > 0 \text{ and }$ $ \frac{df_{i}}{dx} \text{ exists. }$

===Logarithmic derivatives===

The [[logarithmic derivative]] is another way of stating the rule for differentiating the [[logarithm]] of a function (using the chain rule):
:$ (\ln f)= \frac{f}{f} \quad$ wherever {{Mvar|f}} is positive.

[[Logarithmic differentiation]] is a technique which uses logarithms and its differentiation rules to simplify certain expressions before actually applying the derivative.{{cn|date=October 2021}}

Logarithms can be used to remove exponents, convert products into sums, and convert division into subtraction — each of which may lead to a simplified expression for taking derivatives.


== Derivatives of trigonometric functions ==
{{main|Differentiation of trigonometric functions}}

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

