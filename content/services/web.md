---
title: 'Conso-Web'
date: 2018-11-28T15:15:26+10:00
icon: 'services/service-icon-3.png'
featured: true
draft: false
heroHeading: 'Conso-Web'
heroSubHeading: 'Améliorons la tracabilité du produit.'
heroBackground: 'services/service1.jpg'
---

L'application web-score est la plateforme de mise en relation entre les producteurs et les vendeurs.

Elle propose les services essentiels à la mise en place du conso-score, à savoir :

- \- un service d'authentification pour les producteurs et les vendeurs
- \- un service d'ajout de produit vendu pour le producteur

- \- le service permettant aux vendeurs de consulter sa liste de producteurs partenaires ainsi que les produits de chacun d'entre eux afin de calculer de façon précise le conso-score de chaque produit ainsi que la taxe associée à ces derniers.

Ces calculs prennent en compte le transport ainsi que la production afin de bien rendre compte de l'impact environnemental des produits.

## Composition du projet

Le projet comporte:

- \- un site "vitrine" présentant notre projet et ses limites
- \- une application web "conso-Web" mettant en relation les producteurs et les vendeurs afin de déclarer les produits et calculer leur taxe
- \- une application mobile "conso-scan" qui permet de scanner les produits afin de connaitre leur score en tant que consommateur

Voici un schéma de l'architecture:

![schema_architecture](/services/projet-intensif-archi-logiciel.png)

Nos applications front end communique avec notre backend pour l'échange de données. Le service "Conso Auth" est notre service d'authentification, il permet de connecter le vendeur ou le producteur au système. Le service "Conso back office" réalise la logique métier de notre système, c'est-à-dire l'insertion de produits et le calcul des scores.

## Technologies utilisées :

- \- **application web**: React, Typescript, Nodejs, Bootstrap
- \- **services backend**: Flask, Python
- \- **base de données**: Postgresql
- \- **outils**: Docker

## Les Github

Tout notre code est disponible en open source sur les répertoires suivants:

- \- [Conso Web](https://github.com/FloRichard/conso-score-web-app)
- \- [Conso Back Office](https://github.com/FloRichard/conso-score-back-office)
- \- [Conso User Manager](https://github.com/FloRichard/conso-score-user-manager)
- \- [Conso Scan](https://github.com/FloRichard/conso-score-mobile-app)
- \- [Base de donnée](https://github.com/FloRichard/conso-score-bdd)
- \- [Site Vitrne](https://github.com/FloRichard/conso-score-web-site)
