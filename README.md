# Hôtels ISLAM – site web

Site statique (HTML uniquement, aucune dépendance).

- `index.html` : version arabe (page d'accueil)
- `fr.html` : version française

## Publier sur GitHub Pages (gratuit)

1. Créez un compte sur https://github.com puis un nouveau dépôt public (ex. `islam-hotels`).
2. Cliquez sur **Add file > Upload files** et déposez `index.html`, `fr.html` et `README.md`. Validez avec **Commit changes**.
3. Allez dans **Settings > Pages**. Sous *Build and deployment*, choisissez **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
4. Après 1 à 2 minutes, le site est en ligne sur `https://VOTRE-NOM.github.io/islam-hotels/`.

## Modifier le site

- Prix et textes : ouvrez le fichier sur GitHub, cliquez sur le crayon, modifiez, puis Commit.
- E-mail de réception des demandes de réservation : cherchez `var EMAIL=` dans chaque fichier et remplacez l'adresse.
