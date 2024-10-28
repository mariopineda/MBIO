---
tags:
  - notes
---
 The Pythagorean identity is a fundamental [[Trigonometric Identity|trigonometric identity]] that relates the squares of the sine and cosine functions to 1. It is derived from the Pythagorean theorem in the context of a [[Unit Circle|unit circle]]. The identity is given by:

$$\sin^2(x) + \cos^2(x) = 1$$

### Understanding the Identity
To understand why this is true, let's consider the unit circle:

1. **Unit Circle Definition**: A unit circle is a circle with a radius of 1, centered at the origin (0,0) in the coordinate plane.
2. **Coordinates on the Unit Circle**: Any point on the unit circle can be described by coordinates $(\cos(\theta), \sin(\theta))$, where $\theta$ is the angle measured from the positive x-axis.
3. **Pythagorean Theorem**: In a right triangle, the sum of the squares of the lengths of the two legs is equal to the square of the length of the hypotenuse. For a point on the unit circle:
$$
   \cos^2 x + \sin^2 x = 1^2
$$
Simplifying this gives:
$$
   \cos^2 x + \sin^2 x = 1
$$

## The Pythagorean Identity as a Difference of Squares
By rearranging the identity as either 
$$\sin^2(x)=1-\cos^2(x)$$ 
or 
$$\cos^2(x)=1-\sin^2(x)$$

the right hand aside becomes a [[Difference of Squares|difference of squares]] which can be factored as either

$$1-\cos^2(x) = (1 - \cos x)(1+\cos x)$$
or 
$$1-\sin^2(x) = (1 - \sin x)(1+\sin x)$$
respectively.

## Uses of the Pythagorean Identity

1. **Simplifying Trigonometric Expressions**: The identity is often used to simplify expressions and solve trigonometric equations.
2. **Finding Trigonometric Function Values**: If you know the value of $\sin(x)$, you can find $\cos(x)$, and vice versa, using this identity:
$$
   \cos(x) = \pm \sqrt{1 - \sin^2(x)}
$$
$$
   \sin(x) = \pm \sqrt{1 - \cos^2(x)}
$$
The sign of the radical depends on the quadrant in which the angle $x$ is located.
3. **Verifying Identities**: It is used to verify and derive other trigonometric identities.

## Example
If $\sin \theta  = \frac{\displaystyle 3}{\displaystyle 5}$, find $\cos\theta$:

Using the Pythagorean identity:
$$
\begin{align*}
\sin^2\theta + \cos^2\theta & = 1 \\ \\ 
\left(\frac{3}{5}\right)^2 + \cos^2\theta & = 1 \\ \\ 
\frac{9}{25} + \cos^2\theta & = 1 \\ \\ 
\cos^2\theta & = 1 - \frac{9}{25} \\ \\ 
\cos^2\theta & = \frac{25}{25} - \frac{9}{25} \\ \\ 
\cos^2\theta & = \frac{16}{25} \\ \\ 
\cos\theta & = \pm\sqrt{\frac{16}{25}} \\ \\ 
\cos \theta & = \pm \frac{4}{5} \\ \\ 
\end{align*}
$$
The sign of $\cos \theta$ [[CAST|depends on the quadrant]] in which the angle $\theta$ is located.