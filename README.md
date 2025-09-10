# SpaceHub

SpaceHub est une entreprise spécialisée dans la location d'espaces pour des événements, des réunions et des activités diverses. Notre mission est de fournir des espaces flexibles et adaptés aux besoins de nos clients. Nous ciblons principalement les professionnels et les organisateurs d'événements.

## Fonctionnalités de l'application

### Gestion des utilisateurs
- **Inscription/Connexion** : Système d'authentification complet
- **Profils utilisateurs** : Gestion des informations personnelles et préférences
- **Rôles** : Utilisateurs (entreprises) et administrateurs

### Catalogue des lieux (venues)
- **Recherche et filtres** : Par localisation, capacité, équipements, prix
- **Fiches détaillées** : Photos, descriptions, équipements, tarifs
- **Disponibilités** : Calendrier en temps réel
- **Avis et notes** : Système de commentaires clients

### Système de réservation
- **Réservation en ligne** : Interface intuitive avec sélection de dates/heures
- **Confirmation automatique** : Emails de confirmation et rappels
- **Gestion des annulations** : Politique d'annulation flexible

### Gestion pour les propriétaires
- **Dashboard propriétaire** : Vue d'ensemble des réservations et lieux
- **Gestion des lieux** : Ajout, modification, suppression de lieux
- **Calendrier** : Blocage de dates, gestion des disponibilités

### Administration
- **Panel d'administration** : Gestion globale de la plateforme
- **Statistiques** : Tableaux de bord et rapports

### Fonctionnalités transversales
- **Notifications** : Alerts email et push
- **Géolocalisation** : Carte interactive des lieux
- **Export/Import** : Données de réservation
- **API** : Interface pour intégrations tierces

## Charte graphique

Logo du site :

![Logo SpaceHub](/assets/images/logo.svg)

Favicon :

![Favicon SpaceHub](/assets/images/favicon.svg)

### Palette de couleurs

- Couleur principale : #2563eb
- Gris foncé : #1f2937
- Gris clair : #6b7280

Variations de la couleur principale :
- Couleur principale claire : #3b82f6
- Couleur principale très clair : #dbeafe
- Couleur principale foncée : #1d4ed8

Variations de gris :
- Gris moyen : #4b5563
- Fond gris : #f9fafb
- Blanc : #ffffff

Couleurs accent :
- Vert (success) : #10b981
- Rouge (error) : #ef4444
- Orange (warning) : #f59e0b
- Violet (info) : #8b5cf6

Couleurs neutres :
- Gris chaud : #78716c
- Blanc cassé : #fafaf9

### Typographie

- Police principale : 'Inter', sans-serif
- Tailles de police :
  - H1 : 3rem (48px)
  - H2 : 2.25rem (36px)
  - H3 : 1.5rem (24px)
  - H4 : 1.25rem (20px)
  - Body : 1rem (16px)
  - Small : 0.875rem (14px)

## Structure du projet

Le template HTML/CSS comprendra :

### Pages principales
- **index.html** : Page d'accueil avec hero section, présentation des services
- **venues.html** : Catalogue des lieux disponibles
- **venue-detail.html** : Page de détail d'un lieu
- **contact.html** : Formulaire de contact et informations
- **login.html** : Page de connexion
- **register.html** : Page d'inscription
- **dashboard.html** : Tableau de bord des utilisateurs avec liste des lieux et réservations


### Composants réutilisables
- **Header/Navigation** : Menu principal avec logo et navigation
- **Footer** : Liens utiles et informations de contact
- **Cards** : Pour présenter les lieux et services
- **Boutons** : Différents styles selon le contexte
- **Formulaires** : Champs de saisie stylisés
- **Modales** : Pour les actions rapides

### Styles CSS
- **styles.css** : Fichier CSS unique contenant :
  - Reset CSS pour normaliser les styles
  - Variables CSS pour les couleurs et typographie
  - Styles des composants réutilisables
  - Media queries pour le responsive
Pour des raisons de simplicité, ce fichier ne devra pas dépasser les 300 lignes.

## Fonctionnalités du template

### Design system
- Système de grille responsive (mobile-first)
- Composants modulaires et réutilisables
- États d'interaction (hover, focus, active)
- Animations et transitions fluides

### Accessibilité
- Structure HTML sémantique
- Contrastes respectant les standards WCAG
- Navigation au clavier
- Textes alternatifs pour les images

### Performance
- Code CSS optimisé et minifié
- Images optimisées
- Chargement des polices optimisé
- Structure HTML légère

## Installation et utilisation

1. Cloner le repository
2. Ouvrir `index.html` dans un navigateur

## Compatibilité

- Navigateurs modernes (Chrome, Firefox, Safari, Edge)
- Responsive : mobile, tablette, desktop
