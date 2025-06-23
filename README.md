# Site GitHub Pages avec Docusaurus

# Website

Ce site web est construit en utilisant [Docusaurus 2](https://docusaurus.io/fr/), un generateur de site web statique moderne.

### Installation

```
$ yarn
```

### Développement Local

```
$ yarn start
```

Cette commande demare un server de developpement local et ouvvre une fenetre du navigateur. La plupart des modifications sont prises en compte en direct sans avoir besoin de redémarrer le serveur.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

Cette commande génère du contenu statique dans le répertoire `build` et peut être servi à l’aide de n’importe quel service d’hébergement de contenu statique.

### Déploiement

En utilisant SSH :

```
$ USE_SSH=true yarn deploy
```

Sans utiliser SSH :

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

Si vous utilisez GitHub Pages pour l’hébergement, cette commande est un moyen pratique de construire le site web et de le pousser vers la branche `gh-pages`.
