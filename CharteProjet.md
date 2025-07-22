# 📄 Project Charter – Développement de la Plateforme “AgriSmart”

## 📌 1. Titre du projet

**Développement de la plateforme “AgriSmart” – Application Web & Mobile pour la gestion intelligente des coopératives agricoles.**

---

## 🎯 2. Objectif du projet

Créer une plateforme numérique permettant aux coopératives agricoles de :

* Gérer leurs membres, stocks, ventes, dépenses et récoltes.
* Offrir une interface mobile aux producteurs pour consulter leur solde, livrer et vendre.
* Fournir un tableau de bord analytique aux gestionnaires.

---

## 🧱 3. Contexte et justification

Dans un contexte de digitalisation du secteur agricole en Afrique de l’Ouest, les coopératives manquent d’outils modernes.
La plateforme “AgriSmart” vise à :

* Réduire les pertes dues à une mauvaise gestion.
* Offrir plus de transparence et de traçabilité aux membres.
* Favoriser l’accès au financement via une meilleure gestion des données.

---

## 🧑‍🤝‍🧑 4. Parties prenantes (stakeholders)

| Rôle                    | Nom / Structure                  | Contact                                                 |
| ----------------------- | -------------------------------- | ------------------------------------------------------- |
| Commanditaire (Sponsor) | Ministère de l’Agriculture       | [minagri@gouv.ci](mailto:minagri@gouv.ci)               |
| Chef de projet          | Souleymane Sanogo                | [sanogo@agrismart.com](mailto:sanogo@agrismart.com)     |
| Développeur principal   | Yao K. (freelance)               | [yao.dev@protonmail.com](mailto:yao.dev@protonmail.com) |
| Responsable métier      | Coopérative Café-Cacao d’Aboisso | [coop@ccaboisso.org](mailto:coop@ccaboisso.org)         |
| Testeurs utilisateurs   | Membres de coopératives pilotes  |                                                         |

---

## 🧭 5. Périmètre du projet

### ✅ Inclus :

* Développement d’une application web (gestion) + mobile (accès membre).
* Authentification par numéro de coopérative + mot de passe.
* Modules : membres, stocks, ventes, paiements, export Excel, rapports.

### ❌ Exclu :

* Paiement mobile (prévu en version 2)
* Gestion RH des salariés de la coopérative
* Intégration avec les banques partenaires

---

## 🕒 6. Échéancier prévisionnel

| Phase                         | Dates clés                |
| ----------------------------- | ------------------------- |
| Lancement projet              | 01 septembre 2025         |
| Spécifications fonctionnelles | 05 – 12 septembre 2025    |
| Sprint 1 (Membres + Stocks)   | 13 – 25 septembre 2025    |
| Sprint 2 (Ventes + Rapports)  | 26 sept – 10 octobre 2025 |
| Recette                       | 11 – 15 octobre 2025      |
| Déploiement initial           | 18 octobre 2025           |

---

## ⚙️ 7. Livrables attendus

* Application Web (interface de gestion)
* Application Mobile (Android) en Flutter
* Documentation utilisateur
* Code source GitHub + CI/CD avec GitHub Actions
* Tableau de bord de suivi (GitHub Projects)

---

## 🧪 8. Critères de succès

* 100% des fonctionnalités validées par les tests.
* Système utilisable par au moins 3 coopératives pilotes.
* Taux d’adoption > 70% au premier mois.
* Aucune panne majeure pendant les 30 premiers jours.

---

## 💰 9. Budget estimatif

| Poste                      | Montant estimé (FCFA) |
| -------------------------- | --------------------- |
| Développement (freelance)  | 2 500 000             |
| Test terrain + formation   | 500 000               |
| Hébergement cloud (6 mois) | 300 000               |
| Communication & support    | 200 000               |
| **Total**                  | **3 500 000 FCFA**    |

---

## 🔐 10. Risques identifiés et mesures

| Risque                              | Impact | Mesure préventive                   |
| ----------------------------------- | ------ | ----------------------------------- |
| Manque de données réelles pour test | Moyen  | Impliquer tôt les coopératives      |
| Retard sur livraison sprint 2       | Fort   | Réduire scope, faire MVP d'abord    |
| Difficultés d’accès Internet        | Moyen  | Prévoir accès hors-ligne localement |

---

## 🛠 11. Outils de travail & suivi

* **Code** : GitHub (repos `agrismart-web` et `agrismart-mobile`)
* **Suivi projet** : GitHub Projects (vues Kanban et timeline)
* **Communication** : WhatsApp + Google Meet
* **Documentation** : Notion + README.md

---

## ✍️ 12. Approbations

| Nom                     | Rôle                   | Statut      |
| ----------------------- | ---------------------- | ----------- |
| Sanogo Souleymane       | Chef de projet         | ✔️ Approuvé |
| Mme Kouadio (Ministère) | Sponsor institutionnel | ✔️ Approuvé |
| K. Yao                  | Développeur principal  | ✔️ Confirmé |

---

## 📎 13. Annexes

* Annexe 1 : Arborescence fonctionnelle (diagramme)
* Annexe 2 : Exemple de base de données (CSV)
* Annexe 3 : Wireframes initiaux (PDF)
* Annexe 4 : Modèle du tableau GitHub Projects

---

