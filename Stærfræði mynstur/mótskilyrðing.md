"Contraposition"

Önnur leið til þess að sanna staðhæfingu á forminu 

$\forall$x,(P(x)$\rightarrow$ Q(x))

er að nota mótskilyrðingu. Athugum að p $\rightarrow$q er jafngilt $\neg$q $\rightarrow$ $\neg$p

| p   | q   | p$\rightarrow$q | $\neg$p | $\neg$q | $\neg$q $\rightarrow$$\neg$p |
| --- | --- | --------------- | ------- | ------- | ---------------------------- |
| 0   | 0   | 1               | 1       | 1       | 1                            |
| 1   | 0   | 0               | 0       | 1       | 0                            |
| 0   | 1   | 1               | 1       | 0       | 1                            |
| 1   | 1   | 1               | 0       | 0       | 1                             |

Þ.a. ef við getum sannað að $\neg$q $\rightarrow$$\neg$p þá höfum við einnig sannað p $\rightarrow$q

Ef m og n eru [[heiltala]] og mn slétt tala þá er annaðhvort m eða n slétt tala.

**Dæmi**

Látum $P(x)$ tákna „$x$ er slétt tala“. Með [[óðal]] [[heiltala]] erum við að reyna að sýna fram á sanngildi [[yrðing]]arinnar  
$∀m, ∀n : P(mn) →(P(m) ∨P(n))$.  
Með því að nota mótskilyrðingu getum við í staðinn sannað  
$∀m, ∀n : (¬P(m) ∧¬P(n)) →¬P(mn)$.  
Gerum ráð fyrir að $m = 2k + 1$ og $n = 2\lambda + 1$ séu báðar oddatölur, þ.e. $¬P(m) ∧¬P(n)$ er sönn. Þá gildir skv. almennum reiknireglum að 
$m ·n = (2k + 1) ·(2\lambda + 1) = 4k\lambda + 2k + 2\lambda + 1 = 2(2k\lambda + k + \lambda) + 1$  
Þ.e.a.s. við höfum þá að mn er þá einnig oddatala, þ.e. $¬P(mn)$ er sönn.  
Við höfum því sannað mótskilyrðinguna og þar með setninguna.