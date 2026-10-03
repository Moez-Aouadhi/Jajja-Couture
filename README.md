# Jajja Couture — site web

```
jajja-couture/
├── index.html      la page
├── css/styles.css  couleurs, polices, mise en page
├── js/main.js      menu, filtres du lookbook, agrandissement des photos, formulaire, vidéos
└── images/         les 16 photos (optimisées)
```

## Voir le site
Double-cliquez sur `index.html`. Le fil Facebook, les vidéos et la carte ne s'affichent qu'une fois le site en ligne.

## À vérifier
- **WhatsApp** : le formulaire envoie la demande sur WhatsApp au +216 20 212 030. Si ce numéro n'a pas WhatsApp, changez `WHATSAPP_NUMBER` en haut de `js/main.js` (par ex. `21653946500`).
- **Vidéo** : le reel https://www.facebook.com/reel/1246817350901213 est intégré dans la section « La maison en vidéo ». Pour le changer, remplacez `FACEBOOK_REEL` en haut de `js/main.js` et le lien du bouton « Regarder sur Facebook » dans `index.html`. La vidéo ne s'affiche qu'une fois le site en ligne.

## Photos
Les photos sont classées par collection grâce au début de leur nom : `mariage-…`, `soiree-…`, `orientale-…`. Pour ajouter une photo au lookbook, copiez une ligne `<button class="look" …>` dans `index.html` et indiquez sa collection dans `data-cat` (`mariage`, `soiree` ou `orientale`).

## Couleurs
Toutes les couleurs sont en haut de `css/styles.css` (bloc `:root`).

## Mise en ligne
Glissez le dossier sur https://app.netlify.com/drop (gratuit), ou publiez-le sur GitHub Pages / tout hébergeur.
