# Kit de Démarrage Angular AIWA

Bienvenue sur le Kit de Démarrage Angular AIWA (Artificial Intelligence Workshop & Arena) ! Ce projet fournit une base solide et pré-configurée pour démarrer rapidement le développement d'applications web modernes avec Angular et Tailwind CSS.

## Objectif

Ce kit de démarrage vise à :

*   Fournir une structure de projet Angular organisée.
*   Intégrer et configurer Tailwind CSS pour un stylisme utilitaire efficace.
*   Inclure une configuration de base pour le routage.
*   Mettre en place des polices personnalisées (Helvetica Now Text).
*   Offrir un point de départ simple avec une page d'accueil et une page 404.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils suivants sur votre machine :

*   [Node.js](https://nodejs.org/) (Version LTS recommandée)
*   [npm](https://www.npmjs.com/) (généralement inclus avec Node.js)
*   [Angular CLI](https://angular.io/cli) (installez globalement avec `npm install -g @angular/cli`)

## Installation
 **Installez les dépendances** du projet :
    ```bash
    npm install
    ```

## Utilisation

### Commande pour démarrer le serveur

Utilisez la commande suivante pour démarrer le serveur de développement Angular :

```bash
ng serve
```

## Remarque sur la Compatibilité de Tailwind CSS

Si vous rencontrez des problèmes de compatibilité entre Angular et certaines versions de Tailwind CSS, vous pouvez envisager d'utiliser le CDN de Tailwind pour une version plus récente ou plus ancienne. Cela peut être utile pour contourner les problèmes liés à la configuration ou aux conflits de dépendances.

Pour utiliser le CDN, ajoutez simplement le lien suivant dans le fichier `index.html` de votre projet :

```html
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@<version>/dist/tailwind.min.css" rel="stylesheet">
```

Remplacez `<version>` par la version souhaitée. Notez que l'utilisation du CDN peut ne pas offrir toutes les fonctionnalités disponibles avec une installation locale.
