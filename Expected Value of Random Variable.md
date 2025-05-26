In [probability space](probability%20space.md)$(\Omega, \mathcal{A}, \mathbb{P})$, give [random variable](random%20variable.md) $X:\Omega \rightarrow D$, the **expected value** of $X$ is defined by (discrete, $D:=\{x_1, x_2, ...\}$)$$\mathbb{E}X:=\sum\limits_{j=1}^\infty x_j \mathbb{P}\{X=x_j\}$$ or (continuous)
$$\mathbb{E}X := \int_D xp(x)dx$$
Properties:
1. Linear $\mathbb{E}(aX+bY)=a\mathbb{E}X+b\mathbb{E}Y$;
2. For **independent** $X$ and $Y$ possessing an expected value, the expected value of $X\cdot Y$ exists and $\mathbb{E}[XY]=\mathbb{E}X\cdot\mathbb{E}Y$;