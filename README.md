# Présentation Direction Design System

Site de présentation hébergé sur GitHub Pages.

## 🚀 Déploiement sur GitHub Pages

### Étapes pour héberger ce site :

1. **Créer un nouveau dépôt sur GitHub**
   - Allez sur [github.com](https://github.com) et créez un nouveau dépôt
   - Nommez-le comme vous le souhaitez (ex: `presentation-design-system`)

2. **Initialiser Git et pousser les fichiers**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Présentation Design System"
   git branch -M main
   git remote add origin https://github.com/VOTRE_USERNAME/VOTRE_REPO.git
   git push -u origin main
   ```

3. **Activer GitHub Pages**
   - Allez dans les **Settings** de votre dépôt GitHub
   - Dans le menu de gauche, cliquez sur **Pages**
   - Sous **Source**, sélectionnez **Deploy from a branch**
   - Choisissez la branche **main** et le dossier **/ (root)**
   - Cliquez sur **Save**

4. **Accéder à votre site**
   - Votre site sera disponible à l'adresse :
     `https://VOTRE_USERNAME.github.io/VOTRE_REPO/`
   - ⚠️ **Important** : Si votre fichier HTML s'appelle `presentation_direction_design_system.html`, 
     vous devrez y accéder via :
     `https://VOTRE_USERNAME.github.io/VOTRE_REPO/presentation_direction_design_system.html`
   - Pour que `index.html` soit la page d'accueil, renommez le fichier en `index.html`

## 📁 Structure du projet

```
.
├── presentation_direction_design_system.html  # Page principale
├── fonts/                                      # Polices personnalisées
│   └── MrDodo-Medium/
├── Zig*.svg, Zig*.png                          # Images de fond
└── README.md                                   # Ce fichier
```

## 💡 Astuce

Pour que votre site soit accessible directement à `https://VOTRE_USERNAME.github.io/VOTRE_REPO/`, 
renommez `presentation_direction_design_system.html` en `index.html`.

