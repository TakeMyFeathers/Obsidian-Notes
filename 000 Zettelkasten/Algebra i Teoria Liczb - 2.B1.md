---
tags:
  - "#matematyka"
  - "#zadanie"
  - "#podzielność"
  - "#NWD"
  - "#nierówność"
mathLink: $NWD(a,b)\leq \frac{a+b}{3}$
---
_Zadanie._ Udowodnić, że jeżeli $a\neq b$ są liczbami naturalnymi, to $$NWD(a,b)\leq \frac{a+b}{3}$$

_Dowód._ Niech $NWD(a,b)=d$, wtedy mamy $a=da'$ i $b=db'$, dla $a',b'\in\mathbb{N}$. Oczywiście $a'\perp b'$ i z faktu, że $a\neq b$ mamy $a'+b'\geq3$. Wtedy
$$
a+b=d(a'+b')\geq 3d
$$
Co po podzieleniu obustronnie przez 3 jest równoważne naszej tezie. $\square$

_Ćwiczenie dodatkowe._ Uogólnij nierówność dla $NWD(a_{1},a_{2},\dots,a_{n})$.