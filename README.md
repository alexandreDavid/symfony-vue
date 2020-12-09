## Suivre les étapes suivantes :
* https://symfony.com/doc/current/page_creation.html
* https://symfony.com/doc/current/frontend/encore/simple-example.html
* https://symfony.com/doc/current/frontend/encore/vuejs.html

A la suite de ces étapes, vous avez la possibilité de monter de version le framework Vue.js en faisant les manipulations suivantes :
Remplacer les versions des dépendances suivantes dans votre fichier package.json :
"vue": "^3.0.0",
"vue-loader": "^16.1.0"

Lancer les commandes suivantes sur votre projet
```
yarn add @vue/compiler-sfc -D
yarn remove vue-template-compiler
yarn install
```

A partir de ce moment, vous pouvez utiliser Vue3 dans votre projet Symfony