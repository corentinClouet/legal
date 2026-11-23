# Wild Games — politiques de confidentialité

Contenu du dépôt public `legal` (GitHub Pages), qui héberge la politique de
confidentialité de chaque jeu. Un dossier par jeu :

- `wild-wings/index.html` : politique de Wild Wings (français et anglais) ;
- `wild-wings/conditions/index.html` : conditions d'utilisation de Wild Wings (français et anglais), dont Google Play demande le lien ;
- `tak-tik/index.html` : politique de Tak Tik (français et anglais), à l'adresse
  `https://corentinclouet.github.io/legal/tak-tik/`.

Adresse de Wild Wings une fois le site en ligne :
`https://corentinclouet.github.io/legal/wild-wings/` (conditions : `.../wild-wings/conditions/`)

La source de référence reste dans le dépôt du jeu : `docs/legal-site/`.

- **Tak Tik** : ne touche pas à `tak-tik/` ici. Le workflow `legal-sync.yml` de
  tak-tik remplace ce dossier et pousse sur `main` à chaque fusion qui change la
  politique, avec une clé de déploiement de ce dépôt (voir `docs/automatisation.md`
  de tak-tik).
- **Wild Wings** : après chaque modification, recopie le dossier dans `legal` et
  pousse sur `main` (ou installe le même workflow dans wild-wings).
