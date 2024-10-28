## Factor 
Sometimes, factoring with a common term will make everything into a trig identity, for example: $\tan x - \tan x \sin^2(x) = \tan x (1-\sin^2(x)) = \tan x \cos^2(x)$ or 
$$
\frac{2\cos^2(x)-1-\cos(x)}{2\sin(x)\cos(x)+\sin(x)}
$$
where the numerator can be factored using the [[Method of Decomposition]] for quadratic trinomials and the denominator has a greatest common factor that can be factored out,
$$
\frac{(2\cos(x)+1)(\cos(x)-1)}{\sin(x)(2\cos(x)+1)} = \frac{\cos(x)-1}{\sin(x)}
$$
---
## Simplify
Simplify by factoring and cancelling, combining like terms, finding the common denominator of two fractions or eliminating [[Quotient of Fractions]]. For example, the following quotient of fractions can be eliminated by multiplying the quotient in the numerator by the reciprocal of the quotient of the denominator:
$$
\frac{1+\frac{\displaystyle \cos(x)}{\displaystyle \sin(x)}}{\frac{\displaystyle 1}{\displaystyle \sin(x)}} = \left[1+ \frac{\displaystyle \cos(x)}{\displaystyle \sin(x)}\right] \times \sin(x)
$$
---
## Multiply the Denominator by a Conjugate
Whenever you see one of the following $1 + \cos(x)$, $1 - \cos(x)$, $1 + \sin(x)$, $1 - \sin(x)$ in the denominator of one of the sides of your equation, try multiplying numerator and denominator of that side (if it's a fraction) by the conjugate of that term. The conjugate of $1 + \cos(x)$, for example, would be $1 - \cos(x)$. Multiplying by a conjugate will give you a difference of squares in the denominator allowing you to use a [[Pythagorean Identity]].

For example,
$$\frac{\sin x}{1+\cos x}$$ 
multiplied by 
$$\frac{1-\cos x}{1-\cos x}$$ 
results in
$$ 
\begin{align*}
& \frac{\sin x}{1+\cos x} \times \frac{1-\cos x}{1-\cos x} \\ \\
= & \frac{\sin x (1-\cos x)}{1-\cos^2(x)} \\ \\
= & \frac{\sin x-\sin x \cos x)}{\sin^2(x)}
\end{align*}
$$
Allowing you to factor and cancel as follows
$$
\frac{\sin x(1-\cos x)}{\sin^2(x)} = \frac{1-\cos x}{\sin(x)}
$$
---
## Get a Common Denominator
When you have a fraction added to a non-fraction, try giving them a common denominator. For example: 
$$
\begin{align*}
& \sin x + \cos x \cot x\\ \\
= & \sin x + \cos x \frac{\cos x}{\sin x}\\ \\
= & \frac{\sin^2x}{\sin x} + \frac{\cos^2x}{\sin x} \\ \\
= & \frac{\sin^2x + \cos^2 x}{\sin x} \\ \\
= & \frac{1}{\sin x} \\ \\
= & \csc x
\end{align*}
$$
---
## Split Fractions into Separate Fractions
When you have multiple terms in the numerator of a fraction, you might want to split them into separate fractions. For example: 
$$
\begin{align*}
& \frac{\csc(x) − \sin(x)}{\csc(x)} \\ \\
= & \frac{\csc(x)}{\csc(x)} − \frac{\sin(x)}{\csc(x)} \\ \\
= & 1 — \sin^2(x) \\ \\
= & \cos^2(x)
\end{align*}
$$
---
## Rewrite Trigonometric Functions as Sine and Cosine 
Sine and cosine functions are often the easiest to deal with, so it can help to convert other functions into sine and cosine. For example: $\sec(x) = 1/\cos(x)$, $\tan(x) = \sin(x)/\cos(x)$, $\csc(x) = 1/\sin(x)$, $\cot(x) = \cos(x)/\sin(x)$.

