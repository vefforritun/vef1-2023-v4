# Vefforritun 1, 2023: Verkefni 4, CSS #2

[Kynning í fyrirlestri](https://youtu.be/uiIyHNxgalo).

## Markmið

- Nota flexbox til að stýra útliti
- Nota CSS custom properties (variables, breytur)

## Verkefni 2–6

Í verkefnum 2–6 munum við vinna áfram með sama verkefni og byggja ofan á það:

- [Verkefni 2](https://github.com/vefforritun/vef1-2023-v2) skilgreinir grunn HTML og síður.
- [Verkefni 3](https://github.com/vefforritun/vef1-2023-v3) bætir við grunn viðmóti.
- [Verkefni 4](https://github.com/vefforritun/vef1-2023-v4) setur upp útlit (e. layout).
- [Verkefni 5](https://github.com/vefforritun/vef1-2023-v5) setur upp grind og gerir útlit skalanlegt (e. responsive).
- [Verkefni 6](https://github.com/vefforritun/vef1-2023-v6) setur upp tól til að hjálpa við skipulag og vinnu.

## Verkefnið

Verkefnið er framhald af [verkefni 3](https://github.com/vefforritun/vef1-2023-v2), nýtir það efni sem uppsett er í því, og fylgir þeirri verkefnalýsingu. Leyfilegt er að nota [sýnilausn að verkefni 3](https://github.com/vefforritun/vef1-2023-v3-synilausn), sem gefin verður út föstudaginn 15. september.

Nú skal bæta við einföldu útliti á efnið með CSS. Allt útlitið skal vera í `./styles.css` og **allar** HTML skrár skulu vísa í það.

## Útlit

Fyrirmynd að útliti er í `fyrirmynd/` möppu. Öll skjáskot eru tekin í `1000px` breiðum Firefox vafra. Athugið að fyrirmynd er uppfærð frá verkefni 3.

Þar sem allt útlit skal útfæra í einni CSS skrá, skal huga að cascade og erfðum, þó er fullkomlega eðlilegt að endurtaka eigindi, en t.d. fyrir málsgreinar (`<p>`) þarf aðeins að taka fram einu sinni hvert margin þeirra er. Fyrir útlit sem notar „box“ er hægt að útfæra einu sinni og endurtaka þrisvar sinnum.

**Allt það sem tekið er fram í verkefni 3 gildir áfram nema annað komi fram hér**.

### Almennt

Gefið er `styles.css` skjal með grunn að lausn.

Gefið er HTML úr sýnilausn sem er æskilegt að nota, en ekki krafa.

### CSS Custom Properties

Nota skal skilgreind CSS custom properties sem gefin eru í `styles.css`.

### Box

Útfæra skal `.box` með því útliti sem kemur fram í fyrirmynd og nota sömu skilgreiningu á öllum stöðum.

### Myndir

Búið er að uppfæra myndir frá verkefni 3. Á „Um“ síðu skal birta myndir þar sem þær eru að hámarki `400px` háar og alltaf birtar frá topp og miðju (nota skal `object-fit`  og `object-position`).

### Leturgerðir

Nota skal `Lora` fyrir fyrirsagnir og `Noto Sans Display` fyrir meginmál leturgerðirnar frá Google Fonts. Sækja skal leturgerðirnar og geyma í `fonts/`.

### Takmarkanir

Aðeins skal nota eftirfarandi eigindi, og ef tekið fram, viðeigandi gildi:

- `background-color`
- `border` og nánari skilgreiningar
- `box-sizing`
- `color`
- `display: flex;`
  - önnur flex eigindi og `gap`
  - _ekki_ skal nota önnur gildi fyrir `display`
- `font-display`
- `font-family`
- `font-style`
- `font-weight`
- `list-style: none;`
- `margin-bottom` og `margin-top`
  - _ekki_ ætti að nota `margin-left` og `margin-right` heldur flexbox
- `padding` eigindi
- `src`
- `width`, `max-width`, `max-height`
- Þau eigindi notuð í `.sr-only` og ekki tiltekin hér ætti ekki að nota í annað.

Ekki skal nota önnur `display` gildi en `display: flex;` og ekki nota `text-align` til að miðja efni.

Ekki þarf að huga að skalanleika (síðan þarf ekki að líta vel út í undir `800px` skjá).

## Netlify

Setja skal upp verkefni á Netlify með því að hlaða upp skrám með „manual deploy“ _eða_ tengja GitHub repo.

## Mat

- 20% – Snyrtilega uppsett og gilt CSS.
- 20% – Aðeins leyfileg eigindi og gildi notuð.
- 60% – Útlit skv. fyrirmynd.

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 11. september 2023.

## Skil

Skila skal í Canvas, seinasta lagi fyrir lok dags fimmtudaginn 21. september 2023.

Skilaboð skulu innihalda:

- zip skrá með öllum skrám _eða_ hlekkur á almennt (e. public) GitHub.
- slóð á verkefni keyrandi á Netlify sem athugasemd („Add comment“ eða „Bæta við athugasemd“ á skilaskjá í Canvas).

Skila má eins oft og þið viljið þar til skilafrestur rennur út.

## Einkunn

Leyfilegt er að ræða, og vinna saman að verkefni en **skrifið ykkar eigin lausn**. Ef tvær eða fleiri lausnir eru mjög líkar þarf að færa rök fyrir því, annars munu allir hlutaðeigandi hugsanlega fá 0 fyrir verkefnið.

Ef stórt mállíkan (LLM, „gervigreind“, t.d. ChatGTP) er notað til að skrifa part af lausn skal taka það fram. [Sjá nánar á upplýsingasíða um gervigreind hjá HÍ](https://gervigreind.hi.is/).

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.1
