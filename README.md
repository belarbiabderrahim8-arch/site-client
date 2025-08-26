# Site de Commandes - [site-client]

Ce dépôt contient :
- **index.html** — page publique où les clients peuvent passer des commandes via un formulaire.
- **tableau.html** — tableau sécurisé des commandes (protected by JavaScript password check).

##  Comment ça marche ?
1. Le client remplit le formulaire sur **index.html**, les commandes sont envoyées directement par email via **Formspree**.
2. Tu peux ensuite accéder à **tableau.html**, entrer le mot de passe administrateur, et visualiser toutes les commandes enregistrées dans `localStorage`.

##  Lien du site en ligne
Le site est hébergé sur GitHub Pages :  
`https://<ton-nom-utilisateur>.github.io/<nom-du-depot>/`

##  Technologies utilisées
- HTML / Tailwind CSS pour le design
- JavaScript pour la gestion du formulaire & le mot de passe
- Formspree pour la réception des commandes par email
