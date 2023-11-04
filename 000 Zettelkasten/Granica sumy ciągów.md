---
mathLink: $\lim_{n \to \infty}{a_n} + \lim_{n \to \infty}{b_n} = \lim_{n \to \infty}{(a_n + b_n)}$
---
___Twierdzenie.___  Suma dwóch ciągów zbieżnych jest ciągiem zbieżnym, a jego granica równa się sumie granic tych ciągów.

___Dowód.___ Niech ${a_n}$ ma granicę $a$, a ciąg ${b_n}$ ma granicę $b$. Ustalmy $\eta>0$. Wtedy z definicji granicy mamy $|a_n-a|<\eta$ dla $\forall n>n_1$ i $|b_n-b|<\eta$ dla $\forall n>n_2$. Wówczas, dla $n>\max(n_1, n_2)$, zachodzą obie nierówności, więc możemy zapisać:
$$ |(a_n+b_n)-(a+b)| = |(a_n-a)+(b_n-b)| <= |a_n-a| + |b_n-b| < \eta + \eta=2\eta $$
Kładąc $\eta=\varepsilon/2$ kończymy dowód. $\square$

#TODO