Mengi "set" er safn vel skilgreindra hluta. Hlutirnir sem mynda mengið kallast stök þess og þeir geta verið af hvaða tagi sem er, t.d. má tala um mengi allra ríkja í Evrópu og mengi allra [[heiltala]]

Mengi er óraðað safn aðgreindra hluta eða hugtaka sem saman mynda eina heild. ef x er stak$^a$ í menginu A, þá skrifum við x $\in$ A en ef x er ekki stak í A skrifum við x $\notin$ A.

Slaufusvigar eru oft notaðir til þess að afmarka mengi {.....}. og eru þrípunktar settir inn í mengið til þess að sýna fram á augljósa endurtekningu.

Einnig er algengt að tilgreina skylirðin sem stök mengisins þurfa að uppfylla "Set builder notation"
t.d. mengi jákvæðra heiltalna minni en 100 er
{x $\in$ [[heiltala]]$^+$ $\mid$ x < 100}

Ritháttur mengja er oft styttur fyrir bil "interval"

[a,b] = {x $\in$ [[rauntölur]] $\mid$ a $\leq$ x $\leq$ b} er kallað lokað bil
[a,b) = {x $\in$ [[rauntölur]] $\mid$ a $\leq$ x < b}
(a,b] = {x $\in$ [[rauntölur]] $\mid$ a < x $\leq$ b}
(a,b) = {x $\in$ [[rauntölur]] $\mid$ a < x < b} er kallað opið bil

Tómt mengi er táknað með $\varnothing$ og mengi sem er tómt inniheldur aðeins tóma mengið sem stak {$\varnothing$}

Sú útgáfa af mengjafræði sem er oftast kennd í skólum er hversdagsleg mengjafræði "naive set theory" 

hverslagsleg mengjafræði er einfaldari í framsetningu en frumsenduleg mengjafræði "axiomatic set theory"

Hinsvegar er hægt að leiða út þversagnir með hversdagslegri mengjafræði þ.e.a.s.hversdagsleg mengjafræði er ekki samkvæm "consistent"

Ekki hefur tekist að leiða út [[þversögn]] í frumsendulegri mengjafræði og er hún talin samkvæm.

**Dæmi**

Látum $S$ vera mengið sem inniheldur þau mengi $x$ sem ekki innihalda sig sjálf

$S={x|x \notin x}$

Er $S$ í sjálfu sér?
- Ef svo verður það að uppfylla það skylirði að vera ekki í sjálfu sér.
- Ef nei, þá uppfyllir það skilyrðið sem það þarf til að vera í sjálfu sér

Þessi [[þversögn]] leiddi til frumsendulegrar mengjafræði sem býður ekki upp á  
mengjaskilgreiningar eins og í þessu dæmi. [[þversögn]]in er kennd við Bertrand  
Russell (e. Russell’s Paradox).

Tvö mengi eru jöfn "equal" ef þau innihalda sömu stök, þ.e.a.s. fyrir mengi A og B gildir að þau eru jöfn ef eftirfarandi yrðing er sönn

$\forall$x: (x $\in$ A $\leftrightarrow$ x $\in$ B)

við skrifum A = B ef mengin A og B eru jöfn

Röð staka skiptir ekki máli, til dæmis gildir að  
${a,b,c}= {b,c,a}$.  
Stak getur bara komið fyrir einu sinni í mengi, þ.e.a.s.  
${a,b,c}= {a,a,a,b,b,c}$.

það hefur mismunandi nöfn eftir hvað mengið er notað í.

t.d

[[almengi]]
[[formengi]]
[[bakmengi]]
[[myndmengi]]
[[hlutmengi]]
[[skilgreiningarmengi]]
[[endanlegt mengi]]
[[fjöldatala mengis]]
[[veldismengi]]
[[sannmengi]]
[[sammengi]]
[[sniðmengi]]
[[mengjamargfeldi]] er þegar tveimur mengjum er skeitt saman
[[mengjamismunur]]

**Er tóma mengið [[hlutmengi]] í öllum mengjum?**

Notum skilgreininguna, látum $S$ vera mengi. Er yrðingin

$∀x : (x \in \varnothing \rightarrow x \in S)$  
sönn? Við vitum að:  
- $x \in \varnothing$ er alltaf ósatt og  
- yrðingin $p \rightarrow q$ er alltaf sönn þegar forliðurinn $p$ er ósannur.  

Við getum því ályktað út frá skilgreiningu á [[hlutmengi]] að tóma mengið er [[hlutmengi]] í öllum mengjum.

Hægt er að nota [[mengjajafngildisreglur]] til þess að einfalda mengjareikning
