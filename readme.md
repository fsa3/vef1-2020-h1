# Hópaverkefni 1 - Vefforritun 1

## Höfundar

* Björn Borgar Magnússon, [bbm5@hi.is](mailto:bbm5@hi.is) 

* Fannar Steinn Aðalsteinsson, [fsa3@hi.is](mailto:fsa3@hi.is)

* Ármann Schelander, [ars90@hi.is](mailto:ars90@hi.is)

* Páll Freyr Pálsson, [pfp2@hi.is](mailto:pfp2@hi.is)

## Global styles

Búið að skilgreina style fyrir h1, h2 0g h3 þannig nota það alls staðar þar sem á við.

Líka búinn að skilgreina klasana .brown-text og .brown-text__bold og gray-text

Þannig það ætti að vera hægt að nota þessa styles á mjög mikið af texta í verkefninu og það nægir líka á mörgum stöðum að skilgreina bara h1, h2 osfrv þar sem það eru komnir stílar á það

## Skriptur og keyrsla á verkefni

Eftirfarandi skriptur eru til staðar í verkefni: 

* `npm run install` - sækir öll þau npm tól sem notuð eru í verkefninu
* `npm run browser-sync` - keyrir browser-sync sem fylgist með breytingum á index.html og styles.css
* `npm run sass` - þýðir úr sass yfir í css innihald skráarinnar `styles.scss` og skrifar í skránna `styles.css`
* `npm run dev` - keyrir skripturnar `sass` og `browser-sync` samhliða
* `npm run lint` - keyrir stylelint á allar `.scss` skrár
  * Notar reglurnar `stylelint-config-sass-guidelines` og `stylelint-config-standard`

## Uppsetning verkefnis

Í rót verkefnis eru `index.html` (upphafssíða), `styles.scss` (stílar verkefnis sameinaðir í eina skrá) ásamt skrám sem halda utan um stillingar á git, ritli, stylelint og npm tólum.

Í rót eru síðan eftirfarandi möppur með eftirfarandi skrám:

* `img` - inniheldur allar myndir verkefnis
* `pages` - inniheldur `.html` skrár fyrir allar síður nema upphafssíðu
  * `latestrecipes.html`
  * uppskriftarsíða
  * `videorecipes.html`
* `styles` - inniheldur alla stíla verkefnis skipt niður í `.scss` skrár
  * SKRIFA LÝSINGU Á ÖLLUM SCSS SKRÁM ÞÉGAR ÞÆR ERU KLÁRAR
