# QG 4/4/48

Application de pilotage de **La Saintes 4/4/48**, épreuve d'endurance en stand-up paddle sur la Charente (3 au 5 juin 2028, zone de la Palue, Saintes).

Association Saintes 4/4/48, au profit des Bagouz' à Manon.

## Mise en ligne sur GitHub Pages

1. Crée un dépôt, par exemple `qg-448`.
2. Dépose tous les fichiers de ce dossier à la racine du dépôt (`index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, le dossier `icons`).
3. Dans le dépôt : **Settings > Pages > Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.
4. Attends une minute, l'adresse s'affiche : `https://<ton-pseudo>.github.io/qg-448/`.

## Installer sur le téléphone

- **Android (Chrome)** : ouvre l'adresse, menu ⋮ > *Installer l'application*.
- **iPhone (Safari)** : bouton Partager > *Sur l'écran d'accueil*.

## Ce qu'il faut savoir

- **Les données restent sur le téléphone**, dans le navigateur. Rien n'est envoyé sur GitHub. Fais une sauvegarde chaque semaine depuis *Réglages > Télécharger la sauvegarde*. Pour passer les données à Delphine, envoie-lui le fichier et elle fait *Restaurer une sauvegarde*.
- **Assistant IA** : colle ta clé API Anthropic dans *Réglages*. Elle reste stockée sur le téléphone. Ne la mets jamais dans un fichier du dépôt.
- **Hors connexion** : l'appli s'ouvre et fonctionne sans réseau une fois installée. Seul l'assistant a besoin d'internet.
- **Mise à jour** : quand tu remplaces `index.html`, change aussi `VERSION` dans `sw.js` (`qg448-v1` devient `qg448-v2`) pour que les téléphones récupèrent la nouvelle version.
- Le scan Google Drive n'existe que dans la version claude.ai.
