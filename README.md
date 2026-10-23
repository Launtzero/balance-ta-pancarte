# Super Pancarte

Site : https://launtzero.github.io/superpancarte/

Des idées plein les cartons, des slogans plein la rue.
La collection libre et collaborative des pancartes de manif.

- **Je poste** : envoie la photo de ta pancarte via le formulaire https://tally.so/r/vXGJe0 (anonyme, e-mail facultatif).
- **Je m'inspire** : cherche par mots-clés sur le site, pioche les idées, fais ta pancarte.

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | le site (page unique, sans dépendance) |
| `pancartes.json` | la liste des pancartes publiées : `{id, image, texte, tags[], ville, date, cause, w, h, alt}` |
| `images/` | les photos publiées, compressées en WebP, sans métadonnées, visages floutés |

Les photos arrivent d'abord dans un dépôt privé où elles sont vérifiées (visages, contenu) avant d'être publiées ici.

## Licence

- **Les slogans** sont libres : recopie-les, détourne-les, améliore-les.
- **Les photos prises par les personnes qui les envoient** sont publiées sous licence [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.fr) : réutilisation libre en citant « Super Pancarte » et en partageant de la même façon.
- **Les photos trouvées en ligne** restent la propriété de leurs auteurs (droits réservés). La source est indiquée quand elle est connue. Si tu es l'auteur d'une photo et souhaites la faire retirer ou créditer, ouvre une « issue » sur ce dépôt.
