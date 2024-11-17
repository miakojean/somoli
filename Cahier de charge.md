# Cahier des charges : Application Web Somoli


## 1. Contexte et Objectifs
Somoli est une plateforme dédiée à la location de résidence pour de courts sejours en Côte d’Ivoire. Elle vise à connecter des hôtes proposant des logements et des utilisateurs cherchant des hébergements, en mettant l’accent sur :

- Une expérience utilisateur fluide et intuitive.
- Une visibilité des logements locaux avec des caractéristiques culturelles uniques.
- La sécurité des transactions et la fiabilité des hôtes.

## 2. Fonctionnalités Principales

### 2.1 Pour les utilisateurs (locataires)

Inscription et connexion :

- Possibilité de s’inscrire via email, numéro de téléphone ou réseaux sociaux.
- Gestion des mots de passe oubliés.

Recherche de logements :

- Filtres avancés (prix, localisation, équipements, type de logement).
- Affichage des résultats sur une carte interactive.
- Tri par pertinence, prix ou évaluations.

Réservation :

- Système de calendrier pour vérifier la disponibilité.
- Paiement en ligne sécurisé (intégration de solutions locales comme Orange Money et MTN Mobile Money).
- Notifications (email/SMS) pour confirmer les réservations.

Gestion du profil :

- Historique des réservations.
- Possibilité de laisser des avis et notes sur les hôtes.

### 2.2 Pour les hôtes

Inscription et connexion :

- Création de profils professionnels ou particuliers.
- Vérification de l’identité (pièce d’identité, adresse).

Gestion des logements :

- Ajout de logements avec description, photos, prix, et disponibilité.
- Tableau de bord pour suivre les réservations et revenus.

Communication avec les locataires :

- Messagerie intégrée pour répondre aux questions.
- Notifications en cas de nouvelles demandes ou réservations.

### 2.3 Administration (Back-office)
- Gestion des utilisateurs (locataires et hôtes).
- Modération des annonces (validation ou suppression des contenus).
- Gestion des paiements et remboursements.
- Accès aux statistiques d’utilisation de la plateforme (réservations, revenus, - etc.).

## 3. Conception et Design

### 3.1 Expérience Utilisateur (UX/UI)
- Interface moderne et intuitive adaptée aux standards actuels.
- Site responsive et optimisé pour les mobiles.
- Utilisation de couleurs évoquant la culture ivoirienne.

### 3.2 Pages principales
- Page d’accueil : présentation du concept et moteur de recherche.
- Page des résultats : liste des logements et carte interactive.
- Fiche logement : détails du logement, photos, calendrier et avis.
- Dashboard utilisateur (hôtes et locataires).

## 4. Technologies et Outils
- Frontend : Vue.js (pour une interface interactive et rapide).
- Backend : Django (framework robuste pour gérer la logique métier).
- Base de données : PostgreSQL ou MySQL.
- Paiements : Intégration de Stripe et passerelles locales (Orange Money, MTN - Mobile Money).
- Hébergement : AWS ou services cloud locaux pour des performances optimales.
- SEO : Optimisation pour les moteurs de recherche (Google).

## 5. Sécurité
- Chiffrement des données utilisateurs (certificat SSL).
- Protection contre les attaques courantes (XSS, CSRF).
- Vérification des identités pour garantir la fiabilité des utilisateurs.

## 6. Planning Prévisionnel (A revoir)
| Phase   | Description   | Durée estimée  |
|-------------|-------------|-------------|
| Analyse des besoins | Collecte des besoins et ajustements | 2 semaines |
| Conception | Wireframes et maquettes | 3 semaines |
| Développement Frontend | Codage de l'interface utilisateur | 6 semaines |
| Développement Backend | Mise en place des fonctionnalités côté serveur | 6 semaines |
| Test | Vérification et corrections | 3 semaines |
| Lancement | Mise en ligne et promotion | 1 semaines |

## 7. Budget Prévisionnel 
- Développement technique : 
- Hébergement et maintenance annuelle : 
- Marketing et communication : 

## 8. Équipe Projet
- Chef de projet.
- Développeur Frontend (spécialiste Vue.js).
- Développeur Backend (spécialiste Django).
- Designer UI/UX.
- Expert SEO et marketing digital.

## 9. Évolutions Futures
- Application mobile native (iOS et Android).
- Ajout de fonctionnalités comme :
- Réservation de services locaux (guides touristiques, transports).
- Offres promotionnelles pour les périodes creuses.
