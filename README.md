# Verisav - Plateforme SaaS de Gestion SAV

## Vue d'ensemble

Verisav est une plateforme SaaS innovante qui révolutionne la gestion du service après-vente (SAV) pour les retailers, consommateurs et fabricants. Notre objectif est de digitaliser et d'optimiser l'ensemble du parcours SAV, de l'achat à la maintenance des produits électroniques et électroménagers.

## Architecture du Projet

```
verisav/
├── apps/
│   ├── web/              # Application web Next.js
│   ├── mobile/           # Application iOS Swift
│   └── api/              # Backend API
├── packages/
│   ├── ui/               # Composants UI partagés
│   ├── database/         # Schémas et migrations Supabase
│   └── types/            # Types TypeScript partagés
├── docs/                 # Documentation projet
└── .cursor/              # Configuration Cursor
```

## Stack Technologique

- **Frontend**: Next.js 14, React 18, TypeScript 5
- **Backend**: Node.js, API REST
- **Base de données**: Supabase (PostgreSQL)
- **Mobile**: Application iOS native (Swift, Xcode)
- **Déploiement**: Vercel
- **Authentification**: Supabase Auth
- **Paiements**: Stripe

## Fonctionnalités Principales

### 🔍 Module Scan & Activation de Garantie
- Scanner le code-barres du produit acheté
- Activation automatique des garanties
- Génération de certificats numériques
- Notifications automatiques

### 📊 Gestion de la Base Installée
- Registre centralisé des équipements
- Historique complet des interventions
- Alertes préventives intelligentes
- Suivi en temps réel

### 👤 Portail Client Self-Service
- Connexion sécurisée
- Déclaration de panne en ligne
- Suivi des demandes SAV
- Accès aux manuels et tutoriels

### 🔧 Gestion des Work Orders
- Création automatique des ordres de travail
- Assignation intelligente aux techniciens
- Suivi du statut en temps réel
- Intégration gestion des pièces

### 📱 Planning et Dispatching
- Calendrier visuel des interventions
- Optimisation automatique des tournées
- Application mobile pour techniciens
- Géolocalisation en temps réel

### 📈 Analytics et Rapports
- KPIs de performance
- Analyse des pannes récurrentes
- Prévision de la charge de travail
- Rapports SLA

## Démarrage Rapide

```bash
# Installation des dépendances
npm install

# Démarrage en mode développement
npm run dev

# Build de production
npm run build
```

## Règles de Développement

- **Commentaires en français uniquement**
- **TypeScript strict mode**
- **Tests en premier pour les fonctionnalités complexes**
- **Pas de fallbacks silencieux**
- **Gestion d'erreurs explicite**

## Licence

Propriétaire - Verisav SAS
# Force redeploy
