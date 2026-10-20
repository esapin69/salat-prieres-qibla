# Salat — Prières & Qibla

Site personnel de prières en français, indépendant de GHE et de tous les autres projets.

- Horaires des 5 prières avec compte à rebours, méthodes réglables.
- Qibla : direction astronomique et boussole si les capteurs du téléphone et le navigateur sont compatibles.
- Position GPS facultative, données conservées dans le navigateur.
- Notifications expérimentales uniquement lorsque la page est ouverte.

Les horaires sont des estimations astronomiques et peuvent différer de ceux de la mosquée. La boussole doit être testée sur un téléphone en HTTPS. Aucune donnée d'utilisateur n'est envoyée à un serveur.

Ce site statique n'utilise aucune API ni aucun service payant.

Déploiement : GitHub Pages. Activer **Settings → Pages → Build and deployment → Source: GitHub Actions** pour publier avec le workflow fourni.

## Publication

Le site est publié depuis la branche `main` via le workflow GitHub Pages du dépôt Salat.
