# IT5 — Base de connaissances

Migration de la base Google Sites vers Markdown, le 7 novembre 2026.

**Import de travail à réviser.** Les formulations, langues et procédures existantes ont été conservées, sans compléter les sections inachevées ni valider les diagnostics techniques. Aucun changement n’a été apporté au site original.

## Articles

- [Accueil et liens de support](articles/home.md)
- [Passkit](articles/passkit.md)
- [Tourniquets anciens](articles/tourniquet.md)
- [Tourniquets V2](articles/tourniquet-v2.md)
- [Portes](articles/portes.md)
- [Moneris](articles/moneris.md)
- [Musique / Volumio](articles/musique.md)
- [Caméra](articles/camera.md)
- [Google TV](articles/googletv.md)
- [Imprimante](articles/imprimante.md)

## Utiliser dans VS Code et GitHub

1. Décompresser ce dossier et l’ouvrir dans VS Code.
2. Ouvrir un fichier `.md`, puis utiliser l’aperçu Markdown.
3. Réviser les articles et les points de [REVIEW.md](REVIEW.md).
4. Créer de préférence un dépôt **privé** pour la première révision, puis y ajouter le contenu du dossier. Conserver `articles/` et `assets/` ensemble pour que les images fonctionnent.

La publication publique et l’intégration au chatbot sont des étapes ultérieures. Ne pas importer sans distinction les instructions d’administration dans une base destinée aux utilisateurs non techniques.

## Organisation

- `articles/` : un fichier Markdown par page source, avec URL et statut dans l’en-tête YAML.
- `assets/` : images locales, lorsque le téléchargement est possible.
- `source-map.json` : correspondance des dix pages et empreintes des sources.
- `assets-manifest.json` : origine, dimensions et empreintes des images.
- `extraction-errors.json` : erreurs de téléchargement éventuelles (liste vide si aucune).
- `QA.md` : contrôles de migration.

Les liens internes ont été convertis en chemins Markdown relatifs. Les liens externes restent externes, notamment Microsoft Forms, SimpleHelp et la vidéo YouTube. Les fautes et références obsolètes du contenu source sont volontairement laissées à réviser. Les noms génériques des illustrations sont des repères de migration, pas des descriptions visuelles vérifiées.
