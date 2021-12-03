Eftirfarandi tvær reglur gilda fyrir [[yrðingar]] p,q:

			¬(p ∧ q) ≡ ¬p ∨ ¬q
			
			¬(p ∨ q) ≡ ¬p ∧ ¬q

Fyrir heiltölu n≥2gildir almennt fyrir [[yrðingar]] $p_1,p_2,...,p_n$ að
		$¬(p_1 ∧ p_2 ∧...∧ p_n) ≡ ¬p_1 ∨ ¬p_2 ∨...∨ ¬p_n$
		$¬(p_1 ∨ p_2 ∨...∨ p_n) ≡ ¬p_1 ∧ ¬p_2 ∧...∧ ¬p_n$
		
Athugið að reglurnar sýna hvernig hægt er að færa neitunarvirkja inn fyrir sviga sem breytir þá í kjölfarið [[og-un]] í [[eð-un]] og öfugt.

**Útleiðsla De Morgan fyrir [[mengi]]**

A ∩B = {x |x /∈A ∩B} 	(Skilgr. á fyllimengi)  
= {x |¬(x ∈A ∩B)} 		(Skilgr. á /∈)  
= {x |¬(x ∈A ∧x ∈B)} 	(Skilgr. á [[sniðmengi]])  
= {x |¬(x ∈A) ∨¬(x ∈B)} (De Morgan f. [[yrðingar]])  
= {x |x /∈A ∨x /∈B} 	(Skilgr. á /∈)  
= {x |x ∈A ∨x ∈B} 		(Skilgr. á fyllimengi)  
= {x |x ∈A ∪B} 			(Skilgr. á [[sammengi]])  
= A ∪B
