Diffurjafna er jafna sem sýnir tengsl eins eða fleiri falla við [[afleiður]] sínar. Til dæmis

$$f′(x)=2xe^x$$

Það að leysa diffurjöfnu snýst um að ákvarða fallið eða föllin. Lausnin við diffurjöfnunni hér að ofan er t.a.m.

$$f(x)=x2e^x−2e^x+C$$

þar sem $C$ er fasti. Diffurjöfnur hafa almennt ekki ótvírætt ákvarðaðar lausnir nema gefnar séu fleiri upplýsingar. Ef við hefðum t.a.m. fengið þær upplýsingar að $f(0)=3$ þá gætum við séð að

$$f(0)=0⋅2e^0−2e^0+C=−2+C=3$$

Með því að einangra $C$ fæst að $C=3+2=5$ og lausnin væri því

$$f(x)=x2e^x−2e^x+5$$

þessar upplýsingar, þ.e. $f(0)=5$ eru kallaðar [[upphafsgildi]] og eru svona diffurjöfnur því gjarnan kallaðar [[upphafsgildisverkefni]].

Diffurjöfnur eru eitt mikilvægasta málefni stærðfræðigreiningarinnar og eitt helsta viðfangsefni þeirra sem hagnýta stærðfræði eins og verkfræðingar og eðlisfræðingar. Almennt er mjög erfitt að leysa diffurjöfnur og eru margar þeirra jafnvel óleysanlegar með analytískum aðferðum. Þó er auðveldara að leysa sumar gerðir af diffurjöfnum en aðrar.

----

**Aðgreinanlegar diffrujöfnur**

Gefum okkur að eitthvað fall $y=F(x)$ uppfylli að $F′(x)=f(x)$, m.ö.o. þá er $F(x)$ [[stofnfall]] $f(x)$. Við vitum ekki hvað $F(x)$ er en við þekkjum $f(x)$. Við gætum einnig ritað þetta svona

$$\frac{dy}{dx}=f(x)$$

Svona diffurjafna kallst _aðgreinanleg diffurjafna_ af því hana má skrifa sem

$$dy=f(x)dx$$

þar sem við erum einungis með y vinstra megin og einungis með x hægra megin. Við höfum m.ö.o. greint breytistærðir diffurjöfnunnar að. Þetta er einstaklega þægileg gerð diffurjafna því þetta má leysa með því að heilda báðar hliðar jöfnunnar

$$∫dy=∫f(x)dx⇔y=∫f(x)dx$$

og þar sem að $y=F(x)$ þá þekkjum við nú gildi $F(x)$, af því gefnu að við kunnum að heilda $f(x)$

**Dæmi**

Lítum á diffurjöfnuna $\frac{dy}{dx}=6x^2$. Hún er aðgreinanleg þar sem að hana má rita sem

$$dy=6x^2dx$$

Við getum nú heildað báðar hliðar og fengið að

$$y=∫6x^2dx=2x^3+C$$

---

**Óaðgreinanleg diffrujafna** 

Ef við höfum diffurjöfnuna $\frac{dy}{dx}=e^{xy}$ þá er engin leið fyrir okkur að aðgreina diffurjöfnuna þannig að við séum einungis með y vinstra megin og x hægra megin jafnaðarmerkisins. Hún er því ekki aðgreinanleg eða óaðgreinanleg.

Skoðið [[upphafsgildisverkefni]]