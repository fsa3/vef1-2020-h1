# Hópaverkefni 1 - Vefforritun 1

## Höfundar

* Björn Borgar Magnússon, [bbm5@hi.is](mailto:bbm5@hi.is)
  * github: [`bbm5`](https://github.com/BearPays)
* Fannar Steinn Aðalsteinsson, [fsa3@hi.is](mailto:fsa3@hi.is)
  * github: [`fsa3`](https://github.com/fsa3)
* Ármann Schelander, [ars90@hi.is](mailto:ars90@hi.is)
* Páll Freyr Pálsson, [pfp2@hi.is](mailto:pfp2@hi.is)

## Skriptur og keyrsla á verkefni

Eftirfarandi skriptur eru til staðar í verkefni: 

* `npm run install` - sækir öll þau npm tól sem notuð eru í verkefninu
* `npm run browser-sync` - keyrir browser-sync sem fylgist með breytingum á index.html og styles.css
* `npm run sass` - þýðir úr sass yfir í css innihald skráarinnar `styles.scss` og skrifar í skránna `styles.css`
* `npm run dev` - keyrir skripturnar `sass` og `browser-sync` samhliða
* `npm run lint` - keyrir stylelint á allar `.scss` skrár
  * Notar reglurnar `stylelint-config-sass-guidelines` og `stylelint-config-standard`

## Uppsetning verkefnis

Í rót verkefnis eru [`index.html`](./index.html) (upphafssíða), [`styles.scss`](./styles.scss) (stílar verkefnis importaðir í eina skrá) ásamt skrám sem halda utan um stillingar á git, ritli, stylelint og npm tólum.

### Í rót eru síðan eftirfarandi möppur með eftirfarandi skrám:

* [`/img`](./img) - inniheldur allar myndir verkefnis
* [`/pages`](./pages) - inniheldur `.html` skrár fyrir allar síður nema upphafssíðu
  * [`latestrecipes.html`](./pages/latestrecipes.html)
  * [`recipe.html`](./pages/recipe.html)
  * [`videorecipes.html`](./pages/videorecipes.html)
* [`/styles`](./styles) - inniheldur alla stíla verkefnis skipt niður í `.scss` skrár
  * [`box.scss`](./styles/box.scss) - inniheldur stíla fyrir þau "uppskriftarbox" sem eru í verkefninu
  * [`config.scss`](./styles/config.scss) - inniheldur breytur og 'mixin'
  * [`footer.scss`](./styles/footer.scss) - inniheldr stíla fyrir sameiginlega fót síðanna í verkefninu
  * [`global.scss`](./styles/global.scss) - inniheldur global stíla sem eiga við allar síður verkefnisins eins og til dæmis grunnstillingar
  * [`grid.scss`](./styles/grid.scss) - inniheldur klasana fyrir grid, notar for-lykkju til þess að ítra út grid klösum
  * [`header.scss`](./styles/header.scss) - inniheldur stíla fyrir sameiginlega haus síðanna í verkefninu
  * [`hero.scss`](./styles/hero.scss) - inniheldur stíla fyrir 'hero' svæði síðanna í verkefninu
  * [`recipe.scss`](./styles/recipe.scss) - inniheldur stíla fyrir uppskriftir sem eru í verkefninu
  * [`sections.scss`](./styles/sections.scss) - inniheldur stíla fyrir einstök 'sections' sem eru á síðum verkefnis
