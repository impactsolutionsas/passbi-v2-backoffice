# 🚍 PassBi – Plateforme de Billetterie Numérique Multi-opérateurs

Bienvenue sur **PassBi**, une **Progressive Web App (PWA)** moderne conçue pour gérer la billetterie numérique des opérateurs de transport urbain et interurbain.  
PassBi centralise la gestion des tickets, opérateurs, lignes, transactions et feedbacks utilisateurs, avec une expérience fluide, temps réel et responsive.

---

## 📌 Fonctionnalités principales

✅ **Gestion des Opérateurs**
- Enregistrement des opérateurs urbains/interurbains
- Paramètres spécifiques par opérateur (commissions, lignes, statuts)
- Dashboard opérateur dédié

✅ **Gestion des Lignes**
- Création de lignes avec tarifs, zones et stations BRT associées

✅ **Système de Tickets**
- Génération et validation de QR Codes
- Statuts : validé, expiré, utilisé
- Suivi des validations en temps réel
- Notifications lors de l’insertion de nouveaux tickets

✅ **Feedback Utilisateur**
- Collecte et gestion des retours utilisateurs

✅ **Gestion des Utilisateurs**
- Multi-rôles : administrateur, opérateur
- Interfaces personnalisées selon les permissions

✅ **Rapports & Analyses**
- Suivi des ventes et statistiques par opérateur, ligne ou période

---

## 🎨 Charte graphique

- 🎨 **Couleurs principales :**  
  - Vert turquoise `#00a99d` (principal)  
  - Gris foncé `#4d5c61` (secondaire)  
  - Jaune vif pour accentuation  
- 🌓 **Mode sombre** soigneusement conçu pour le confort visuel
- 🔠 **Typographie :** Sans-serif lisible, titres en gras, hiérarchie claire
- 🧩 **Composants UI :**  
  - Cartes, tableaux alternés, boutons hiérarchisés
  - Badges de statut colorés
  - Formulaires clairs avec validation intuitive

---

## 🧩 Navigation

- Menu latéral rétractable avec navigation hiérarchique
- Permissions dynamiques selon rôle
- État actif mis en évidence
- Responsive sur desktop & mobile

---

## ⚙️ Architecture technique

- **Frontend :** React + TypeScript  
  - Tailwind CSS + shadcn/ui pour composants
  - Mode PWA : offline-ready, manifest, installation mobile

- **Backend :** Supabase  
  - PostgreSQL sécurisé avec RLS (Row Level Security)
  - Authentification et permissions fines
  - Subscriptions temps réel pour tickets & notifications

---

## 🚀 Lancement du projet

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/ton-org/passbi-pwa.git
   cd passbi-pwa
2. **Installer les dépendances :**
  ```bash
   npm install
  
3. **Configurer les variables d’environnement :**
   ```bash
   .env.local avec les clés Supabase : SUPABASE_URL, SUPABASE_ANON_KEY

Démarrer en développement :

Copier
Modifier
npm run dev
Accéder à l’application :
http://localhost:3000

bash

🤝 Contribuer
```bash
Forkez ce repo
Créez votre branche (git checkout -b feature/ma-feature)
Commitez vos changements (git commit -m 'feat: ma nouvelle fonctionnalité')
Poussez la branche (git push origin feature/ma-feature)
Ouvrez une Pull Request !
bash
📄 Licence
Projet sous licence MIT.

Impact Solution SAS © 2025
Plateforme PassBi – Pour une mobilité plus fluide et inclusive. 🌍🚍
