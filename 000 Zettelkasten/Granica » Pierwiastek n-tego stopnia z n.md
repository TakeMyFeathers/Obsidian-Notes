___Twierdzenie.___ Ciąg $a_{n}=\sqrt[n]{ n }$ ma granicę jeden.
$$
\lim_{ n \to \infty } \sqrt[n]{ n }=1
$$

^01d475

___Dowód.___ Połóżmy $\delta_{n}=\sqrt[n]{ n }-1$. Wtedy mamy
$$
n=\sqrt[n]{ n^n } = (1+\delta_{n})^n=
\binom{n}{0}+\binom{n}{1}\delta_{n}+\binom{n}{2}\delta_{n}+\dots = 1 + n\delta_{n}+ \frac{n(n-1)}{2}\delta_{n}^2+\dots
$$

^03b974

Stąd $n>\frac{n(n-1)}{2}\delta_{n}^2$[^1], gdy $n>1$. Równoważnie, 
$$
\delta_{n}<\sqrt{ \frac{2}{n-1} }
$$
Ponieważ u nas $|a_{n}-g|=|\sqrt[n]{ n }-1|=\delta_{n}$[^2], więc wystarczy sprawdzić, dla jakich n zachodzi
$$
\sqrt{ \frac{2}{n-1} }<\varepsilon
$$

^1c4897

Nietrudno się przekonać, że spełniają ją wszystkie liczby $n>1+\frac{2}{\varepsilon^2}$. Zatem biorąc $n>n_{\varepsilon}:=2+\left[ \frac{2}{\varepsilon^2} \right]$ nasz dowód jest zakończony.

[^1]: Ujmując wyrazy dodatnie z n dostaniemy coś odeń mniejszego
[^2]: Łatwo tutaj zauważyć sens naszego wyboru $\delta_{n}$

___Tagi:___ #twierdzenie #matematyka #analiza_matematyczna #granice 