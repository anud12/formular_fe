
## Discusion starters
* Tabs vs spaces
* In ziua de azi e bine pentru javascript, e pe microcontrolere, nodejs in banci, NaN is number, 42ie e o valoare valida (nicioadata nu o sa scapam de IE) pentru input number, asa ca why javascript?

~~O sa iti spun o serie de cuvinte si tu imi spui ce sentimete iti trezesc~~
* wordpress
* php
* typescript

## CSS

* > css framework
    * > bootsrap
    * > tailwind
* > variabile css
    * > skinning
* > css media query (`@media(max-width: XXXXpx)`)
    * > dark mode
* > css processors
    * > scss
        * why?
    * > less
* > layouting
    * cum aliniez un buton in centrul header-ului?
    * > flex
    * > grid
        * grid mai usor decat flex? sau flex mai usor decat grid?

## JS
* > Promises
    * > `finally`
    * > `all`
    * > `allSetteled`
    * ce se intapmla daca intr-un promise nu se apeleaza nici un resolver?
        * > eventually se va curata din cauza `GC`-ului (garbage colector)
* diferenta intre arrow function si function
* diferenta intre `XMLHTTPREQUEST` si `fetch`
    * > low hanging fruit: promise based
    * > `fetch` prinde redirect
        * cand fetch intra pe catch?
*  Ai folosit patternul/modelul de map/reduce?
    1. > `map` / `filter`
    2. > `flat` / `find`
    3. > `flatMap` / `reduce`

## Typescript
* Typescript maine este abandonat pentru Coffescript, good/bad? 
* > interfara vs type
* > conditional types    
* > discriminating union
* > operatorul `satisfies`

## Nodejs
* > express
    * L-ai folosit?
    * > middleware
* cum pot sa am un websocket, dar fara websocket?
    * > transfer enconding chunked face ca un request sa nu are un size prestabilit

## Angular
* why angular
* de ce nu au folosit `promise` in loc de `rxjs`?
* diferenta intre `BehaviourSubject` si `ReplaySubject`

## Vue
* why vue?
* pain points vue 2
* good things about vue 3
* > redux (vuex?)
* > nuxt?
* ai avut nevoie sa folosesti vue pe langa SSR?


## Frontend General
* Graphql? propria noastra baza de date
* Mobile first or Desktop first design?
* Ce se intampla cand scriu in url `http://www.google.com`
    * > tcp / dns / browser request / etc.
    * Dar in chrome `reddit.com`?
        * > face append `https://www` automat
* Trebuie pentru un site care supporta si dark theme sa fac un banner
    > format imagini + svg
    * cum pot sa fac fundalul sa fie alb cand e white,
    * cum pot sa fac fundalul sa fie negru cand e dark
    * cum pot sa fac sa il maresc de 10 ori sa il folosesc in pagina de login fara sa fie pixelat?

* login in app sau in afara?
    * cum stii identitatea utilizatorului?
## CI/CD/OPS
* yaml sau json?
* > docker
    * instante minime?
    * `from` din mai multe imagini?
* > kubernetess
    * la ce e bun?
* Cand stiu ca un server accepta connectiuni?
* `build`
    * > webpack
        * why not rollup?
    * > babel
        * poate fetch fi backport-uit pentru IE6 de exemplu?
* > runner
    * ce folosesti sa automatizezi build-ul si deployul applicatiei?
    * > bamboo
    * > github actions
    * > gitlab actions

* Cand crapa aplicatia pe bune ce faci, unde te uiti?
* Cate medii e bine sa ai?

## Metodologii
* Experienta cu Agile?
    * La ce e util un scrum master?
    * 1 punct = o zi right?
* Kanban sau sprinturi?
    * why?

## Database
* Why SQL?
* > Migration strategy
    * regresion migration
* De ce nu google sheets?, e scalabila, e resilienta (cand crapa google?) rapoarte built in.
* ORM?


## Testing
* ce poti testa intr-un 'site web'?
* ce economisesti avand teste?
* Cand stii ca testele cu verde sunt chiar valide?
* Se poate automatiza browserul sa rulezi teste?
    * > selenium
    * > cypress
    * > integration test
    * > regresion test