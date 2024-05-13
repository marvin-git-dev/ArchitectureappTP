# ArchitectureappTP

Ce projet est une extension de l'application basique de liste de tâches. Il intègre des fonctionnalités avancées telles que la catégorisation des tâches, l'utilisation de design patterns tels que Singleton et des principes OOP comme l'héritage et l'abstraction.

## Fonctionnalités

- **Catégorisation des Tâches :** Les tâches peuvent être ajoutées sous différentes catégories (travail, maison, divers) avec des couleurs associées à chaque catégorie pour une identification facile.
- **Singleton pour Gestion des Tâches :** Un singleton est utilisé pour gérer un accès unique à la liste des tâches à travers l'application.
- **Héritage de Classe :** Implémentation d'une classe de tâches avancée qui hérite de la classe de tâches de base.
- **Abstraction de Classe :** Utilisation d'une classe abstraite `TaskRenderer` pour définir le rendu des tâches, avec des classes concrètes pour les rendus spécifiques aux catégories.

## Structure du Projet

Le projet suit l'architecture MVC (Modèle-Vue-Contrôleur) et est organisé en fichiers suivants :
- `index.html` : La page principale de l'application.
- `style.css` : Les styles CSS pour la mise en page de l'application.
- `model.js` : Contient le modèle de données de l'application, gérant les tâches et catégories.
- `view.js` : Gère la présentation des tâches et la manipulation des éléments de l'interface utilisateur.
- `controller.js` : Fait le lien entre le modèle et la vue, gérant les interactions de l'utilisateur.
