# Calculateur de Temps de Trajet

Ce projet est une application web simple permettant de calculer le temps de trajet entre deux points en utilisant l'API OpenRouteService et la bibliothèque Leaflet pour l'affichage de la carte.

## Fonctionnalités

- Sélectionnez un lieu de départ et un lieu de destination directement sur la carte en cliquant.
- Calculez le temps de trajet en voiture entre ces deux points.
- Visualisez le tracé du trajet sur la carte.
- Réinitialisation automatique des champs et des marqueurs après chaque calcul pour une nouvelle sélection.

## Technologies utilisées

- **HTML** : Structure de la page web.
- **TailwindCSS** : Framework CSS utilitaire pour le style.
- **DaisyUI** : Composants UI pour TailwindCSS.
- **Leaflet** : Bibliothèque JavaScript pour les cartes interactives.
- **OpenRouteService API** : Service d'itinéraire pour calculer les trajets.

## Installation

1. Clonez le dépôt sur votre machine locale :
   ```bash
   git clone https://github.com/Cyber-Thibaut/calculateur-temps-trajet.git
   ```

    Ouvrez le fichier `index.html` dans votre navigateur pour tester l'application.

2. Configuration

    Clé API OpenRouteService : Remplacez la clé API par votre propre clé dans le code JavaScript. Vous pouvez obtenir une clé API gratuite sur [OpenRouteService](https://openrouteservice.org/).

    ```const apiKey = 'votre_clé_api_ici';```

3. Utilisation

    Cliquez sur la carte pour sélectionner un lieu de départ et un lieu de destination.
    Appuyez sur le bouton "Calculer le temps de trajet" pour obtenir l'itinéraire et le temps de trajet estimé.
    Le trajet est affiché sur la carte et les détails du temps de trajet sont affichés sous le bouton.

Licence

Ce projet est sous licence. Voir le fichier [LICENSE](https://github.com/Cyber-Thibaut/Calculateur-temps-trajet/tree/main?tab=License-1-ov-file) pour plus de détails.
Auteur

    Thibaut Cellier - Créateur principal
