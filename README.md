# Portfolio - Floriane Guillou

Portfolio personnel présentant mes projets académiques et compétences en développement et data science.

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer un dépôt GitHub

1. Allez sur [GitHub.com](https://github.com) et connectez-vous
2. Cliquez sur le bouton **"+"** en haut à droite, puis sélectionnez **"New repository"**
3. Donnez un nom à votre dépôt (par exemple : `portfolio` ou `floriane-guillou-portfolio`)
4. Choisissez **Public** (pour que GitHub Pages soit gratuit)
5. **Ne cochez PAS** "Initialize this repository with a README" (vous avez déjà un README)
6. Cliquez sur **"Create repository"**

### Étape 2 : Initialiser Git et pousser votre code

Ouvrez votre terminal (PowerShell, CMD, ou Git Bash) dans le dossier de votre portfolio et exécutez ces commandes :

```bash
# Initialiser Git (si ce n'est pas déjà fait)
git init

# Ajouter tous les fichiers
git add .

# Créer le premier commit
git commit -m "Initial commit: Portfolio"

# Ajouter votre dépôt GitHub (remplacez USERNAME par votre nom d'utilisateur GitHub)
git remote add origin https://github.com/USERNAME/portfolio.git

# Pousser le code sur GitHub
git branch -M main
git push -u origin main
```

**Note :** Remplacez `USERNAME` par votre nom d'utilisateur GitHub et `portfolio` par le nom de votre dépôt.

### Étape 3 : Activer GitHub Pages

1. Allez sur votre dépôt GitHub (sur le site web)
2. Cliquez sur l'onglet **"Settings"** (en haut du dépôt)
3. Dans le menu de gauche, cliquez sur **"Pages"** (dans la section "Code and automation")
4. Sous **"Source"**, sélectionnez **"Deploy from a branch"**
5. Choisissez la branche **"main"** et le dossier **"/ (root)"**
6. Cliquez sur **"Save"**

### Étape 4 : Accéder à votre portfolio

Après quelques minutes (généralement 1-2 minutes), votre portfolio sera accessible à l'adresse :

```
https://USERNAME.github.io/portfolio/
```

**Remplacez :**
- `USERNAME` par votre nom d'utilisateur GitHub
- `portfolio` par le nom de votre dépôt

### 🔄 Mettre à jour votre portfolio

Chaque fois que vous modifiez votre portfolio, utilisez ces commandes pour mettre à jour le site :

```bash
# Ajouter les modifications
git add .

# Créer un commit avec un message descriptif
git commit -m "Description de vos modifications"

# Pousser les modifications sur GitHub
git push
```

Les modifications seront visibles sur votre site GitHub Pages après quelques minutes.

## 📁 Structure du projet

```
portfolio/
│
├── index.html      # Page principale du portfolio
├── styles.css      # Styles CSS
├── script.js       # JavaScript pour les interactions
└── README.md       # Ce fichier
```

## 🎨 Fonctionnalités

- ✅ Design moderne et responsive
- ✅ Navigation fluide entre les sections
- ✅ Animations au scroll
- ✅ Menu mobile pour les petits écrans
- ✅ Sections : Accueil, Projets, Compétences, Contact
- ✅ Compatible avec tous les navigateurs modernes

## 📝 Personnalisation

Vous pouvez facilement personnaliser votre portfolio en modifiant :

- **Contenu** : Éditez `index.html` pour changer les textes
- **Couleurs** : Modifiez les variables CSS dans `styles.css` (section `:root`)
- **Animations** : Ajustez les animations dans `script.js`

## 🆘 Aide

Si vous rencontrez des problèmes :

1. **Git n'est pas installé** : Téléchargez-le sur [git-scm.com](https://git-scm.com/)
2. **Erreur de connexion GitHub** : Vérifiez que vous êtes connecté avec `git config --global user.name` et `git config --global user.email`
3. **Le site ne s'affiche pas** : Attendez 2-3 minutes après l'activation de GitHub Pages, puis vérifiez l'onglet "Actions" dans votre dépôt pour voir s'il y a des erreurs

## 📧 Contact

- Email : floriane0602@gmail.com
- LinkedIn : [Floriane Guillou](https://www.linkedin.com/in/floriane-guillou-1a46432a4)

---

Bon courage avec votre portfolio ! 🎉

