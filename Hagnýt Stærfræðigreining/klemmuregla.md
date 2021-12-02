Gerum ráð fyrir að $f(x)\leq g(x) \leq h(x)$ fyrir öll $x$ á bili $(b,c)$ sem inniheldur $a$, nema kanski $x=a$ gerum ennfremur ráð fyrir $lim_{x\to a}f(x)=lim_{x\to a}h(x)=L$ þá er $lim_{x\to a} g(x)=L$

Dæmi um klemmureglu:

Reiknum [[markgildi]] 

$lim_{x\to 0}\frac{sin(x)}{x}$

Athugum að bæði [[teljari]] og [[nefnari]] taka gildið $0$ þegar við stingum inn $x=0$ og $\frac{0}{0}$ er ekki skilgreint. Nú er vitað að fyrir öll $x\in \mathbb{R}$ gildir að 

$sin(x)\leq x\leq tan(x)$

við getum nú deilt í gegnum [[ójafna]] $sin(x)$ til þess að fá

$1 \leq \frac{x}{sin(x)} \leq \frac{1}{cos(x)}$

þar sem við nýttum okkur að $tan(x)=\frac{sin(x)}{cos(x)}$
Næst snúum við [[ójafna]] við, með því að velta öllum brotunum, til þess að fá

$cos(x) \leq \frac{sin(x)}{x} \leq 1$

Notum nú klemmuregluna til að ákvarða gildi $\frac{sin(x)}{x}$ þar sem það er klemmt á milli $1$ og $\frac{1}{cos(x)}$ því við sjáum að

$lim_{x \to 0}1=1$

og

$lim_{x\to 0}cos(x)=cos(0)=1$

þá segir klemmureglan að

$1\leq lim_{x\to 0}\frac{sin(x)}{x}\leq 1$

Aðeins ein tala uppfyllir að vera bæði stærri eða jöfn $1$ og minni eða jöfn $1$, og það er talan $1$. Því fæst að

$lim_{x\to 0}\frac{sin(x)}{x}=1$