# 🐍 Quiz Python - Licence 2

Application web de quiz Python pour évaluer les étudiants de Licence 2 (IAGE et GL) avec système anti-triche intégré.

## ✨ Fonctionnalités

### Pour les étudiants
- 📝 **50 questions** de difficulté progressive (faciles → très difficiles)
- ⏱️ **60 minutes** chronomètre
- 🎯 **Note sur 20** avec calcul automatique
- 🚫 **Système anti-doublon** : impossible de repasser le test
- ⚠️ **Détection de triche** : -2 points par changement d'onglet
- 📊 Résultats détaillés à la fin

### Pour l'enseignant
- 🔐 **Accès sécurisé** (login : mustafa / password : 14051994)
- 📈 **Statistiques complètes** (moyenne, taux de réussite, etc.)
- 🎓 **Filtrage par classe** (L2-IAGE / L2-GL)
- 📥 **Export CSV** de tous les résultats
- 📄 **Rapports individuels** détaillés
- 👁️ **Monitoring de triche** avec historique

## 🚀 Déploiement rapide

### Option 1 : Ouvrir directement les fichiers
1. Double-cliquez sur `index.html` → Quiz étudiants
2. Double-cliquez sur `admin.html` → Tableau de bord admin

### Option 2 : GitHub Pages (recommandé)
1. Créez un dépôt GitHub
2. Uploadez `index.html` et `admin.html`
3. Activez GitHub Pages dans Settings → Pages
4. Partagez le lien aux étudiants

## 📂 Structure

```
quiz-python/
├── index.html    # Application quiz pour étudiants
├── admin.html    # Tableau de bord administrateur
└── README.md     # Ce fichier
```

## 🎓 Classes disponibles

- **L2-IAGE** : Licence 2 - Intelligence Artificielle et Génie Logiciel
- **L2-GL** : Licence 2 - Génie Logiciel

## 📊 Répartition des questions

| Difficulté | Points | Nombre | Total |
|------------|--------|--------|-------|
| Facile | 1 pt | 10 | 10 pts |
| Assez Facile | 1.25 pts | 10 | 12.5 pts |
| Moyen | 1.5 pts | 10 | 15 pts |
| Assez Difficile | 1.75 pts | 10 | 17.5 pts |
| Très Difficile | 2 pts | 10 | 20 pts |

**Total : 75 points → Note finale sur 20**

## 🔐 Sécurité

- ✅ Anti-doublon avec normalisation insensible à la casse
- ✅ Détection de changement d'onglet
- ✅ Détection de perte de focus
- ✅ Enregistrement de tous les avertissements
- ✅ Pénalité automatique de -2 points par tentative

## 🛠️ Technologies utilisées

- React 18
- Tailwind CSS
- SweetAlert2 (notifications)
- LocalStorage (stockage des résultats)

## 📝 Utilisation

### Pour les étudiants
1. Ouvrir le lien du quiz
2. Entrer nom, prénom et classe
3. Lire les consignes attentivement
4. Commencer le test (impossible de le refaire après)
5. Consulter les résultats à la fin

### Pour l'enseignant
1. Ouvrir `admin.html`
2. Se connecter avec les identifiants
3. Consulter les statistiques
4. Filtrer par classe ou statut (admis/échec/triche)
5. Exporter les résultats en CSV

## ⚠️ Important

- Les résultats sont stockés dans le **localStorage** du navigateur
- **Exportez régulièrement** les données en CSV pour sauvegarde
- Les étudiants ne peuvent passer le test **qu'une seule fois**
- Vérifiez la liste des tricheurs dans l'onglet "Avec triche"

## 📧 Support

Pour toute question ou problème, contactez l'enseignant.

## 📄 Licence

© 2025 - Projet éducatif Licence 2

---

**Déployé avec ❤️ pour les étudiants de L2-IAGE et L2-GL**
