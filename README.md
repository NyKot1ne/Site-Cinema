# Site-Cinema

## Description
Ce projet consiste à créer une application web permettant aux clients d'un cinéma local d'accéder à des informations sur les films disponibles, dans le but d'attirer plus de jeunes des villages alentours. L'application repose sur l'API OMDb (The Open Movie Database) pour récupérer les données des films.

## Fonctionnalités

### Pages principales :

1. **Page d'accueil (index.html)**
   - Affichage de films tendances (minimum 3 films).
   - Informations affichées pour chaque film :
     - Poster.
     - Nom du film.
     - Lien pour en savoir plus (redirection vers `movie.html`).
     - Affichage d'un résumé du film.
     - Bouton pour charger plus de films de 2024.

2. **Page de recherche (search.html)**
   - Barre de recherche permettant de rechercher des films en temps réel.
   - Affichage des résultats sans rechargement de la page.
   - Pour chaque résultat affiché :
     - Poster du film.
     - Titre du film.
     - Lien pour en savoir plus (redirection vers `movie.html`).
   - Bouton pour charger plus de résultats.

3. **Page détails du film (movie.html)**
   - Informations affichées :
     - Titre du film.
     - Poster du film.
     - Grand résumé.
     - Genre du film.
     - Acteurs.
     - Notes obtenues par le film.
     - Date de sortie en DVD (formatée en français : jj/mm/aaaa).

## Technologies Utilisées

- **Frontend** : HTML, CSS, JavaScript
- **Backend** : Utilisation d'un serveur HTTP local (Extension Live Server sur VS)
- **API** : OMDb (The Open Movie Database)
- **Gestion de projet** : Git & GitHub

3. **Démarrer le serveur local** :
   - Avec Live Server (VS Code) :
     - Faites un clic droit sur `index.html` et cliquez sur **"Open with Live Server"**.

## Utilisation

1. Accédez à la page d'accueil pour voir les films tendances.
2. Effectuez des recherches sur la page `search.html` pour trouver des films.
3. Cliquez sur un film pour afficher ses détails sur la page `movie.html`.

## API OMDb

Pour récupérer des données depuis l'API OMDb :
- Créez un compte sur le site de l'OMDb.
- Demandez une clé API (elle sera envoyée par email).
- Utilisez la clé dans vos requêtes pour tous les fichiers js :
  ```
  https://www.omdbapi.com/?apikey=[votre_API_key]&s=[nom_du_film]
  ```

## Organisation Git

- **Branches** :
  - `main` : Branche principale avec le code stable.
  - `css/` : Dossier qui stock le code CSS.
  - `js/` : Dossier qui stock les codes JS.
  - `index.html` : Développement de la page d'accueil.
  - `search.html` : Développement d'une page de recherche.
  - `movie.html` : Développement d'une page de détail.

- NyKot1ne
