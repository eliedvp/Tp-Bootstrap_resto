# Bouche B Resto — site vitrine avec Bootstrap

Exercice réalisé pendant la formation GoMyCode : réaliser la page d'accueil d'un restaurant fictif avec Bootstrap 5.

## Sections de la page

- **Barre de navigation** fixe et repliable sur mobile (Accueil, Menu, À propos, Contact).
- **Section héros** plein écran avec image de fond et accroche.
- **Menu** : plats présentés sous forme de cartes Bootstrap.
- **À propos** du restaurant.
- **Formulaire de contact** (nom, e-mail, message).
- **Pied de page** avec liens vers les réseaux sociaux (Bootstrap Icons).

## Notions travaillées

- Système de grille et classes utilitaires Bootstrap (espacements, couleurs, flexbox)
- Composants Bootstrap : `navbar`, `card`, formulaires
- Mise en page responsive
- Icônes avec Bootstrap Icons

## Stack

HTML5, Bootstrap 5.3 et Bootstrap Icons (chargés par CDN).

## Lancer le projet

Ouvrir `Tp-Bootstrap_resto.html` dans un navigateur (connexion internet nécessaire pour charger Bootstrap depuis le CDN).

Les images du menu et de la section « À propos » utilisent des chemins absolus (`/assets/...`) : pour qu'elles s'affichent, servir le dossier du dépôt à la racine d'un serveur local, par exemple avec l'extension **Live Server** de VS Code ou `python -m http.server 8000`, puis ouvrir http://localhost:8000/Tp-Bootstrap_resto.html.
