# 🥩 L'Aile ou la Cuisse — Site & réservations

Site vitrine premium + app de réservation, en un seul fichier (`index.html`), aucune installation. Ouvrez-le dans un navigateur ou publiez le dossier (GitHub Pages : `https://<votre-site>/boucherie/`).

## Le site
- Hero plein écran, histoire familiale sur 5 générations (frise 1898 → 2020), portraits de l'équipe
- Animations au défilement, navigation avec section active, menu mobile
- Contact : appel direct (06 01 22 70 15) et itinéraire Google Maps en un clic
- Toutes les images (morceaux, équipe, photo d'époque) générées avec Gemini — remplaçables

## Côté client
- Voir les morceaux disponibles du jour (photo, prix, stock restant, badges Disponible / Bientôt épuisé / Épuisé)
- Réserver à l'avance : quantité, date de retrait, remarque — le stock se décompte automatiquement
- Suivi de « Mes réservations » sur son appareil

## Photos des morceaux
Chaque pièce peut avoir une photo, visible par les clients. Dans l'espace boucher → Modifier une pièce :
- **📷 Prendre une photo** : ouvre directement l'appareil photo du téléphone
- **🖼️ Choisir une image** : depuis la galerie (par ex. une image générée avec Gemini)
- Les images sont automatiquement redimensionnées et compressées (rapides à charger)

### Générer des images réalistes avec Gemini
Ouvrez l'appli Gemini (ou gemini.google.com), collez un prompt ci-dessous, enregistrez l'image sur le téléphone, puis déposez-la via « 🖼️ Choisir une image » :

> Photo professionnelle très réaliste d'une entrecôte de bœuf crue persillée, posée sur un billot de boucher en bois, éclairage doux de vitrine de boucherie artisanale française, format paysage

Remplacez « entrecôte de bœuf crue persillée » par : *filet de bœuf*, *côtes de porc*, *poulet fermier entier*, *merguez fraîches*, *gigot d'agneau*… en gardant le reste du prompt pour un style homogène.

## Côté boucher (bouton « Espace boucher », code par défaut : **1234**)
- **Stock du jour** : ajouter / modifier / supprimer des pièces, ajuster le stock en un clic (+/−, bouton « Épuisé »)
- **Réservations** : liste avec nom, téléphone (cliquable), date de retrait ; marquer « Retirée » ou « Annuler » (le stock est remis automatiquement)
- Changer le code d'accès depuis l'app

## À savoir
- Les données sont stockées dans le navigateur (localStorage) : parfait pour une tablette au comptoir ou une démo. Pour partager le stock en temps réel entre les téléphones des clients et celui du boucher, il faudra brancher un petit backend (je peux le faire sur demande).
- Pensez à changer le code **1234** dès la première utilisation.
