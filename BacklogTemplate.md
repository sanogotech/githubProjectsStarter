# 🗂️ Exemple de Backlog de Projet – “AgriSmart” (Plateforme Web + Mobile)

### ⚙️ Contexte :

Projet de 3 sprints (durée 2 semaines par sprint) pour développer un **MVP** de gestion de coopératives agricoles.

---

## 📋 Format du backlog

| ID  | Tâche / User Story                                | Sprint   | Priorité | Estimation | Type        | Équipe      | Statut   |
| --- | ------------------------------------------------- | -------- | -------- | ---------- | ----------- | ----------- | -------- |
| #1  | \[US01] En tant qu’admin, je peux créer un membre | Sprint 1 | Haute    | 1 jour     | Feature     | Backend     | À faire  |
| #2  | \[US02] Interface liste des membres               | Sprint 1 | Haute    | 2 jours    | UI/Frontend | Frontend    | En cours |
| #3  | \[US03] Authentification JWT                      | Sprint 1 | Haute    | 1 jour     | Sécurité    | Backend     | Terminé  |
| #4  | \[US04] Dashboard statistique                     | Sprint 2 | Moyenne  | 3 jours    | Feature     | Fullstack   | À faire  |
| #5  | \[US05] Ajout récolte et édition                  | Sprint 2 | Haute    | 2 jours    | Feature     | Backend     | À faire  |
| #6  | \[US06] Interface mobile membre : voir solde      | Sprint 2 | Haute    | 2 jours    | Mobile      | Mobile Dev  | À faire  |
| #7  | \[US07] Export des ventes en Excel                | Sprint 3 | Moyenne  | 1 jour     | Outil       | Backend     | À faire  |
| #8  | \[BUG01] Solde incorrect si suppression récolte   | Sprint 3 | Haute    | 1 jour     | Bugfix      | Backend     | À faire  |
| #9  | \[US08] Interface de login mobile                 | Sprint 1 | Moyenne  | 1 jour     | Mobile      | Mobile Dev  | En cours |
| #10 | \[US09] Déploiement CI/CD via GitHub Actions      | Sprint 3 | Moyenne  | 2 jours    | DevOps      | DevOps Team | À faire  |

---

## 📆 Planification par sprint (extrait)

### 🏁 Sprint 1 (Semaine 1-2)

* Mise en place de la base (auth, membres)
* Interfaces principales (liste, login)
* Durée cible : **10 jours-hommes**

**Tâches :** #1, #2, #3, #9

---

### 🏁 Sprint 2 (Semaine 3-4)

* Fonctionnalités métiers (récoltes, solde)
* Dashboard analytique
* Début app mobile

**Tâches :** #4, #5, #6

---

### 🏁 Sprint 3 (Semaine 5-6)

* Corrections et outils (export, déploiement)
* Optimisation
* Tests utilisateurs

**Tâches :** #7, #8, #10

---

# ✅ Bonnes pratiques de remplissage d’un backlog dans GitHub Projects

## 🔧 Structure recommandée des champs personnalisés :

| Champ           | Type                                                         | Pourquoi ?                                    |
| --------------- | ------------------------------------------------------------ | --------------------------------------------- |
| **Sprint**      | Menu déroulant                                               | Pour grouper les tâches par période           |
| **Priorité**    | Menu (Haute, Moyenne, Basse)                                 | Pour décider quoi faire d’abord               |
| **Estimation**  | Numérique ou texte                                           | Pour équilibrer la charge                     |
| **Type**        | Menu (Feature, Bugfix, UI, Sécurité, etc.)                   | Pour filtrer                                  |
| **Statut**      | Colonnes (Backlog → À faire → En cours → En revue → Terminé) | Suivi agile                                   |
| **Responsable** | Assignee                                                     | Pour éviter les tâches orphelines             |
| **Tags/Labels** | Labels GitHub                                                | Pour ajouter des dimensions (Mobile, Urgent…) |

---

# 🏆 Top 30 des Bonnes Pratiques dans GitHub Projects

## 🔍 Structuration

1. Utiliser le **nouveau GitHub Projects** (v2).
2. Créer des **vues multiples** : par sprint, par priorité, par équipe.
3. Créer des **champs personnalisés** adaptés à ton contexte.
4. Relier tous les dépôts nécessaires via **“Link to Project”**.
5. Utiliser des **nomenclatures claires** dans les titres (`[US01]`, `[BUG02]`...).

## 🔄 Planification Agile

6. Planifier avec des **sprints (ou phases)** clairs dans un champ.
7. Limiter le nombre de tâches par sprint (respecter la vélocité).
8. Préciser les **estimations** (jours, points, etc.).
9. Organiser les tâches par **valeur métier** et complexité.
10. Prioriser avec les **labels ou champs dédiés**.

## 🧠 Gestion des tâches

11. Décomposer les tâches complexes en sous-tâches.
12. Lier chaque **PR à une issue** (Fixes #id).
13. Attribuer chaque tâche à un **membre responsable**.
14. Utiliser des **checklists** dans les descriptions.
15. Documenter les dépendances et blocs.

## 👥 Collaboration

16. Mettre à jour les statuts lors des daily meetings.
17. Mentionner les membres dans les commentaires pour suivi.
18. Partager les vues du projet lors des réunions de pilotage.
19. Créer des **modèles d’issue personnalisés** pour homogénéité.
20. Ne pas tout suivre : filtrer avec des **vues dynamiques**.

## ⚙️ Automatisation

21. Utiliser **GitHub Actions** pour mettre à jour le projet.
22. Activer les **règles automatiques** (ex : “close when merged”).
23. Lier les **commits aux tâches** avec `Fixes #` ou `Closes #`.

## 📊 Suivi et amélioration

24. Créer une **vue “Terminé ce sprint”**.
25. Exporter les tâches en CSV si besoin de reporting.
26. Suivre les taux d’achèvement vs estimation.
27. Réaliser une **rétrospective** à chaque fin de sprint.
28. Archiver les projets terminés pour les garder propres.
29. Réutiliser les **modèles de projet** pour les nouveaux.
30. Capitaliser les leçons apprises dans un wiki ou fichier rétrospective.

---


