# Mamoune Bellatif
Projet TODO 
# Application -> [https://todo.mamounebellatif.xyz](https://todo.mamounebellatif.xyz)

# Fonctionnalités implémentés:
- Toutes les fonctionnalités demandés de base 
- Annuler et refaire une action
- filtres sauvegradés de manière locale
- Gestion de plusieurs utilisateurs
- Gestion de plusieurs listes par utilisateur (comptes google)
- Listes collaboratives (si connexion anonyme)
- Changement du label de liste
- partage de liste sans se connecter (par qr code)
(les liste partagées fonctionnent grâce au routing)
- l'application est PWA et marche si la connexion internet est coupée et peut etre installée sur mobile
- import et export de liste
- listes hebergé sur firestore et affichés en temps réel
- application deployée sur firebase hosting (redirection dns sur un nom de domaine perso)
- Css supplémentaire et Angular Material pour les fonctionnalités en plus

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.2.

# Bug connus et limitations:
- le label de liste bug quand on change de liste
sur mobile
- Annuler ou refaire une action génère des bugs lorsqu'on change de liste