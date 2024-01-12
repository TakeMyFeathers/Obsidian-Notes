_Zadanie._ Niech $a\in\mathbb{N}$. Udowodnić, że dla każdej liczby $n\in\mathbb{N}$ zachodzi równość
$$
\frac{1a!}{a}+\frac{2(a+1)!}{a^2}+\dots+\frac{n(a+n-1)}{a^n}=\frac{(n+a)!}{a^n}-a!
$$

_Dowód._ Wykonamy indukcję po n:
1) Baza indukcji (n=1):
$$L=\frac{a!}{a}$$
$$
R=\frac{(a+1)!}{a}-a! = a!\left( \frac{a+1}{a}-1 \right) = \frac{a!}{a}=L
$$
2) Krok indukcyjny:
Zakładamy, że teza jest prawdziwa dla n, tj. $$\sum_{k=1}^n\left( \frac{k(a+k-1)}{a^k} \right)=\frac{(n+a)!}{a^n}-a!$$
3) Pokażemy, teraz wynikanie $T(n)\implies T(n+1)$:
$$
\sum_{k=1}^{n+1}\left( \frac{k(a+k-1)}{a^k} \right)=\frac{(n+a)!}{a^n}-a!+\frac{(n+1)(a+n)!}{a^{n+1}} = \frac{(a+n)!}{a^n}\left( 1 + \frac{n+1}{a} \right) - a = \frac{(a+n+1)!}{a^n} - a!
$$
$$\begin{flalign}
&& \square
\end{flalign}$$