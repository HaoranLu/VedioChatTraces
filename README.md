# VedioChatTraces
To make the data I collected during my course project publicly available

We collect network traces using android phone during vedio chat on a application called Wechat.

The traces are collected under three different circumstances: Both ends good network connection; Both bad...; One bad and the other one good;

Traces from different end are stored in seperate folders, "LHR" and "HXQ". Three circumstances are denoted using different subfolder name, 3-x, 4-x and 5-x(0 < x < 6).

Give asymptotically tight bounds on the following summations. Assume that $$r \ge 0$$ and $$s \ge 0$$ are constants.
a. $$\displaystyle \sum_{k=1}^n k^r$$.
$$ \begin{array}{rrlll} \displaystyle \int_{0}^n x^r dx &\le& \displaystyle \sum_{k=1}^n k^r &\le& \displaystyle \int_{1}^{n+1} x^r dx \ \displaystyle \frac{n^{r+1}}{r+1} &\le& \displaystyle \sum_{k=1}^n k^r &\le& \displaystyle \frac{(n+1)^{r+1}}{r+1} - \frac{1}{r+1} \end{array} $$
$$\Theta(n^r)$$
b. $$\displaystyle \sum_{k=1}^n \lg^sk$$.
$$ \begin{array}{rll} \displaystyle \sum_{k=1}^n \lg^sk &=& \displaystyle \sum_{k=1}^{\lfloor n / 2 \rfloor} \lg^sk + \sum_{k=\lfloor n / 2 \rfloor + 1}^n \lg^sk \ &\ge& \displaystyle \sum_{k=1}^{\lfloor n / 2 \rfloor} 0 + \sum_{k=\lfloor n / 2 \rfloor + 1}^n \lg^s(\lfloor n / 2 \rfloor) \ &=& \displaystyle n/2 \cdot \lg^s (n/2) \ &=& \Omega(n\lg^s n) \end{array} $$
$$ \begin{array}{rll} \displaystyle \sum_{k=1}^n \lg^sk &=& \displaystyle \sum_{k=1}^{\lfloor n / 2 \rfloor} \lg^sk + \sum_{k=\lfloor n / 2 \rfloor + 1}^n \lg^sk \ &\le& \displaystyle \sum_{k=1}^{\lfloor n / 2 \rfloor} \lg^s(\lfloor n / 2 \rfloor) + \sum_{k=\lfloor n / 2 \rfloor + 1}^n \lg^sn \ &=& \displaystyle n/2 \cdot \lg^s (n/2) + n/2 \cdot \lg^sn\ &=& O(n\lg^s n) \end{array} $$
Therefore $$\Theta(n \lg^sn)$$
c. $$\displaystyle \sum_{k=1}^n k^r \lg^sk$$.
$$\Theta(n^{r+1}\lg^sn)$$
