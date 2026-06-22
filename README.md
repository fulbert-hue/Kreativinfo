[README.md](https://github.com/user-attachments/files/29203727/README.md)
# Kreativ Horizon — Portail d'information béninois
**Site HTML/CSS statique complet — Prêt à déployer**

---

## Structure du projet

```
kreativ-horizon/
├── index.html              ← Page d'accueil principale
├── css/
│   └── style.css           ← Feuille de style complète
└── pages/
    ├── politique.html
    ├── societe.html
    ├── economie.html
    ├── sport.html
    ├── culture.html
    ├── sante.html
    ├── opinion.html
    └── videos.html
```

---

## Fonctionnalités incluses

- ✅ Barre supérieure avec date dynamique et réseaux sociaux
- ✅ Logo "KH" avec slogan
- ✅ Navigation sticky avec 8 rubriques
- ✅ Bandeau breaking news animé (défilement auto)
- ✅ Grille À la Une (article principal + 2 secondaires)
- ✅ Sections Politique, Société, Économie, Sport, Culture
- ✅ Section spéciale DSSR sur fond noir
- ✅ Sidebar : Les plus lus, Météo, Réseaux sociaux, Newsletter
- ✅ 8 pages de rubriques avec filtres
- ✅ Footer complet avec 4 colonnes
- ✅ Responsive mobile (breakpoints 900px et 600px)
- ✅ Animations : pulse live, ticker breaking news
- ✅ Formulaire newsletter interactif

---

## Options de déploiement gratuit

### Option 1 — GitHub Pages (recommandé)
1. Créer un compte sur github.com
2. Nouveau dépôt public nommé `kreativ-horizon`
3. Uploader tous les fichiers
4. Aller dans Settings > Pages > Source: main branch
5. Votre site sera en ligne sur : `votre-pseudo.github.io/kreativ-horizon`

### Option 2 — Netlify (le plus simple)
1. Aller sur netlify.com
2. Glisser-déposer le dossier `kreativ-horizon` dans l'interface
3. Site en ligne instantanément sur un sous-domaine Netlify gratuit

### Option 3 — Domaine personnalisé
Pour un domaine `.bj` béninois, contacter l'ASIN (Agence des Systèmes d'Information) ou un registrar international comme Namecheap pour un `.com`.

---

## Personnalisation rapide

### Changer le nom du site
Dans tous les fichiers HTML, remplacer `Kreativ Horizon` par votre nom.

### Changer les couleurs
Dans `css/style.css`, modifier les variables CSS :
```css
:root {
  --rouge: #D62B2B;    /* Couleur principale */
  --noir: #0D0D0D;     /* Fond navigation */
}
```

### Ajouter de vraies images
Remplacer les `div.article-img-placeholder` par des balises `<img>` :
```html
<img src="images/mon-article.jpg" alt="Description de l'image">
```

### Connecter un CMS
Pour gérer les articles sans toucher au code, connecter un CMS headless :
- **Contentful** (gratuit jusqu'à 25 000 entrées)
- **Sanity.io** (gratuit avec généreux quota)
- **WordPress.com** en mode headless avec API REST

---

## Prochaines étapes recommandées

1. **Page article individuel** — gabarit pour afficher un article complet
2. **Moteur de recherche** — intégrer Algolia ou Lunr.js
3. **Commentaires** — intégrer Disqus ou Commento
4. **Publicité** — espaces publicitaires 728x90 et 300x250
5. **Google Analytics** — suivi d'audience
6. **PWA** — rendre le site installable sur mobile

---

Créé par Claude pour Kreativ Horizon — Cotonou, Bénin © 2026
