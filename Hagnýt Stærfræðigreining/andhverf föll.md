Sem dæmi má taka fallið $f(x)=x^3$ þar sem fallið tekur töluna x og hefur hana í 3 veldi. andhverfa þess er því $f^{-1}(x)=\sqrt[3]x$, því ef inntak er tala í þriðja veldi skilar það tölvunni sjálfri veldislausri út.

Talan $-1$ í $f^{-1}$ er ekki til þess að segja að f sé í mínus veldi heldur er hún notuð til þess að tákna andhverfu fallsins f.

ýmsar aðferðir má nota til þess að ákvarða hvort fall sé andhverfanlegt eða ekki. Oft er auðvelt að sjá það af grafi fallsins, t.d ef fallið er ekki [[eintækt]]

Dæmi um hvernig á að finna andhverfu:

$f(x)=x^3+4$

við skiptum f(x) út fyrir y og einangrum svo x

$y=x^3+4$
$\iff x^3=y-4$
$\iff x=\sqrt[3]y-4$

með því fæst að fallið $f^{-1}(x)=\sqrt[3]{x-4}$ er andhverfa fallsins $f(x)$

Andhverfur hafa þann rúmfræðilega eginleika að þær eru [[speiglun]] fallsins um línuna $y=x$ sem gerir það að verkum að það er þægilegt að teikna graf þeirra.

Hægt er að gera óandhverfanleg föll andhverfanleg með því að takmarka [[skilgreiningarmengi]] fallsins þannig að það verði [[eintækt]].

Þar sem [[hornaföll]] eru lotubundin gefur það til kynna að þau séu ekki eintæk og þar af leiðandi ekki andhverfanleg nema að [[skilgreiningarmengi]] sé takmarkað með þeim afleiðingum að þau verði [[eintækt]]

|     | Hornafall           | sin(x)                                     | cos(x)               | tan(x)                                     |
| --- | ------------------- | ------------------------------------------ | -------------------- | ------------------------------------------ |
|     | Tákn andhverfu      | $sin^{-1}(x)$                              | $cos^{-1}(x)$        | $tan^{-1}(x)$                              |
|     | [[skilgreiningarmengi]] | $\big [-\frac{\pi}{2},\frac{\pi}{2}\big ]$ | $\big [0,\pi \big ]$ | $\big [-\frac{\pi}{2},\frac{\pi}{2}\big ]$ |
|     |                     |                                            |                      |                                            |


|     | Hornafall           | cot(x)              | csc(x)                                                | sec(x)                                    |
| --- | ------------------- | ------------------- | ----------------------------------------------------- | ----------------------------------------- |
|     | Tákn andhverfu      | $cot^{-1}(x)$       | $csc^{-1}(x)$                                         | $sec^{-1}(x)$                             |
|     | [[Skilgreiningarmengi]] | $\big [0,\pi \big]$ | $\big [-\frac{\pi}{2},\frac{\pi}{2} \big], x \neq 0$ | $\big [0,\pi \big] x \neq \frac {\pi}{2}$ |
    |                     |                     |                                                       |                                           |
***

Rifjum upp að gagntæk [[vörpun]] $f:X\to Y$ hefur [[andhverf föll]] $f−1:Y\to X$ sem uppfyllir að

$y=f(x)$ þá og því aðeins að $x=f^{−1}(y)$

Látum $f:X\to Y$ vera fall sem skilgreint er á [[mengi]] $X$. Gerum ráð fyrir að $f$ sé [[eintækt]]. Með því að einskorða [[bakmengi]] $f$ við myndmengið $Y=f(X)$ þá verður $f:X\to Y$ gagntækt fall. Þá er til andhverfa $f^{−1}:Y\to X$

Fall sem er strangt [[vaxandi]] eða strangt minnkandi er [[eintækt]] og á sér því andhverfu
***

**Eiginleikar andhverfa**

- $y=f^{−1}(x)$ þá og því aðeins að $x=f(y)$
    
-   Skilgreingarsvæði $f$ er [[myndmengi]] $f^{−1}$
    
-   [[Myndmengi]] $f^{−1}$ er jafnt [[skilgreiningarmengi]] $f$
    
-   $f^{−1}(f(x))=x$ fyrir öll $x$ í [[skilgreiningarmengi]] $f$
    
-   $f(f^{−1}(x))=x$ fyrir öll $x$ í [[skilgreiningarmengi]] $f^{−1}$
    
-   $(f^{−1})^{−1}(x)=f(x)$ fyrir öll $x$ í [[skilgreiningarmengi]] $f$, alltsvo $(f^{−1})^{−1}=f$
    
-   Graf $f^{−1}$ er speglun á grafi $f$ um línuna $y=x$

***
**Afleiða anhverfunar**

Gerum ráð fyrir að fall $f$ hafi andhverfu $f^{−1}$. Látum $x$ vera á [[skilgreiningarmengi]] $f$ og gerum ráð fyrir að $f$ sé diffranlegt í punktinum $f^{−1}(x)$ og að $f′(f^{−1}(x))\neq 0$. Þá er $f^{−1}$ diffranlegt í punktinum $x$ og

$(f^{−1})′(x)=\frac{1}{f′(f^{−1}(x))}$

Sem segir okkur sér í lagi að láréttur [[snertill]] við $f$ svarar til lóðrétts snertils við $f^{−1}$