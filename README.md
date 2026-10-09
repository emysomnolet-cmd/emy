# Site vitrine témoin – restaurant

1. **Nouveau client** : dans `wrangler.jsonc`, remplacez `"name": "nom-du-site"` par un nom unique (minuscules, chiffres, tirets), par ex. `"chez-paul-lyon"`.
2. **Contenu** : dans `public/index.html`, modifiez chaque texte précédé de `<!-- À MODIFIER -->` (y compris le bloc JSON-LD et les balises `og:` dans `<head>`).
3. **Style** : dans `public/theme.css`, changez les variables du bloc `:root` (couleurs, polices, arrondis, espacements).
4. **Images** : remplacez les fichiers de `public/images/` en gardant les mêmes noms (JPG, ~1200 px max, < 200 Ko), puis adaptez les textes `alt`.
5. **Mentions légales** : complétez les champs entre crochets dans `public/mentions-legales.html`.
6. **Adresse du site** : remplacez `https://www.example.com/` par le vrai domaine (canonical, Open Graph, JSON-LD).
7. **Mise en ligne** : Cloudflare → Workers & Pages → Créer → Importer un dépôt Git → choisir le dépôt du client (commande de déploiement : `npx wrangler deploy`, sans commande de build).
8. Seul le dossier `public/` est publié ; `README.md` et `wrangler.jsonc` restent privés. Ajoutez ensuite le domaine du client dans Paramètres → Domaines et routes.
9. Avant publication, cherchez « 00 00 », « example » et « remplacer » : il ne doit plus rien rester.
