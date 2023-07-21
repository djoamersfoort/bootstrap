# DJO Bootstrap Thema

Het DJO Bootstrap thema, gebaseerd op [Zephyr](https://bootswatch.com/zephyr/). Door middel van SCSS wordt het basisthema overschreven met de DJO-kleuren.

## Kleuren

- ![#f03c15](https://placehold.co/15x15/180f75/180f75.png) `#180f75`
- ![#f03c15](https://placehold.co/15x15/03cea4/03cea4.png) `#03cea4`
- ![#f03c15](https://placehold.co/15x15/f03c15/db504a.png) `#db504a`
- ![#f03c15](https://placehold.co/15x15/f2c14e/f2c14e.png) `#f2c14e`
- ![#f03c15](https://placehold.co/15x15/6184d8/6184d8.png) `#6184d8`

## Installatie

Voor het omzetten van SCSS wordt gebruik gemaakt van `node-sass`. Ook is `bootstrap` nodig voor de basis-SCSS. Gebruik onderstaand commando om deze te installeren:

```bash
npm install
```

## Aanpassen

Om aanpassingen te maken aan de kleuren en eventuele andere variabelen moet je bij `scss/main.scss` zijn. Zie ook de [Bootstrap documentatie](https://getbootstrap.com/docs/5.3/customize/overview/) voor meer informatie.

## Live Server

Bij het aanpassen is het handig om een voorbeeld te hebben van hoe alles eruit ziet. Hiervoor kan de `html/` map handig zijn. Hierin zit een placeholder-site die gebruik maakt van het huidige thema.

Deze site heeft echter wel CSS nodig. Hiervoor is het dus nodig om de live server op te starten:

```bash
npm run serve
```

Dit zorgt ervoor dat `css/main.css` automatisch build bij aanpassingen aan de SCSS-bestanden.

## Builden

Als het tijd is om te builden voer je het volgende uit:

```bash
npm run build
```

Het minified CSS-bestand is vervolgens te vinden in `dist/djo.min.css`.
