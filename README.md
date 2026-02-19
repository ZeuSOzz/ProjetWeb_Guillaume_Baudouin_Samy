# 🎓 Site Vitrine - Département Informatique EFREI

## 📋 Description du projet

Site vitrine du département d'Informatique de l'EFREI Paris, développé dans le cadre du cours XTI205-CYB (Programmation Web).

Ce projet met en œuvre les technologies web fondamentales (HTML5, CSS3, JavaScript) pour créer un site moderne, responsive et interactif présentant le département informatique de l'EFREI.

---

## 👥 Équipe de développement

| Nom | Rôle | Responsabilités |
|-----|------|----------------|
| **Guillaume** | Developer | Page Cours |
| **Baudouin** | Developer | Pages Equipe |
| **Samy** | Developer | Page A propos et accueil |

---

## 🎯 Objectifs pédagogiques

- ✅ Navigation intuitive avec hyperliens
- ✅ Design responsive (media queries, viewport)
- ✅ Manipulation de formulaires et tableaux
- ✅ Fonctionnalités dynamiques en JavaScript
- ✅ Conception de maquette (wireframe)
- ✅ Validation W3C de toutes les pages

---

## 🌐 Structure du site

```
📦 Arborescence (max 2 niveaux)
│
├── 🏠 Niveau 0 : Accueil (index.html)
│
└── 📄 Niveau 1 : Pages principales
    ├── Cours et formations
    ├── Équipe enseignante
    ├── Contact / À propos
    └── [Pages additionnelles]
```

---

## 📁 Organisation des fichiers

```
projet-xti205/
│
├── index.html                 # Page d'accueil
├── pages/
│   ├── cours et formations.html
│   ├── equipe enseignante.html
│   └── a-propos.html
│
├── css/
│   ├── style.css             # Styles principaux
│   └── animations.css        # Animations CSS
│
├── js/
│   ├── script.js             # Script principal
│   └── form-validation.js    # Validation formulaires
│
├── images/
│   ├── logo-efrei.png
│
├── maquette/
│   └── wireframe.pdf         # Maquette du site
│
├── README.md
└── .gitignore
```

---

## 🚀 Fonctionnalités principales

### Pages obligatoires

1. **Page d'accueil** (`index.html`)
   - Présentation du département d'informatique
   - Carrousel d'images
   - Navigation vers les autres pages

2. **Cours et formations** (`cours-formations.html`)
   - Liste des formations proposées
   - Tableau des cours
   - Descriptifs détaillés

3. **Équipe enseignante** (`equipe-enseignante.html`)
   - Présentation des enseignants
   - Photos et biographies
   - Spécialités et contacts

4. **Contact / À propos** (`contact.html`)
   - Formulaire de contact
   - Informations sur l'équipe du projet
   - Présentation du travail réalisé

### Fonctionnalités JavaScript

- 🎨 Menu de navigation interactif
- ✔️ Validation de formulaires
- 🖼️ Carrousel d'images automatique
- 📅 Gestion d'agenda des permanences
- 🔄 Animations et transitions dynamiques

### Design responsive

- 📱 Mobile First
- 💻 Tablette optimisé
- 🖥️ Desktop adapté
- Media queries pour tous les breakpoints

---

## 🛠️ Technologies utilisées

| Technologie | Version | Utilisation |
|------------|---------|-------------|
| HTML5 | - | Structure et contenu |
| CSS3 | - | Styles et animations |
| JavaScript | ES6+ | Interactivité |

⚠️ **Aucun framework ni bibliothèque autorisé** (Respect des consignes XTI205-CYB)

---

## 📐 Charte graphique

### Couleurs principales
```css
--primary-color: #003DA5;      /* Bleu EFREI */
--secondary-color: #F39200;    /* Orange EFREI */
--text-color: #333333;
--background: #FFFFFF;
--accent: #E6E6E6;
```

### Typographie
- **Titres** : [Police à définir]
- **Texte** : [Police à définir]
- **Taille de base** : 16px

---

## 🔧 Installation et utilisation

### Prérequis
- Navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Éditeur de code (VS Code recommandé)
- Git installé

### Cloner le projet
```bash
git clone [URL_DU_REPOSITORY]
cd [NOM_DU_PROJET]
```

### Lancer le site
1. Ouvrir `index.html` dans un navigateur
2. Ou utiliser un serveur local :
   ```bash
   # Avec Python 3
   python -m http.server 8000
   
   # Avec Node.js (http-server)
   npx http-server
   ```

---

## 🔄 Workflow Git

### Branches
- `main` : Code validé et fonctionnel
- `dev` : Développement commun
- `[prenom]-dev` : Branches personnelles

### Commandes principales
```bash
# Récupérer les dernières modifications
git pull origin dev

# Créer une nouvelle branche de fonctionnalité
git checkout -b feature/nom-fonctionnalite

# Commiter vos modifications
git add .
git commit -m "Description claire des modifications"

# Pousser sur GitHub
git push origin [nom-branche]

# Créer une Pull Request sur GitHub
```

---

## ✅ Validation W3C

Toutes les pages doivent être validées :
- **HTML** : https://validator.w3.org/
- **CSS** : https://jigsaw.w3.org/css-validator/

---

## 📊 Évaluation

| Critère | Pondération |
|---------|-------------|
| Suivis en classe | 25% |
| Maquette | 25% |
| Réalisation finale | 50% |
| **Bonus/Malus** | Créativité valorisée |

### Points d'attention
- ✅ Qualité du code (lisibilité, propreté)
- ✅ Respect des consignes
- ✅ Créativité et animations
- ✅ Design responsive
- ✅ Validation W3C
- ⚠️ Plagiat strictement interdit

---

## 📝 Livrables

- [ ] Dossier source complet (HTML/CSS/JS/media)
- [ ] Maquette du site (wireframe, Miro, etc.)
- [ ] Lien du dépôt Git/GitHub
- [ ] Documentation complète (ce README)

---

## 🎨 Fonctionnalités bonus implémentées

- [ ] Animations CSS avancées
- [ ] Mode sombre / clair
- [ ] Effets parallax
- [ ] Lazy loading des images
- [ ] Accessibilité optimisée (ARIA)
- [ ] Performance optimisée
- [ ] [Autres fonctionnalités créatives]

---

## 📚 Ressources utiles

- [MDN Web Docs](https://developer.mozilla.org/)
- [W3Schools](https://www.w3schools.com/)
- [CSS-Tricks](https://css-tricks.com/)
- [Can I Use](https://caniuse.com/)

---

## 📧 Contact

Pour toute question concernant ce projet :
- **Cours** : Web
- **Année** : 2025-2026

---

## 📄 Licence

Projet académique - EFREI Paris © 2025-2026

---

**Dernière mise à jour** : [Date]

**Statut du projet** : 🚧 En développement
