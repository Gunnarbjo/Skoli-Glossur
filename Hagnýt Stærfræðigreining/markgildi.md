íslenska orðið yfir "limit" 

$\lim_{x \to y}$

Dæmi um markgildi:

- $\lim_{x \to a} c = c$, c fasti
- $\lim_{x \to a} x = a$
- $\lim_{x \to a} \vert x \vert = \vert a \vert$

Reiknireglur fyrir markgildi

Gerum ráð fyrir að $\lim_{x \to a}f(x)=L$ og að $lim_{x\to a}g(x)=M$. Þá gildir:

-   $\lim_{x\to a}(f(x)+g(x))=L+M$
-   $\lim_{x\to a}(f(x)−g(x))=L−M$
-   $\lim_{x\to a}f(x)g(x)=LM$ 
-   $\lim_{x\to a}kf(x)=kL$ , þar sem $k$ er fasti. 
-   $\lim_{x\to a}f(x)/g(x)=L/M$, að því gefnu að $M\neq0$   
-   Gerum ráð fyrir að $m$ og $n$ séu [[heiltala]] þannig að $f(x)^{m/n}$ sé skilgreint fyrir öll $x$ á bili (b,c) umhverfis $a$ (en ekki endilega fyrir $x=a$) og að $L^{m/n}$ sé skilgreint. Þá er $\lim_{x\to a}f(x)^{m/n}=L^{m/n}$   .
-   Ef til er bil (b,c) sem inniheldur a þannig að $f(x)\leq g(x)$ fyrir öll $x\in$(b,c), nema kannski $x=a$, þá er $\lim_{x\to a}f(x)=L\leq M=\lim_{x\to a}g(x)$.

eins og fyrsti liður í setningunni á undan segir að ef markgildin $lim_{x\to a}f(x)$ og $lim_{x\to a}g(x)$ eru til þá sé markgildið $\lim_{x\to a}(f(x)+g(x))$ einnig til.

En hún segir **ekki** að ef $f$ og $g$ eru föll þannig að markgildið $\lim_{x\to a}(f(x)+g(x))$ er til, að þá séu markgildin $\lim_{x\to a}f(x)$ og $\lim_{x\to a}g(x)$ einnig til.

Ef við skoðum fallið $h(x)=\frac{x−1}{x−1}$ er ljóst að hægt er að stytta $x−1$ í teljara út fyrir $x−1$ í nefnara. Því er $1$ afmáanlegur [[sérstöðupunkt]]. Munum þó, að þetta fall hefur [[skilgreiningarmengi]] $\mathbb{R} ∖{1}$ og það að stytta fallið breytir því ekki. Því gildir, að jafnvel þó fallið sé styttanlegt í $h(x)=1$ að $1$ er enn ekki hluti af [[skilgreiningarmengi]] og því fallið óskilgreint í punktinum. En þar sem við gátum stytt nefnarann í burtu þá gildir að

$lim_{x\to 1}\frac{x−1}{x−1}=1$

Almennt gildir, ef hægt er að stytta ræða fallið $\frac{P(x)}{Q(x)}$ í fastann $c$, að $lim_{x\to a}\frac{P(x)}{Q(x)}=c$ fyrir öll $a\in \mathbb{R}$, jafnvel þó a sé ekki í [[skilgreiningarmengi]] fallsins. Ef hægt er að stytta einhverjar en ekki allar [[núllstöðvar]] nefnara fallsins í burtu þá er [[markgildi]] einfaldlega gildi nýja, stytta fallsins í punktinum, þ.e. ef ræða fallið $f(x)$ hefur afmáanlega [[sérstöðupunkt]] $a$ svo unnt er að stytta það í ræða fallið $\frac{P(x)}{Q(x)}$ þá gildir að

$lim_{x\to a}\frac{P(x)}{Q(x)}=\frac{P(a)}{Q(a)}$

Ef fallið stefnir ekki á eina ákveðna tölu, heldur stefnir fallgildið á að verða annað hvort óendanlega stórt eða óendanlega lítið (úr báðum áttum), segjum við að markgildið sé $\pm \infty$, þar sem $+$ er notað ef fallið stefnir á að vera óendanlega stórt en $−$ ef það stefnir á að vera óendanlega lítið.

Gerum ráð fyrir að fall f sé skilgreint á opnu bili umhverfis punktinn $a$, nema hvað hugsanlega er $f(a)$ ekki skilgreint. Við segjum að $f(x)$ stefni á $\infty$ þegar $x$ stefnir á $a$, og ritum $lim_{x\to a}f(x)=\infty$, ef eftirfarandi skilyrði er uppfyllt.

Fyrir sérhverja tölu $B$ er til tala $δ>0$ þannig að um öll $x$ sem eru þannig að

$0<|x−a|<δ$ gildir að $f(x)>B$.

Athugum sérstaklega að það sama verður að gilda fyrir báðar áttir. Ekki dugar að markgildið stefni á $−∞$ úr annarri áttinni en $+∞$ úr hinni.

Stundum er $+$-tákninu sleppt fyrir $+∞$ og aðeins er skrifað $∞$. Þetta er í samræmi við tölur almennt, þar sem jákvæðar tölur eru formerkislausar en neikvæðar tölur ávallt táknaðar með $−$ fyrir framan. Munum þó jafnframt að $∞$ er ekki tala og hegðar sér ekki eins og slík. Almennar reiknireglur gilda ekki þegar rætt er um óendanleikann.

Sumir vilja gera greinarmun á þegar [[markgildi]] er einhver tala og þegar [[markgildi]] er $±∞$. Þá er fyrra tilfellið ýmist kallað endanlegt [[markgildi]] eða eiginlegt [[markgildi]] en það seinna ýmist óendanlegt [[markgildi]] eða óeiginlegt markgildi.

Mörg föll stefna á $±∞$ í einhverjum punkti eða punktum. Það er t.a.m. algeng hegðun hjá ræðum föllum sem hafa [[núllstöðvar]] í [[nefnari]] sem ekki er hægt að stytta út (þ.e. það er ekki afmáanlegur [[sérstöðupunkt]]).

**Dæmi um óendanlegt markgildi**

Lítum á fallið $h(x)=\frac{1}{(x−2)^2}$ og veltum því fyrir okkur hvað gerist þegar við látum $x\to 2$.

Ef við skoðum hegðun fallsins í kringum punktinn $2$ getum við séð að því meir sem við nálgumst punktinn, úr báðum áttum, þeim mun stærra verður $y$-gildið.

því er ljóst að

$lim_{x\to 2}\frac{1}{(x−2)^2}=\infty$

**Skilgreining á markgildi þegar $x\rightarrow \infty$**

Gerum ráð fyrir að fall $f$ sé skilgreint á bili $(a,∞)$. Við segjum að $f(x)$ stefni á tölu $L$ þegar $x$ stefnir á $∞$, og ritum $lim_{x\to ∞}f(x)=L$, ef eftirfarandi skilyrði er uppfyllt:

Fyrir sérhverja tölu $\epsilon>0$ er til tala $R$ þannig að um öll $x>R$ gildir að

$|f(x)−L|<ϵ$.

**Skilgreining á markgildi þegar $x \rightarrow -\infty$**

Gerum ráð fyrir að fall f sé skilgreint á bili $(−∞,a)$. Við segjum að $f(x)$ stefni á tölu $L$ þegar $x$ stefnir á $−∞$, og ritum $lim_{x\to −∞}f(x)=L$, ef eftirfarandi skilyrði er uppfyllt:

Fyrir sérhverja tölu $ϵ>0$ er til tala $R$ þannig að um öll $x<R$ gildir að

$|f(x)−L|<ϵ$.