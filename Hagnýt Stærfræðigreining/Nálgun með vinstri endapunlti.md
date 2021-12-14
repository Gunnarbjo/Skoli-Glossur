Á sérhverju hlutbili $[x_{i−1},x_i]$ fyrir $i=1,2,…n$ búum við til rétthyrning með breiddina $Δx$ og hæðina $f(x_{i−1})$, þ.e. fallgildið í vinstri endapunkti hlutbilsins. Þá er flatarmál þessa rétthyrnings $f(x_{i−1})⋅Δx_i$. Ef við summum saman flatarmál allra þessara rétthyrninga fæst nálgunargildi á flatarmál svæðisins $A$. Við notum ritháttinn $L_n$ til að tákna að þetta sé nálgun með vinstri endapunkti ($L$ fyrir e. left) með $n$ hlutbilum. Formúlan er því

$$A≈L_n=∑_{i=1}^nf(x_{i−1})⋅Δx$$

Ef við höfum t.d. $n=5$ hlutbil til að nálga flatarmál svæðisins sem myndast á milli línanna $x=1$ og $x=6$, og er fyrir ofan x-ásinn og undir ferli fallsins $f(x)=cos(x)+3$. Sérhvert hlutbil hefur lengdina $Δx=1$. Hæð rétthyrninganna má reikna með $cos(x)+3$ fyrir $x=1,…,5$ og er (frá vinstri til hægri) $3,54$,$2,58$, $2,01$, $2,35$, og $3,28$. Þar sem lengd bilanna er 1 hæð rétthyrninganna jafnframt flatarmál þeirra, þ.e. $(cos(xi)+3)⋅Δx=(cos(x_i)+3)⋅1=cos(x_i)$. Því fæst að nálgun á flatarmáli $A$ sé

$$L_5=3,54+2,58+2,01+2,35+3,28=13,76$$

Raunverulegt flatarmál svæðisins er $A=15−sin(1)+sin(6)≈13,88$. Skekkjan er því $13,88−13,76=0,12$ eða u.þ.b. $0,9%$ munur, sem hlýtur að teljast nokkuð gott miðað við nálgun sem notast við ansi fá hlutbil.