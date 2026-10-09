# Site vitrine témoin – restaurant

1. **Contenu** : dans `index.html`, modifiez chaque texte précédé d'un commentaire `<!-- À MODIFIER -->` (y compris le bloc JSON-LD et les balises `og:` dans `<head>`).
2. **Style** : dans `theme.css`, changez les variables du bloc `:root` (couleurs, polices, arrondis, espacements).
3. **Images** : remplacez les fichiers de `images/` en gardant les mêmes noms (JPG, ~1200 px de large max, < 200 Ko), puis adaptez les textes `alt`.
4. **Mentions légales** : complétez les champs entre crochets dans `mentions-legales.html`.
5. **Adresse du site** : remplacez `https://www.example.com/` par le vrai domaine (canonical, Open Graph, JSON-LD).
6. **Mise en ligne** : Cloudflare → Workers & Pages → Créer → Pages → « Importer des ressources » (glisser le dossier) ou connecter le dépôt Git.
7. Réglages Pages : aucun framework, commande de build vide, dossier de sortie `/`.
8. Ajoutez ensuite le nom de domaine du client dans l'onglet « Domaines personnalisés ».
9. Avant publication, cherchez « 00 00 », « example » et « remplacer » : il ne doit plus rien rester.
