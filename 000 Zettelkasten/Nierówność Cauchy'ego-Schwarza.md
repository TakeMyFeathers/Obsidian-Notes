---
tags:
  - nierówności
---
```ad-Theorem
title: Nierówność Cauchy'ego-Schwarza
Jeżeli $(a_1, \ldots, a_n)$ i $(b_1, \ldots, b_n)$ są dowolnymi ciągami liczb rzeczywistych, to zachodzi nierówność 
$$\begin{equation}(a_1b_1+\ldots+a_nb_n)^2\leq(a_1^2+\ldots+a_n^2)(b_1^2+\ldots+b_n^2)\end{equation}$$
```

```ad-Proof
Załóżmy, że $(a_1, \ldots, a_n)\neq(0, \ldots, 0)$ i rozważmy funkcje $f:\mathbb{R}\to\mathbb{R}$ daną wzorem:
$$f(x)=(a_1x-b_1)^{2}+\ldots+(a_nx-b_n)^{2}$$
Jest to funkcja wielomianowa wyznaczona przez trójmian kwadratowy $AX^{2} + BX + C$, gdzie $A=\sum_{k=1}^{n}{{a_{k}^{2} } }$, $B=\sum_{k=1}^{n}{{b_{k}^{2} } }$, $C=-2\sum_{k=1}^{n}{{a_{k}b_{k} } }$. Wartość $f(x)$, jako suma kwadratów, jest liczbą nieujemną dla każdego $x\in\mathbb{R}$. Zatem wyróżnik $C^{2}-4AB$ jest niedodatni. Tzn. $C^{2} \geq4AB$, a to jest tylko inaczej zapisana teza.
Ponadto, równość $C^{2} - 4AB=0$ zachodzi wtedy i tylko wtedy, gdy trójmian ma pierwiastek $f(\lambda )=0$. I wtedy $a_1\lambda -b_1=\ldots=a_n\lambda -b_n=0$.
```