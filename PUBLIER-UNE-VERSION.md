# Publier une version (mémo)

1. Dans le dépôt de travail : monter `version` dans `package.json`, puis `npm run zip:firefox`.
2. Envoyer le zip et l'archive des sources sur addons.mozilla.org (*Upload New Version*, canal non listé), puis télécharger le `.xpi` signé.
3. **Renommer le fichier en `farental-bar.xpi`** : le lien « dernière version » du README pointe vers ce nom exact.
4. Ici : *Releases* → *Draft a new release*.
   - *Choose a tag* : `v<version>` (par exemple `v0.2.1`), *Create new tag*.
   - Titre : `Farental Bar <version>`, et deux ou trois lignes sur ce qui change.
   - Joindre `farental-bar.xpi`.
   - Laisse *Set as a pre-release* décoché : une pré-version n'est pas prise en compte par le lien « dernière version » du README.
   - *Publish release*.
5. Vérifier que https://github.com/anjclerc/farental-bar/releases/latest/download/farental-bar.xpi télécharge bien la nouvelle version.
