
***Embedding diagrams***

Suppose we have a (curved) $n$-dimensional manifold representing our spacetime. This manifold is characterized by $\frac{1}{2}n(n+1)$ metric components (since the $g_{\mu\nu}$ form a symmetric $n\times n$ matrix, and thus only $\frac{1}{2}n(n+1)$ are "independent"). In fact, since we are free to arbitrarily choose the $n$ coordinates of our reference frame ($t,r,\theta,\phi$, for example), we can force $n$ of the metric components to take any values we want; we could make them 0 if we wish. So only $\frac{1}{2}n(n+1)-n=\frac{1}{2}n(n-1)$ of the metric components are "coordinate-independently" significant.  

Thus, if we want to embed our $n$-dimensional spacetime in a (flat) $N$-dimensional manifold, this embedding will be described by expressing $N-n$ of the embedding manifold's coordinates (Euclidean or Lorentz) in terms of the *other* $n$ coordinates.

And for the embedding to be possible, clearly this number of "choosable" functions has to be at least as large as the number of significant metric coefficients, $\frac{1}{2}n(n-1)$. So we conclude that the dimensionality of the embedding space has to be $N\geq\frac{1}{2}n(n+1)$. **(why n+1 and not n-1?)**

(According to T&B, this only analyzes local features of the embedding. If we also want to preserve the local topology of spacetime, in general we must go to an even greater-$N$ embedding space.)

The universe we live in (as best as we can tell) has a spacetime of $n=4$; for its local embedding we'd need a flat space of at least $N=10$ dimensions. Unfortunately, we 3-dimensional beings can't visualize a space like that. But! What we *can* do is extract a 2-dimensional surface from our spacetime, and embed it in a flat space of $N=3$ dimensions. (This is the highest-dimensional surface we can get away with -- a 3-surface would require $N=6$.)

**Example 1: equatorial plane of a static, spherical star**  

The spacetime metric in this case is the *Schwarzschild* metric, which gives a line element of $ds^2=-(1-\frac{2M}{r}) dt^2 + \frac{1}{1-2M/r} dr^2 + r^2d\theta^2+(r\sin\theta)^2 d\phi^2$. To look at an "equatorial plane" at a specific moment in time $t$, we set $t=$const and $\theta=\pi/2$, leaving $r,\phi$ free as the parameters on our equatorial 2-surface. The line element on this surface is $ds^2=\frac{1}{1-2m(r)/r} dr^2 + r^2 d\phi^2$, where the "mass" parameter $m$ is given by $m(r)=\int_0^r 4\pi r^2 \rho dr$. 


