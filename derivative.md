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

