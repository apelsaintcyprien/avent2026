# L'enquête de l'Avent 2026

De Nazareth à la crèche : 14 témoins, 14 énigmes, une lettre par jour (30 novembre → 17 décembre).

## Contenu
- `index.html` : tout le site (carte illustrée + une page par jour)
- `videos/` : une vidéo par témoin, nommées `temoin-01.mp4` … `temoin-14.mp4`

## Mise en ligne (GitHub Pages)
Settings → Pages → Source : **Deploy from a branch**, branche `main`, dossier `/ (root)`.

## Ajouter une vidéo
1. Déposer le fichier dans `videos/` (ex. `temoin-02.mp4`).
2. Dans `index.html`, sur la ligne du jour (`n:2,…`), remplacer `video:""` par `video:"videos/temoin-02.mp4"`.

## Verrouillage
- Chaque jour s'ouvre à minuit à sa date ; le site arrive directement sur le témoin du jour.
- La lettre du jour s'affiche à 16 h 30 (`LETTER_HOUR`).
- La phrase finale s'affiche le 17 décembre à 11 h (`REVEAL_FINAL`).

## Mode aperçu (équipe)
Cliquer 3 fois sur « ENQUÊTE DE L'AVENT 2026 » en haut de la carte : tout s'ouvre sur ce navigateur. Bouton « Mode aperçu · quitter » pour revenir.
