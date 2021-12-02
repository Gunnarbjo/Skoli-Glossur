**Skilgreining á samfellt fall**

Við segjum að fall $f$ sé samfellt ef það er samfellt í sérhverjum punkti [[skilgreiningarmengi]]

Athugið að til að fall sé samfellt er einungis gerð krafa um að það sé samfellt í öllum punktum [[skilgreiningarmengi]] síns. Samkvæmt þessari skilgreiningu er fallið $f(x)=\frac{1}{x}$ með [[skilgreiningarmengi]] $\mathbb{R}∖{0}$ samfellt jafnvel þó það taki stökk í kringum $x=0$ einfaldlega af þeirri ástæðu að $0$ er ekki í [[skilgreiningarmengi]] fallsins.

**Dæmi um samfelld föll**

- [[margliður]]
- [[ræð föll]]
- [[ræð veldi]]
- [[hornaföll]]
- [[tölugildisfall]]

**Að búa til samfellt fall**$

Með því að nota föllin úr dæminu á undan sem efnivið þá getum við búið til fjölda samfelldra falla 

Fallið $cos(3x+5)$ er samfellt. Margliðan $g(x)=3x+5$ og $f(x)=cos(x)$ eru samfelld föll og þá er samskeytingin $f∘g(x)=cos(3x+5)$ einnig samfellt fall.

**Skilgreining á innri punkt**

Látum $A\subseteq \mathbb{R}$ og $x \in A$. Við segjum að $x$ sé [[innri punktur]] $A$ ef $A$ innihleldur opið bil umhverfis $x$, þ.e.a.s. til er tala $\delta>0$ þannig að $(x-\delta,x+\delta)\subseteq A$ 

ef $x$ er ekki innri punktur $A$ og $x\in A$ þá segjum við að $x$ sé [[jaðarpunktur]]

Þessi skilgreining virkar aðeins fyrir [[innri punkt]] [[skilgreiningarmengi]]. Þannig að ef ætlunin er að rannsaka samfelldni í [[jaðarpunktur]] þá gengur þessi skilgreining ekki. Hins vegar getum við útvíkkað skilgreininguna á samfelldni fyrir hægri og vinstri endapunkta bila með því að einskorða okkur við [[markgildi]] frá vinstri og hægri.

**Skilgreining á hægri/vinstri samfelldni**

Fall $f$ er samfellt frá hægri í punkti $c$ ef $lim_{x\to c^+}f(x)=f(c)$

.

Hér er gert ráð fyrir að fallið f

sé amk. skilgreint á bili [c,a[-   .
    
-   Fall f
    
er _samfellt frá vinstri í punkti_ c ef limx→c−f(x)=f(c)

.

Hér er gert ráð fyrir að fallið f

sé amk. skilgreint á bili ]a,c

**Skilgreining á samfelldni í punkti**

Látum $f$ vera fall og $c$ [[innri punkt]] [[skilgreiningarmengi]] $f$. Sagt er að $f$ sé samfellt í punktinum $c$ ef

$lim_{x\to c}f(x)=f(c)$

Látum $f$ og $g$ vera föll. Gerum ráð fyrir að $c$ sé [[innri punktur]] [[skilgreiningarmengi]] beggja fallanna og að bæði föllin séu samfelld í punktinum $c$. Þá eru eftirfarandi föll samfelld í $c$:

-  $f+g$
-   $f−g$
-   $fg$
-   $kf$, þar sem $k$ er fasti
-   $f/g$, ef $g(c)\neq 0$
-   $(f(x))^{1/n}$, að því gefnu að $f(c)>0$ ef $n$ er slétt tala og $f(c)\neq 0$ ef $n<0$
    
Þessi setning er bein afleiðing af reiknireglum fyrir [[markgildi]]

**Samskeiting samfelldra falla**

Látum $g$ vera fall sem er skilgreint á opnu bili umhverfis $c$ og samfellt í $c$ og látum $f$ vera fall sem er skilgreint á opnu bili umhverfis $g(c)$ og samfellt í $g(c)$. Þá er fallið $f∘g$ skilgreint á opnu bili umhverfis $c$ og er samfellt í $c$.

Ef fall er skilgreint með formúlu og [[skilgreiningarmengi]] er ekki tilgreint sérstaklega, þá er venjan að líta alla þá punkta þar sem formúlan gildir sem [[skilgreiningarmengi]] fallsins.

