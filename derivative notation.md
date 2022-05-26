---
aliases: [leibniz notation, newton notation, lagrange notation, leibniz's notation, newton's notation, lagrange's notation]
---
# Leibniz
the original notation employed by [[Gottfried Leibniz]] is used throughout mathematics. It is particularly common when the equation $y = f(x)$ is regarded as a functional relationship between $y$ and $x$ Leibniz's notation makes this relationship explicit by writing the derivative as $\frac{dy}{dx}\text{ or }\frac{d}{dx}y\text{ or }\frac{df}{dx}(x)\text{ or }\frac{d f(x)}{dx}\text{ or }\frac{d}{dx} f(x).$

Higher derivatives are written as:
$$\frac{d^2y}{dx^2}$$
as in,
$$\frac{d\left(\frac{dy}{dx}\right)}{dx} = \left(\frac{d}{dx}\right)^2y = \frac{d^2y}{dx^2}$$

The value of the derivative of $y$ at a point $x=a$ may be expressed in two ways using Leibniz's notation:

$$\left.\frac{dy}{dx}\right|_{x=a} \text{ or } \frac{dy}{dx}(a)$$

Leibniz's notation allows one to specify the variable for differentiation (in the denominator). This is especially helpful when considering [[partial derivatives|partial derivative]].  It also makes the [[chain rule]] easy to remember and recognize:

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

Leibniz's notation for differentiation does not require assigning a meaning to symbols such as {{math|''dx''}} or {{math|''dy''}} on their own, and some authors do not attempt to assign these symbols meaning.  Leibniz treated these symbols as [[infinitesimal]]s.  Later authors have assigned them other meanings, such as infinitesimals in [[non-standard analysis]] or [[exterior derivative]]s.

Some authors and journals set the differential symbol {{math|''d''}} in [[roman type]] instead of [[italic type|italic]]: {{math|d''x''}}. The [[ISO/IEC 80000]] scientific style guide recommends this style.

=== Leibniz's notation for antidifferentiation ===
{{image frame|width=200|innerstyle=font-size:400%; line-height: 120%; font-family:Times New Roman, serif; text-align:center;|
caption = The single and double indefinite integrals of <var>y</var> with respect to <var>x</var>, in the Leibniz notation. |
content =∫ ''y'' ''dx''<br>∫∫ ''y'' ''dx''{{sup|2}}}}

{{for|functions of 2 or more variables|Multiple integral}}

Leibniz introduced the [[integral symbol]] {{math|∫}} in ''Analyseos tetragonisticae pars secunda'' and ''Methodi tangentium inversae exempla'' (both from 1675).  It is now the standard symbol for [[integral|integration]].
: $\begin{align}
                                                   \int y'\,dx &= \int f'(x)\,dx = f(x) + C_0 = y + C_0 \\
                                                    \int y\,dx &= \int f(x)\,dx = F(x) + C_1 \\
                                             \iint y\,dx^2 &= \int \left ( \int y\,dx \right ) dx = \int_{X\times X} f(x)\,dx = \int F(x)\,dx = g(x) + C_2 \\
  \underbrace{\int \dots \int}_{\!\! n} y\,\underbrace{dx \dots dx}_n &= \int_{\underbrace{X\times\cdots\times X}_n} f(x)\,dx = \int s(x)\,dx = S(x) + C_n
\end{align}$
Lagrange