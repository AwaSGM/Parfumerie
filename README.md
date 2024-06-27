#Parfumerie en Ligne Inspirée par Marionnaud



Table des Matières
Introduction
Architecture Front-end
Architecture Back-end
Sécurité Back-end
Sécurité Front-end
Technologies Utilisées
Installation
Contributeurs

Introduction /

Ce projet consiste en la création d'une boutique de parfumerie en ligne inspirée par Marionnaud. Le but est de développer une application web complète, incluant à la fois les parties front-end et back-end, avec un accent particulier sur la sécurité des données et des transactions.

Architecture Front-end
Pages Principales
Page d'accueil (Home)

Bandeau avec images de produits phares
Offres spéciales et promotions
Nouveautés et tendances
Recommandations personnalisées
Page de Catégorie (Category)

Liste des sous-catégories
Filtres pour affiner la recherche
Affichage des produits sous forme de grille ou liste
Page de Détail du Produit (Product Detail)

Image(s) haute résolution du produit
Description détaillée du produit
Options de taille et de volume
Avis des clients
Produits associés
Panier (Cart)

Liste des produits ajoutés au panier
Résumé des prix
Options de modification
Page de Paiement (Checkout)

Formulaire de livraison
Méthodes de paiement
Résumé de la commande
Confirmation de la commande
Page de Connexion / Inscription (Login/Register)

Formulaires de connexion et d'inscription
Options de connexion via les réseaux sociaux
Page de Profil Utilisateur (User Profile)

Informations personnelles
Historique des commandes
Préférences et paramètres
Composants Communs
En-tête (Header)

Logo, barre de recherche, icônes de panier, profil et favoris
Menu de navigation
Pied de page (Footer)

Liens d'informations, réseaux sociaux, newsletter

Design et UX/UI

 A MODIFIER
 
 ////   Palette de couleurs : Blanc, noir, rose poudré, violet élégant, or, argent
Typographie : Playfair Display, Georgia, Open Sans, Roboto
Images haute résolution et graphismes minimalistes mais élégants
Style général minimaliste, luxueux et intuitif
 //// 

 
Architecture Back-end
Structure des Données
Ingrédients

ID, nom, description, origine, quantité stockée, prix unitaire
Formules

ID, nom, ingrédients, quantités
Produits Finis

ID, nom, formule, quantité stockée, prix
Ventes

ID, produit, quantité vendue, date, client, prix total
Clients

ID, nom, adresse, contact

Relations entre les Tables

Ingrédients et Formules : une formule utilise plusieurs ingrédients

Produits Finis et Formules : un produit fini est basé sur une formule

Ventes et Produits Finis : plusieurs ventes peuvent contenir le même produit fini

Ventes et Clients : plusieurs ventes peuvent être réalisées par le même client


Sécurité Back-end

Utiliser des bibliothèques et frameworks fiables pour éviter les vulnérabilités de sécurité connues

Mettre à jour régulièrement les dépendances pour corriger les vulnérabilités de sécurité

Utiliser HTTPS pour chiffrer les données transmises entre le serveur et le client (pas nécessaire pour le moment)

Utiliser des tokens d'authentification sécurisés pour protéger les ressources sensibles

Limiter le nombre de tentatives de connexion pour prévenir les attaques par force brute

Mettre en place la vérification en deux étapes pour renforcer la sécurité des comptes utilisateur

Utiliser des captchas pour prévenir les attaques par robot

Utiliser des en-têtes de sécurité tels que Content Security Policy (CSP) et Strict-Transport-Security (HSTS)

Utiliser des paramètres de requête préparés pour éviter les attaques par injection SQL (non nécessaire si PostgreSQL est utilisé)

Utiliser des bibliothèques de validation de schéma pour valider les données d'entrée et de sortie

Utiliser des bibliothèques de journalisation pour enregistrer les activités du serveur et détecter les anomalies

Utiliser un pare-feu pour limiter l'accès au serveur et aux ressources sensibles

Effectuer des tests de sécurité réguliers pour détecter les vulnérabilités et les failles de sécurité

Sécurité Front-end

Échapper toutes les entrées utilisateur pour éviter les attaques par injection de code malveillant

Utiliser des bibliothèques et frameworks fiables pour éviter les vulnérabilités de sécurité connues

Mettre à jour régulièrement les dépendances pour corriger les vulnérabilités de sécurité

Utiliser HTTPS pour chiffrer les données transmises entre le serveur et le client (pas nécessaire pour le moment)

Utiliser des tokens d'authentification sécurisés pour protéger les ressources sensibles

Limiter le nombre de tentatives de connexion pour prévenir les attaques par force brute

Mettre en place la vérification en deux étapes pour renforcer la sécurité des comptes utilisateur

Utiliser des captchas pour prévenir les attaques par robot

Utiliser des en-têtes de sécurité tels que Content Security Policy (CSP) et Strict-Transport-Security (HSTS)

Effectuer des tests de sécurité réguliers pour détecter les vulnérabilités et les failles de sécurité


NB : Utiliser bcrypt pour hacher les mots de passe


Technologies Utilisées

Front-end : HTML, CSS, JavaScript, frameworks front-end react

Back-end : Node.js,, PostgreSQL

Sécurité : bcrypt pour le hachage des mots de passe, JWT pour l'authentification, Helmet.js pour les en-têtes de sécurité


COLLABORATION :
ADILE EVA AWA
