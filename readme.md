# Hópverkefni 1

Fyrsta hópverkefnið í vefforritun 1 á haustönn 2020. <br/>
Í hópinum eru;

 * **Bryndís Rósa Sigurpálsdóttir** *brs58@hi.is*,
 * **Eydís Sjöfn Kjærbo**,  *esk12@hi.is*
 * **Katarina Kekic**  *kka10@hi.is*
 * **Kristín Eva Ólafsdóttir** *keo7@hi.is*

Notendanöfnin hópameðlima á github eru ;<br/>
*bryndisrosa97* hjá Bryndísi<br/>
*eydissjofn* hjá Eydísi <br/>
*katkek* hjá Katarinu <br/>
*kristin3va* hjá Kristínu <br/>

## Lýsing á verkefni

Verkefnið felst í því að smíða vef eftir forskrift.

Gefin er [hönnun í Figma](https://www.figma.com/file/Ld0BojedvArxiADpq80wVD/Vefforritun-1-2020-h%C3%B3pverkefni-1)

Allt efni, litir, stærði o.s.fr er tekið úr Figma skjalinu.

Ekki verður útfærð nein virkni fyrir takka eða form.

Eins og fram hefur komið verður verkefnið unnið af **Bryndísi**, **Eydísi**, **Katarinu** og **Kristínu**.

Notast verður við Git og GitHub í hópavinnunni. Hópmeðlimir munu „committa“ allan kóða og vinna gegnum Git.

## Hefjumst handa

Náð er í verkefnið með því að skrifa eftirfarandi í Terminal/Command Prompt
```
git clone https://github.com/katkek/vef1-2020-h1.git
```

### Tæki og tól
Skilyrði er  að hafa npm *pakkastjóra* (package manager) til að geta keyrt skipanirnar. Hópverkefnið er sett upp með Node.js: https://nodejs.org/en/

Setja skal upp node-sass, browser-sync, stylelint og concurrently til að nýta Sass og geta gert breytingar sem sjást strax í vafra. Sass og stylelint er sett upp mep `stylelint-config-sass-guidelines` og `stylelint-config-standard`.

Fyrst þarf að búa til `package.json` með því að keyra `npm init` í verkefnamöppu.

Síðan þarf að sækja hvert tól með `npm install <nafn á tóli>`.

 [Nánari upplýginar varðandi uppsetningu má nálgast hér. ](https://github.com/vefforritun/vef1-2020/blob/master/fyrirlestrar/06/06.2.npm.md#t%C3%B3l-%C3%AD-verkefnum). Þegar skipunin `npm run lint -s` er keyrð skal keyra stylelint með þessum reglum og ættu engar villur að koma fram.

 Til að passa upp á samræmi í verkefninu eru skrárnar `.gitignore`, `.gitattributes` og `.editorconfig` notaðar sem voru gefnar.


 ### Uppsetning á verkefninu

Í undirmöppunni 'styles/' þá höfum við sass(.scss) skrár og eru þær 11 talsins. Í stuttu máli, gerir þetta hópnum kleift að skrifa nákvæmari sass-skjöl sem eru sniðin fallega og þurfa minna af endurteknum aðferðum sem finnast almennt hjá CSS kóða.  Hver sass(.scss) skrá stjórnar ákveðnum eiginleika t.d  styles/header.scss sjá alfarið um stíla alla eiginleika sem viðkoma headernum. 

Við höfum gróflega farið yfir uppsetningu verkefnisins hér fyrir ofan en við höfum í þessu verkefni eftirfarandi skrár og gögn:

Skipting og skipulag
- fjórar html skrár sem eru síðurnar okkar (*index.html*, *Latesrecipes.html*, *index.html*, *method.html*)
- í möppunni 'styles/' 7 svg myndir og 23 png ([Hægt að nálgast þær hér](https://github.com/katkek/vef1-2020-h1/tree/master/img))
- ein .css skrár (grid-overlay.css) verður búin til með "npm run sass"-skipun.
- eina .scss skrá (styles.scss)
- .stylelintrc skrá
- package.json skrá
- package-lock.json skrá
- .gitignore skrá
- .gitattributes skrá
- .editorconfig skrá
- styles folder (hér eru fleiri scss skrár sem er notast við að stílbreyta síðuna)
--- book.scss, config.scss, footer-bar.scss, global.scss, grid.scss, header.scss, hero.scss, latest-recipe.scss, method.scss, newsLetter.scss og videohero.scss


### Uppsetning á vefsíðunni

Hér er linkur á vefsíðuna: https://notendur.hi.is/~esk12/vefforritun/hopverkefni1/index.html

Athugið að menu-barinn bendir á hinar síðurnar. Heitin og innihald síðanna passa ekki enda viljum við halda hönnuninni og geta gefið aðgang að öllum síðum.

### Keyrsla á verkefninu

Til að byrja með þýðum við scss yfir í css. Við gerum það með að Opna Terminal / Command Prompt og skrifa:

```
npm run sass
```

Því næst skrifum við inn í Terminal/ Command Prompt: 

```
npm run dev
```
Þegar skipunin `npm run dev` er keyrð mun verkefnið keyra upp vefþjón með browser-sync, þýða sass skrár og fylgjast með breytingum á HTML og Sass.

## Mat

* 10% - `README` eftir forskrift, tæki og tól uppsett
* 15% – Snyrtilegt, gilt (skv. stylelint) CSS/Sass, gilt og aðgengilegt HTML
* 15% – Almennt útlit
* 15% – Forsíða
* 15% – Listasíða
* 15% – Uppskriftasíða
* 15% – Almennur skalanleiki

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 5. október 2020.


## Hönnun

Upprunaleg hönnun eftir [Meghan Regior](https://twitter.com/meghanregior) fyrir verkefni í vefforritun 2016. Flutt í Figma og uppfært af Óla.

> Útgáfa 0.1
