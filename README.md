# Créer une application de blog en JavaScript

## Objectifs :

- Développer une application web de blog avec JavaScript.
- Implémenter des interfaces utilisateurs pour les fonctionnalités suivantes :
- Ajouter un article.
- Modifier un article.
- Supprimer un article.
- Afficher tous les articles.
- Intégrer un mode clair/sombre.
- Ajouter un menu hamburger pour une meilleure navigation en mode responsive.

# Spécifications :

## Page principale :

## Affiche une liste des articles de blog.

     Chaque article contient :
       Un titre.
       Un contenu.
       Une date de création.
       Boutons "Modifier" et "Supprimer".

## Formulaire d’ajout/modification :

- Permet de saisir :
  Le titre de l’article.
  Le contenu de l’article.
  Affiche un bouton "Enregistrer".

## Mode clair/sombre :

- Ajouter un bouton pour basculer entre le mode clair et le mode sombre.
- Sauvegarder la préférence de l'utilisateur dans le localStorage.

## Menu hamburger (responsive) :

Créez un menu qui s’affiche sous forme de hamburger en mode mobile.
Le menu contient des liens vers :
La page d’accueil.
Un formulaire pour ajouter un article.

# Contraintes techniques :

Utiliser uniquement HTML, CSS et JavaScript pur (sans framework).
Utiliser localStorage pour sauvegarder les articles.
La liste des articles doit être récupérée dynamiquement depuis le localStorage.
Le design doit être responsive.

# Étapes recommandées :

## Étape 1 : Structure HTML

    Créez les pages suivantes :
    index.html pour afficher la liste des articles.
    Une section ou un formulaire pour l’ajout/modification d’articles.

## Étape 2 : Styles CSS

    Implémentez un thème clair et sombre en utilisant des variables CSS.
    Ajoutez des styles pour le menu hamburger en mode mobile.

## Étape 3 : Fonctionnalités JavaScript

    Gestion des articles :

## Ajouter un article :

    Collecter les données du formulaire et les enregistrer dans localStorage.

## Modifier un article :

    Charger les données dans le formulaire pour édition.
    Mettre à jour l’article dans localStorage.

## Supprimer un article :

    Retirer l’article sélectionné de localStorage.

## Afficher tous les articles :

    Charger les articles depuis localStorage et les afficher sur la page principale.

## Mode clair/sombre :

    Ajouter un bouton "Mode clair/sombre".
    Basculer entre les thèmes et sauvegarder la préférence de l’utilisateur.

## Menu hamburger :

    Implémentez un bouton pour ouvrir/fermer le menu en mode mobile.

# Livrables attendus :

    Code source organisé avec des commentaires.
    Une application fonctionnelle et responsive.
    Un mode clair/sombre qui persiste après le rafraîchissement de la page.

# Critères d'évaluation :

L'application respecte les fonctionnalités demandées.
Le design est esthétique et responsive.
Le code est bien structuré et commenté.
Le mode clair/sombre fonctionne correctement.
Le menu hamburger est fluide et intuitif.
