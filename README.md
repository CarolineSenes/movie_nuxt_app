
# Application de sorties de films

Application de sorties de films réalisée avec Nuxt.js, l'API de The Movie Database
et déployée sur Heroku.

[--> Démo live](https://github.com/CarolineSenes/movie_nuxt_app/blob/master/assets/imgs/screenshots/mobile_movies.png)
## Badges
[![CodeFactor](https://www.codefactor.io/repository/github/carolinesenes/movie_nuxt_app/badge)](https://www.codefactor.io/repository/github/carolinesenes/movie_nuxt_app)

![W3C Validation](https://img.shields.io/w3c-validation/default?targetUrl=https%3A%2F%2Fmovie-nuxt-app.herokuapp.com%2F)
## Screenshots

![desktop_movies](https://github.com/CarolineSenes/movie_nuxt_app/blob/master/assets/imgs/screenshots/desktop_movies.png)
![desktop_movie](https://github.com/CarolineSenes/movie_nuxt_app/blob/master/assets/imgs/screenshots/desktop_movie.png)
![mobile](https://github.com/CarolineSenes/movie_nuxt_app/blob/master/assets/imgs/screenshots/mobile_movies.png)
## Tech Stack

**Client:** NuxtJS, Sass
**Server:** Node

  
## Problème rencontré et solution

Pour utiliser Sass dans Nuxt avec les instructions de la [doc.](https://nuxtjs.org/fr/docs/configuration-glossary/configuration-css/), 
 il faut revenir sur Node v.14 car fibers n'est plus supporté 
 sur les dernières versions.


## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

## Ressources utilisées

 - [Doc. Nuxt.js](https://nuxtjs.org/fr/docs/get-started/installation)

  