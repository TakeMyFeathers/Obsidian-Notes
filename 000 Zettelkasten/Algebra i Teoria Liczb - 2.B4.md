_Tagi:_ #matematyka #teoria-liczb #indukcja #rekurencja #NWD

_Zadanie._ Liczby naturalne $a_{n}, b_{n}$ wyznaczamy z równości $a_{n}+b_{n}\sqrt{ 2 }=(1+\sqrt{ 2 })^n$, dla wszystkich $n\in\mathbb{N}$. Wyznaczyć $NWD(a_{n}, b_{n})$.

_Rozwiązanie._ Z równości
$$
a_{n}+b_{n}\sqrt{ 2 } = (1+\sqrt{ 2 })(1+\sqrt{ 2 })^{n-1}=(1+\sqrt{ 2 })(a_{n-1}+b_{n-1}\sqrt{ 2 })=(a_{n-1}+2b_{n-1}) + (a_{n-1}+b_{n-1})\sqrt{ 2 }
$$
i niewymierności $\sqrt{ 2 }$ otrzymujemy $a_{n}=a_{n-1}+2b_{n-1}$ oraz $b_{n}=a_{n-1}+b_{n-1}$. Stąd natychmiast otrzymujemy $-a_{n-1}=a_{n}-2b_{n}$ i $b_{n-1}=a_{n}-b_{n}$. Załóżmy teraz, że $d\in D(a_{n}, b_{n})$. Dzięki udowodnionym zależnościom, otrzymujemy $d\in D(a_{n-1}, b_{n-1})$. Oczywista ___indukcja wsteczna___ pokazuje więc, że $d\in D(a_{1}, b_{1})$. Ale $D(a_{n}, b_{n})=\{1,-1\}$. I ostatecznie, $NWD(a_{n}, b_{n})=1$ dla każdego $n\in\mathbb{N}$.

_Dodatkowe uwagi._
1. _Obserwacja._ Zamiast dowodzić fakt, że liczby są względnie pierwsze, pokazujemy, że zbiór ich wspólnych dzielników zawiera tylko 1 i -1.
2. _Myśl._ Ciekawe użycie indukcji wstecznej. Dzięki _(1)_ widzimy, że zamiast coś rozszerzać na całą dziedzinę, chcemy coś zwęzić.  