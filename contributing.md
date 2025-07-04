# 📄 CONTRIBUTING.md – PassBi-BackOffice-V2

Bienvenue sur **PassBi-BackOffice-V2**, la plateforme de billettique digitale multi-opérateurs, mobile-first et intermodale.  
Merci de contribuer à la qualité et la scalabilité du projet 🚀

---

## ✅ 1️⃣ Workflow Git

| Branche      | Usage                                          |
| ------------ | ---------------------------------------------- |
| `main`       | Version stable en production.                  |
| `staging`    | Intégration features validées (staging).       |
| `feature/*`  | Nouvelle fonctionnalité.                       |
| `hotfix/*`   | Correctif urgent en production.                |

➡️ **Règle** :  
- Jamais de commit direct sur `main` ou `develop`.  
- **Une feature = une branche = une PR.**

---

## ✅ 2️⃣ Pull Requests (PR)

✔ **Checklist PR :**
- Liée à une issue : `Fixes #123`.
- Commits respectent [Conventional Commits](https://www.conventionalcommits.org).
- Tests unitaires & E2E passent (`npm test`).
- Linter OK (`npm run lint`).
- Fichiers Swagger/OpenAPI mis à jour si API modifiée.
- Scripts de migration DB versionnés si applicable.
- Préfère **Squash & Merge** pour garder un historique propre.
- Supprime la branche après merge.

---

## ✅ 3️⃣ Conventions Commits

| Type         | Usage                                        |
| ------------ | -------------------------------------------- |
| **feat:**    | Nouvelle fonctionnalité                      |
| **fix:**     | Correction de bug                            |
| **docs:**    | Changement de documentation                  |
| **style:**   | Formatage/code style, sans logique modifiée  |
| **refactor:**| Refactoring structure sans ajout de feature  |
| **test:**    | Ajout/modif tests unitaires/E2E              |
| **chore:**   | Maintenance, upgrade dépendances             |
| **ci:**      | Modifications CI/CD                          |

**Exemples :**
```
feat: add batch sync for offline mode
fix: prevent duplicate validation in Control module
docs: update API Gateway flow in README
```

---

## ✅ 4️⃣ Sécurité & Secrets

🚫 **Jamais de secrets, tokens ou clés API** dans le code versionné !  
✅ Utilisez `.env` et ajoutez bien `.env` à `.gitignore`.  
✅ Vérifiez les secrets avec un scanner avant push (GitGuardian, TruffleHog).

---

## ✅ 6️⃣ Bonnes pratiques Git

✔ Toujours `git pull --rebase` avant push pour éviter les conflits.  
✔ Liez chaque PR à une **Issue** pour la traçabilité.  
✔ Déployez en **staging** automatiquement après merge sur `sandbox`.  
✔ Activez la **protection des branches** `main` et `sandbox`.

---

## ✅ 7️⃣ Déploiement CI/CD

- Pipeline GitHub Actions pour lint, test, build.
- Déploiement staging sur merge `staging`.
- Production stable sur `main`.

---

## ✅ 8️⃣ Besoin d’aide ?

Pour toute question, ping ton **Tech Lead** ou le **CTO**.  
Merci de contribuer à un code propre, sécurisé et scalable pour PassBi 🚍🚏

---

## 🏆 Merci pour ta contribution !  
**L’équipe PassBi**

