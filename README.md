# Package Management - MDN Toolchain Example

> Un projet d'apprentissage de la gestion de packages npm et des outils de développement modernes, basé sur le cours [Understanding Client-Side Tools](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools) de MDN.

## 📋 Description

Ce projet est une application React qui interroge l'API GitHub pour afficher des statistiques de dépôt. Il sert de support pratique pour apprendre à utiliser une toolchain complète de développement front-end moderne.

## 🚀 Démo

Le projet est déployé sur GitHub Pages : [Voir la démo](https://romaymes-ra.github.io/package-mangement-test/)

## ✨ Fonctionnalités

- 📊 Visualisation de données GitHub avec Plotly.js
- ⚛️ Application React avec hooks modernes
- 🔄 Gestion des requêtes API avec TanStack Query
- 🎨 CSS Modules pour le styling scopé
- ⚡ Build optimisé avec Vite

## 🛠️ Technologies utilisées

### Framework & Librairies
- **React 19** - Interface utilisateur
- **Vite 7** - Build tool et dev server
- **TanStack Query** - Gestion des requêtes asynchrones
- **Plotly.js** - Visualisation de données

### Outils de qualité du code
- **ESLint 8** - Linting JavaScript/JSX
- **Prettier 3** - Formatage automatique du code
- **eslint-plugin-react** - Rules spécifiques React
- **eslint-plugin-react-hooks** - Validation des hooks React

## 📦 Installation

### Prérequis
- Node.js (v18 ou supérieur)
- npm ou yarn

### Étapes

1. Cloner le dépôt
```bash
git clone https://github.com/romaymes-ra/package-mangement-test.git
cd package-mangement-test
```

2. Installer les dépendances
```bash
npm install
```

## 🎯 Utilisation

### Développement

Lancer le serveur de développement avec hot-reload :
```bash
npm run dev
```
Le site sera accessible sur `http://localhost:5173/`

### Build de production

Créer une version optimisée pour la production :
```bash
npm run build
```
Les fichiers générés seront dans le dossier `dist/`

### Preview du build

Prévisualiser le build de production localement :
```bash
npm run preview
```

### Formatage du code

Formater automatiquement tous les fichiers :
```bash
npm run format
```

### Linting

Vérifier le code avec ESLint :
```bash
npx eslint .
```

## 📁 Structure du projet

```
package-management/
├── .github/
│   └── workflows/          # GitHub Actions (CI/CD)
├── public/                 # Assets statiques
│   ├── fonts/
│   └── images/
├── src/                    # Code source
│   ├── assets/
│   ├── components/         # Composants React
│   ├── constants/
│   ├── hooks/              # Custom hooks
│   ├── pages/
│   ├── services/           # API calls
│   ├── store/              # State management
│   ├── styles/
│   ├── utils/              # Fonctions utilitaires
│   ├── App.jsx             # Composant principal
│   ├── App.module.css      # Styles du composant App
│   ├── main.jsx            # Point d'entrée
│   └── index.css           # Styles globaux
├── tests/                  # Tests unitaires
├── .gitignore
├── .prettierrc.json        # Config Prettier
├── .prettierignore
├── eslint.config.js        # Config ESLint
├── vite.config.js          # Config Vite
├── index.html              # Template HTML
├── package.json
└── README.md
```

## 📜 Scripts disponibles

| Commande | Description |
|----------|-------------|
| `npm run dev` | Démarre le serveur de développement |
| `npm run build` | Crée le build de production |
| `npm run preview` | Prévisualise le build de production |
| `npm run format` | Formate le code avec Prettier |

## ⚙️ Configuration

### Vite
Configuration dans `vite.config.js` :
- Plugin React pour supporter JSX
- Base path configuré pour GitHub Pages

### ESLint
Configuration dans `eslint.config.js` :
- Rules recommandées ESLint
- Support React et JSX
- Validation des hooks React

### Prettier
Configuration dans `.prettierrc.json` :
- `bracketSameLine: true` - Brackets sur la même ligne

## 🚀 Déploiement

Le projet est configuré pour un déploiement automatique sur GitHub Pages via GitHub Actions.

À chaque push sur la branche `master`, le workflow :
1. Installe les dépendances
2. Build le projet
3. Déploie sur GitHub Pages

URL de production : `https://romaymes-ra.github.io/package-mangement-test/`

## 📚 Ressources d'apprentissage

Ce projet est basé sur les cours MDN :
- [Understanding Client-Side Tools](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools)
- [Package Management](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Package_management)
- [Introducing a complete toolchain](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Introducing_complete_toolchain)
- [Deploying our app](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Deployment)

## 👤 Auteur

**Romain Aymes**
- GitHub: [@romaymes-ra](https://github.com/romaymes-ra)

## 📄 Licence

ISC

## 🙏 Remerciements

- [MDN Web Docs](https://developer.mozilla.org/) pour les excellents tutoriels
- Projet inspiré de [mdn/client-toolchain-example](https://github.com/mdn/client-toolchain-example)
