Let $X$ be a [random variable](random%20variable.md). If $\mu := \mathbb{E}X$, then its **variance** is defined as $$\mathbb{V}X :=  \mathbb{E}|X-\mu|^2 = \mathbb{E}|X-\mathbb{E}X|$$ where $\mathbb{E}$ is [expected value](expected%20value%20of%20random%20variable.md). It follows that $$\mathbb{V}X = \sum_{j=1}^\infty(x_j-\mu)^2 \cdot p_j \text{ and } \mathbb{V}X = \int\limits_{-\infty}^{\infty}(x-\mu)^2p(x)dx$$
**Propositions:** (Assume $X$ and $Y$ are random variables with finite second moment)
1. $\mathbb{V}X=\mathbb{E}X^2-(\mathbb{E}X)^2$;
2. If $\mathbb{P}\{X=c\}=1$ for some $c \in \mathbb{R}$, then $\mathbb{V}X=0$;
3. For $a, b \in \mathbb{R}$ follows that $\mathbb{V}(aX+b)=a^2\mathbb{V}X$;
4. In the case of **independent** $X$ and $Y$ one has $\mathbb{V}(X+Y)=\mathbb{V}X+\mathbb{V}Y$.