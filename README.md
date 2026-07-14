# YANGO Driver Tracker - Cameroun

Une application web mobile simple et hors ligne conçue pour les chauffeurs YANGO au Cameroun afin de suivre leurs revenus et dépenses quotidiens.

## Fonctionnalités

- **Deux types de revenus** : Commandes YANGO Direct + Commandes personnelles
- **Suivi des dépenses** avec catégories courantes (Carburant, Entretien, Nourriture, Péages, Autres)
- **Rapports quotidiens, hebdomadaires et sur 14 jours**
- **Horodatage automatique** sur chaque transaction
- **Connexion sécurisée** avec nom d'utilisateur + mot de passe
- **Changement de mot de passe**
- **Export / Import de sauvegarde** (JSON)
- **Progressive Web App (PWA)** – Installable sur Android & iOS
- **100% hors ligne** – Données stockées localement sur l'appareil
- **Support multi-utilisateurs** – Chaque chauffeur a ses propres données privées

## Stack Technique

- HTML5 + Tailwind CSS
- JavaScript Vanilla
- LocalStorage (persistance des données)
- Service Worker (support PWA)

## Démarrage

### Exécution locale

1. Téléchargez `yango-driver-tracker-final.html`
2. Renommez-le en `index.html`
3. Ouvrez le fichier dans un navigateur moderne

### Déploiement en production (Recommandé)

**Option 1 : Netlify (Le plus simple)**
1. Rendez-vous sur [netlify.com](https://netlify.com)
2. Glissez-déposez le fichier `index.html`
3. Votre application sera en ligne instantanément

**Option 2 : GitHub Pages**
1. Créez un nouveau dépôt
2. Téléversez `index.html`
3. Activez GitHub Pages dans les paramètres du dépôt

## Structure du projet

```
yango-driver-tracker-final.html   # Application principale
README.md                         # Documentation anglaise
README_FR.md                      # Documentation française
USER_GUIDE.md                     # Guide utilisateur anglais
USER_GUIDE_FR.md                  # Guide utilisateur français
```

## Sécurité et Confidentialité

- Toutes les données sont stockées **uniquement sur l'appareil de l'utilisateur**
- Aucune donnée n'est envoyée vers un serveur
- Chaque utilisateur dispose de ses propres données isolées (basées sur le nom d'utilisateur)

## Licence

Utilisation gratuite à des fins personnelles et commerciales.

---

**Développé pour les chauffeurs YANGO au Cameroun**  
Version : 4.0 (Finale) | Date : Juillet 2026