**Aðferð Newtons**

Byrjað er á því að velja eina tölu $x_0$ sem fyrsta nálgunargildið. Næsta nálgunargildi á eftir er svo reiknað með því að nota

$$x_1=x_0-\frac{f(x_0)}{f'(x_0)}$$

Almennt gildir fyrir allar [[náttúrulegar tölur]] $n\in \mathbb{N}$ að nálgunargildi númer $n$ þ.e. $x_n$ fæst með formúlunni 

$$x_n=x_{n-1}-\frac{f(x_{n-1})}{f'(x_{n-1})}$$

Aðferð Newton er ekki takmörkuð við það að nálga [[núllstöðvar]] margliða. Aðferðina má nota til að nálga núllstöð nokkurn veginn hvaða falls sem er, þó svo að í sumum tilfellum virki hún betur en í öðrum. Það er þó nauðsynlegt að fallið sé að minnsta kosti einu sinni diffranlegt.

**Dæmi**

Notum aðferð Newtons til þess að finna fimmta stigs nálgun (þ.e. $x_5$) á núllstöð margliðunnar

$$f(x)=x^3−3x+1$$

á bilinu $[1,2]$ þar sem upphafsgildið okkar er $x_0=2$.

Athugum að fyrsta afleiða fallsins er 

$$f'(x)=3x^2-3$$

við byrjum á að reikna fyrsta stigs nálgunn núllstöðvarinnar:

$$x_1=x_0−\frac{f(x_0)}{f′(x_0)}=2−\frac{2^3−3⋅2+1}{3⋅2^2−3}=2−\frac39≈1,666666667$$

Því næst finnum við annars stigs nálgun núllstöðvarinnar:

$$x_2=x_1−\frac{f(x_1)}{f′(x_1)}≈1,548611111$$

Höldum þessu áfram þar til við höfum fundið $x_5$, fáum að lokum að

$$x_1≈1666666667$$
$$x_2≈1,548611111$$
$$x_3≈1,532390162$$
$$x_4≈1,532088989$$
$$x_5≈1,532088886$$

Ef við hefðum haldið áfram hefði talan sem fékkst í $x_5$ endurtekið sig í $x_6$ og þá líklega ekki breyst eftir það, m.ö.o. aðferð Newtons hverfur þar náð hámarksnákvæmni sinni.

---

**Hvað getur klikkað**

- Á einhverjum tímapunkti fæst nálgunargildi $x_n$ þannig að $f′(x_n)=0$ en $f(x_n)≠0$. Af þessu leiðir að snertillinn við f í $x_n$ sker ekki x-ásinn og þar með er ekki hægt að halda ferlinu áfram.
    
-   Nálganirnar fikrast í átt að annarri rót en þeirri sem leitað var að. Ef fallið hefur fleiri en eina rót og leitað var af ákveðinni rót þarf að takmarka sig við leit á ákveðnu bili. Ef önnur rót slysast inn á bilið getur það gerst að aðferðin finni hana í staðinn.
    
-   Aðferðin bregst algerlega og skilar gildi sem er ekki nálægt neinni rót. Þetta getur t.a.m. gerst þegar upphafságiskunin er ekki nægilega góð og ágiskanirnar sem koma í framhaldinu sveiflast á milli tveggja gilda.

---
**Tölulegar vs. analytískar aðferðir**

Leiðum hugan að því algenga verkefni, að finna [[núllstöðvar]] falla. Í grunn- og framhaldsskólum er kennt að finna [[núllstöðvar]] fyrir fyrsta- og annars stigs [[margliður]]. Margir framhaldsskólar snerta einnig á aðferðum fyrir þriðja- og fjórða stigs [[margliður]]. Eða hvað með 5. stigs [[margliður]]? Eitthvað á borð við

$$x^5+8x^4+4x^3−2x−7$$

Raunin er sú að engin þekkt leið er til sem finnur [[núllstöðvar]] margliða af stigi 5 eða hærra. Jafnvel formúlurnar sem til eru fyrir [[margliður]] af stigi 3 og 4 eru svo flóknar að fæstir skólar hafa fyrir því að kenna þær. En hvað er þá gert þegar okkur vantar að vita hverjar [[núllstöðvar]] margliða af hærra stigi eru?

Þegar analytískar aðferðum þ.e. aðferðir sem nota hefðbundna, stærðfræðilega nálgun til að finna nákvæmar lausnir við stærðfræðilegum spurningum og verkefnum, er ekki til að skipta, þá taka við tölulegar aðferðir, þ.e. aðferðir þar sem fundin er góð nálgun á hinni raunverulegu lausn.

Jafnvel þótt fæstir kynnist hugtökunum analytísk aðferð og töluleg aðferð er kennt nánast eingöngu að notast við analytískar aðferðir, þá höfum við öll rekist á þær tölulegu, jafnvel þó við vitum ekki af því. Nánast allar tölvur, allir símar, allar reiknivélar og allt sem notast við einhvers konar tölvu lógík notar tölulegar aðferðir í útreikningum sínum. Þegar þú stimplar inn í reiknivélina þína $cos(0)$ og hún birtir á skjánum svarið $1$, þá er það ekki af því að vasareiknirinn reiknaði gildið $cos(0)$. Reiknivélin sótti einhvert reiknirit sem nálgar gildi kósínus-fallsins upp á eitthvað ákveðið marga marktæka aukastafi.

Aðferð Newtons er ein af þeim tölulegu aðferðum sem til eru sem finnur nálgunargildi á [[núllstöðvar]] margliða.

**Hvernig virkar aðferð Newtons?**

Aðferð Newtons virkar þannig að í byrjun er giskað á einhverja núllstöð, köllum ágiskunina $x_0$. Aðferðin notar svo reiknirit sitt til þess að koma með aðra (yfirleitt) betri ágiskun, þ.e. $x_1$ út frá þeirri fyrstu. Hún notar svo þá tölu til að búa til aðra ágiskun, og svo koll af kolli þar til valið er að hætta af því nálgunin er nógu góð. Aðferðin fikrar sig því sífellt nær réttu gildi en án þess þó endilega að vita nokkurn tímann hvert hárrétt gildi er. Því betri sem upphafságiskunin er, því styttri tíma tekur að fá þokkalega góða nálgun.