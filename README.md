# Jana — DataQuiz (Seconde générale)

Application pédagogique gratuite pour réviser les notions de **données et de dictionnaire des données** à partir d'un exemple de bibliothèque.

## Contenu
- **Cours** : données, noms de données, identifiants, types A (alphabétique), N (numérique), D (date) et L (logique).
- **Quiz** : 12 questions sélectionnées au hasard, avec corrections expliquées.
- **Exercice pratique** : compléter le dictionnaire des données d'une bibliothèque et consulter la correction.

## Utilisation
Ouvrir `index.html` dans un navigateur sur ordinateur ou téléphone. L'application ne requiert ni connexion, ni compte, ni bibliothèque JavaScript externe. Le meilleur score du quiz est enregistré localement dans le navigateur.

## Publication sur Cloudflare Pages via GitHub
1. Aller dans **Cloudflare > Workers & Pages > Create > Pages > Connect to Git**.
2. Autoriser le dépôt GitHub **Adelovitch/jana**.
3. Sélectionner la branche `main`.
4. **Framework preset** : `None`.
5. **Build command** : laisser vide.
6. **Build output directory** : `/` (racine du dépôt).
7. Publier. Une URL en `*.pages.dev` sera proposée par Cloudflare.

Les futurs commits sur `main` pourront déclencher un redéploiement automatique si le projet Pages est connecté à GitHub.

## Technique
Projet statique (HTML, CSS et JavaScript natifs) : aucun serveur, aucune API, aucun tracker, aucune donnée personnelle collectée. Les scores sont conservés uniquement dans le navigateur.
