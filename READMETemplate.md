
# 🌾 AgriSmart – Plateforme de gestion intelligente des coopératives agricoles

## 📌 Description

**AgriSmart** est une application **Web + Mobile** open source conçue pour les coopératives agricoles d’Afrique de l’Ouest. Elle permet aux gestionnaires de suivre les membres, les récoltes, les ventes, les paiements et d’obtenir des **rapports détaillés** pour une meilleure transparence et efficacité.

Version actuelle : **v1.0.0**  
Statut : ✅ En développement actif  
Licence : MIT

---

## 🧭 Table des matières

- [Fonctionnalités](#-fonctionnalités)
- [Capture d'écran](#-capture-décran)
- [Technologies utilisées](#-technologies-utilisées)
- [Installation](#-installation)
- [Utilisation](#-utilisation)
- [API](#-api)
- [Roadmap](#-roadmap)
- [Contribuer](#-contribuer)
- [Support & Contact](#-support--contact)
- [Licence](#-licence)

---

## ✅ Fonctionnalités

- [x] Gestion des membres (adhésion, solde, historique)
- [x] Saisie et suivi des récoltes
- [x] Enregistrement des ventes et dépenses
- [x] Tableau de bord analytique
- [x] Export Excel et PDF
- [x] Interface mobile simple pour les producteurs
- [ ] Intégration paiements mobile (à venir v2)

---

## 🖼 Capture d’écran

![Dashboard AgriSmart](docs/screenshots/dashboard.png)

---

## 🛠 Technologies utilisées

| Frontend Web | Backend API | Mobile App | Base de données | Autres |
|--------------|-------------|------------|------------------|--------|
| React.js     | Node.js + Express | Flutter     | PostgreSQL         | GitHub Actions, Docker, JWT Auth |

---

## 🚀 Installation

### Prérequis

- Node.js v18+
- PostgreSQL
- Flutter 3.x (pour mobile)
- Git / Docker (optionnel)

### 1. Cloner le projet

```bash
git clone https://github.com/votre-org/agrismart.git
cd agrismart
````

### 2. Installation backend

```bash
cd backend
npm install
cp .env.example .env
# Modifier les variables d’environnement
npm run dev
```

### 3. Installation frontend

```bash
cd frontend
npm install
npm run dev
```

### 4. Lancer la version mobile

```bash
cd mobile
flutter pub get
flutter run
```

---

## 💻 Utilisation

* Se connecter avec les identifiants fournis par l’administrateur.
* Naviguer entre les modules : Membres, Récoltes, Ventes, etc.
* Utiliser le tableau de bord pour visualiser les données.

> Astuce : L’appli est responsive et fonctionne aussi sur tablette.

---

## 📡 API

La documentation complète de l’API est disponible via Swagger à l’adresse :
`http://localhost:5000/api/docs`

Quelques endpoints :

```
GET    /api/members
POST   /api/harvests
PUT    /api/sales/:id
DELETE /api/expenses/:id
```

---

## 🛣 Roadmap (extrait)

| Version | Fonctionnalité                     | Statut           |
| ------- | ---------------------------------- | ---------------- |
| 1.0.0   | Version MVP Web + Mobile           | ✅ Terminé        |
| 1.1.0   | Authentification SMS               | 🛠 En cours      |
| 2.0.0   | Paiement mobile Orange Money / MTN | 🕒 Prévu Q4 2025 |

---

## 🤝 Contribuer

### Étapes de contribution

1. Forker le projet
2. Créer une branche (`git checkout -b feature/nouvelle-fonction`)
3. Commiter vos modifications (`git commit -am 'Ajout de ...'`)
4. Pousser (`git push origin feature/...`)
5. Ouvrir une pull request

### Bonnes pratiques

* Respecter les conventions de nommage
* Écrire des tests pour chaque nouvelle fonctionnalité
* Documenter toute modification majeure

---

## 📬 Support & Contact

* 📧 [contact@agrismart.org](mailto:contact@agrismart.org)
* 🌐 [Site Web de la coopérative](https://agrismart.org)
* 🐛 Pour signaler un bug, ouvrez une [issue GitHub](https://github.com/votre-org/agrismart/issues)

---

## 📄 Licence

Ce projet est sous licence **MIT**. Voir le fichier [LICENSE](LICENSE) pour plus d’informations.

---

## 🙏 Remerciements

Merci à :

* Tous les contributeurs open source
* Les coopératives partenaires pour les tests terrain
* L’équipe du Ministère pour son soutien technique



---

