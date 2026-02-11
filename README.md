# 📌 Menu Maker – Planification de projet web

Projet OpenClassrooms – Développement

🎯 Contexte du projet

Ce projet s’inscrit dans le cadre de la formation Développeur Web
OpenClassrooms.

L’objectif était de planifier le développement complet d’un site web pour le client
Qwenta (produit "Menu Maker") à partir
de :

- Maquettes fournies
- Spécifications fonctionnelles
- User Stories

⚠️ Aucun développement (codage) n’était demandé. Le travail consistait a preparer la planification,
la methode de suivi, la veille et les specifications techniques.

## Objectifs pedagogiques

- Decouper une fonctionnalite en taches pour preparer le developpement
- Mettre en place une methode de veille technologique
- Presenter la solution technique
- Rediger les specifications techniques d'un projet web a partir de besoins
  fonctionnels
- Suivre le deroulement du projet grace a un outil de gestion de projet

## Contexte du projet

Menu Maker est une application qui permet aux restaurateurs de creer et
personnaliser leurs menus en ligne, avec previsualisation en temps reel,
connexion securisee et diffusion/export (PDF, impression, Instagram).

## Livrables

- Presentation : `SIMON_Fanny_4_presentation_122025.ppsx`
- Specifications techniques : `SIMON_Fanny_1_specifications_techniques_122025.pdf`
- Kanban : `SIMON_Fanny_2_kanban_122025.pdf`
- Veille technologique : `SIMON_Fanny_3_veille_122025.pdf`

## Suivi de projet (Kanban)

Outil : Notion  
Lien : https://feline-pocket-1b9.notion.site/2c4575bd051681b48deacf0ca714e4d2?v=2c4575bd051681cc95de00c92b157cc

## Methode et organisation

- Cadre : Agile / Scrum
- Equipe cible : 1 dev front, 1 dev back, 1 designer, Product Owner (Soufiane)
- Sprints proposes :
  - Sprint 1 : analyse des besoins, structure, fonctionnalites principales
  - Sprint 2 : developpement des fonctionnalites prioritaires (menus)
  - Sprint 3 : diffusion, compte utilisateur, tests fonctionnels
  - Sprint 4 : corrections, optimisations, validation et livraison
- Validations : revue de conception, conformite aux user stories, tests globaux,
  recette finale

## Specifications techniques (synthese)

- Stack principale : MERN (React, Node.js/Express, MongoDB)
- Frontend : React + Sass (SCSS), composants et modales (React-modal)
- Authentification : 100% passwordless via magic link, JWT a duree de vie courte
  et usage unique, envoi par mail (Nodemailer)
- API : REST (CRUD menus), routes securisees, integration Instagram Graph API
- Base de donnees : MongoDB + Mongoose (documents flexibles pour menus et users)
- Hebergement : cloud commercial (Vercel/Render + MongoDB Atlas)
- Accessibilite : bonnes pratiques WCAG (contraste, clavier, lecteurs d'ecran)
- Securite : OWASP, rate limiting, validation requetes, CORS, Helmet, secrets en
  variables d'environnement
- Maintenance : mises a jour dependances, supervision, sauvegardes, evolutions

## Veille technologique

- Outil principal : Feedly (agregateur RSS)
- Axes de veille :
  - Developpement web (source : freeCodeCamp)
  - Framework React (source : React Blog)
- Complement : comparaison d'outils IA (Perplexity, ChatGPT) et tableau de
  sources pour assurer la fiabilite (date, provenance, pertinence).
- Impact : choix techniques, securite, accessibilite, hebergement et scalabilite

## Contenu detaille

Les informations completes sont dans les livrables PDF et la presentation.