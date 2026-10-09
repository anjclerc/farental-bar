# Farental Bar — Confidentialité / Privacy policy

*Dernière mise à jour / Last updated: 9 octobre 2026 / October 9, 2026*

## Français

Farental Bar est une extension non officielle, créée par un joueur, qui affiche dans la barre d'outils l'état de ta tâche en cours dans le jeu Farental.

**Ce que l'extension utilise**
- Le **dernier lieu atteint** (destination du dernier voyage vu), pour centrer la carte. Enregistré dans le stockage local de ton navigateur.
- Le **lien de stream** que tu colles dans ses réglages (créé sur farental.ch/account, section *Widget de stream*). Il est enregistré uniquement dans le stockage local de ton navigateur.
- Tes **réglages** (langue, thème, intervalle d'actualisation…), enregistrés au même endroit.

**Ce que l'extension envoie**
- Une seule requête, en lecture : `https://farental.ch/stream/task/{lien}/data`, qui renvoie le titre et le temps restant de ta tâche en cours. Elle part directement de ton navigateur vers farental.ch.
- Seulement si tu cliques sur le bouton **Carte** : un nouvel onglet ouvre la carte communautaire sur `umap.openstreetmap.fr`, avec dans l'adresse le nom du lieu où se trouve ton personnage (ex. `?feature=Balanol`). L'extension elle-même n'envoie rien à ce site.
- Rien d'autre : pas de statistiques, pas de publicité, pas de serveur de l'auteur, pas de service tiers. L'auteur de l'extension ne reçoit aucune donnée.

**Ce que l'extension lit dans le navigateur**
- L'adresse des onglets ouverts sur farental.ch, uniquement pour afficher l'onglet du jeu déjà ouvert au lieu d'en ouvrir un nouveau.
- Le thème clair ou sombre du navigateur, pour adapter les couleurs de l'icône.

**Effacer tes données** : retire le lien dans les réglages de l'extension, ou désinstalle-la. Si ton lien de stream a pu être vu par quelqu'un, régénère-le sur farental.ch/account : l'ancien cesse de fonctionner.

Le code source est disponible pour vérification. Contact : via le dépôt du projet ou l'adresse indiquée sur la fiche du store.

## English

Farental Bar is an unofficial extension, made by a player, that shows the state of your current task in the game Farental in the browser toolbar.

**What the extension uses**
- The **last place reached** (destination of the last journey seen), to centre the map. Stored in your browser's local storage.
- The **stream link** you paste in its settings (created on farental.ch/account, *Stream widget* section). It is stored only in your browser's local storage.
- Your **settings** (language, theme, refresh interval…), stored in the same place.

**What the extension sends**
- A single read-only request: `https://farental.ch/stream/task/{link}/data`, which returns the title and remaining time of your current task. It goes directly from your browser to farental.ch.
- Only if you click the **Map** button: a new tab opens the community map on `umap.openstreetmap.fr`, with the name of your character's location in the address (e.g. `?feature=Balanol`). The extension itself sends nothing to that site.
- Nothing else: no analytics, no ads, no server run by the author, no third-party service. The author of the extension receives no data.

**What the extension reads in the browser**
- The address of tabs open on farental.ch, only to show the game tab that is already open instead of opening a new one.
- The browser's light or dark theme, to adapt the icon colours.

**Deleting your data**: remove the link in the extension settings, or uninstall the extension. If your stream link may have been seen by someone else, regenerate it on farental.ch/account: the old one stops working.

The source code is available for review. Contact: through the project repository or the address shown on the store listing.
