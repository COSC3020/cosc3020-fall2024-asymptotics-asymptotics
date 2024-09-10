# The O, Omega, and Theta

Each row in the table below specifies two functions $f(n)$ and $g(n)$.
Fill in the *number* from this list that best describes their relationship:

1. $f(n)\in O(g(n))$, but $f(n)\not \in \Omega(g(n))$
1. $f(n)\in \Omega(g(n))$, but $f(n)\not \in O(g(n))$
1. $f(n)\not\in O(g(n))$, and $f(n)\not \in \Omega(g(n))$
1. $f(n)\in \Theta (g(n))$

I have done the first one for you, as an example.

| $f(n)=\ldots$              | compared to | $g(n)=\ldots$          |
|----------------------------|:-----------:|------------------------|
| $f(n)=n$                   | 1           | $g(n)=2n^2 + n$        |
| $f(n)= 10n + 3\log_{15} n$ |      1      | $g(n)= 4n - 2\log_2 n$ |
| $f(n) = 2n^5$              |        2     | $g(n) = 5n^2$          |
| $f(n)=\log_{10} \left(n^{10}\right)$ | 3 | $g(n)=n$ |
| $f(n)= 4n^5 $ | 4 | $g(n)= 5n^4$ |
| $f(n) = 10^{256}$ | 3 | $g(n) = \log n$ |
| $f(n)= n^2 $ | 4 | $g(n)= 2^n$ |



I used programiz to get a refresher on asymptotic notations, the link is: https://www.programiz.com/dsa/asymptotic-notations
it provided graphs and explinations of each notation. 
I also used my previous discrete notes to see comparisons.


I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.