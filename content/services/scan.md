---
title: 'Conso-Scan'
date: 2018-11-28T15:15:34+10:00
icon: 'services/service-icon-4.png'
featured: true
draft: false
heroHeading: 'Conso-Scan'
heroSubHeading: 'Vous voulez connaître la consommation énergétique de votre produit ? Découvrez Conso-Scan.'
heroBackground: 'services/service2.jpg'
---

Cette application permet aux consommateurs de visualiser la fiche  descriptive d'un produit (nom, conso-score, taxe et bilan carbone  détaillé) en scannant son code-barre.

## Informer le consommateur

L'utilisateur scanne le code barre de l'article, ensuite la fiche du produit est directement affichée sur le téléphone.

Le but de l'application est de permettre à l'utilisateur de comprendre pourquoi le produit a ce conso-score et aussi de comprendre pourquoi on taxe le produit.

## Technique

L'application est développée en Java Android.

Elle utilise la librairie zxing pour le scanneur de code barre et retrofit2 pour la communication avec le back office.

L'application communique avec le backoffice sur le chemin /datas/product/{codebar}/
