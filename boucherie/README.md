# 🥩 App de réservation — Boucherie

Un seul fichier (`index.html`), aucune installation. Ouvrez-le dans un navigateur ou publiez le dossier (GitHub Pages : `https://<votre-site>/boucherie/`).

## Côté client
- Voir les morceaux disponibles du jour (prix, stock restant, badges Disponible / Bientôt épuisé / Épuisé)
- Réserver à l'avance : quantité, date de retrait, remarque — le stock se décompte automatiquement
- Suivi de « Mes réservations » sur son appareil

## Côté boucher (bouton « Espace boucher », code par défaut : **1234**)
- **Stock du jour** : ajouter / modifier / supprimer des pièces, ajuster le stock en un clic (+/−, bouton « Épuisé »)
- **Réservations** : liste avec nom, téléphone (cliquable), date de retrait ; marquer « Retirée » ou « Annuler » (le stock est remis automatiquement)
- Changer le code d'accès depuis l'app

## À savoir
- Les données sont stockées dans le navigateur (localStorage) : parfait pour une tablette au comptoir ou une démo. Pour partager le stock en temps réel entre les téléphones des clients et celui du boucher, il faudra brancher un petit backend (je peux le faire sur demande).
- Pensez à changer le code **1234** dès la première utilisation.
