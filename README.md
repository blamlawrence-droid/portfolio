# 🚀 Portfolio Professionnel - Guide de Déploiement

Bienvenue dans ton portfolio freelance ! Ce guide te montrera comment mettre en ligne ton portfolio gratuitement sur Netlify.

## 📋 Ce que tu as dans ce dossier

```
portfolio/
├── index.html           ← Page principale de ton portfolio
├── style.css           ← Mise en forme (design moderne)
├── script.js           ← Interactions du site
├── projets/
│   ├── restaurant/      ← Démo 1 : Site vitrine restaurant
│   ├── ecommerce/       ← Démo 2 : Boutique en ligne
│   └── agency/          ← Démo 3 : Agence de services
└── README.md           ← Ce fichier
```

## 🔧 Étapes pour déployer (5 minutes)

### 1. Crée un compte GitHub (gratuit)
- Va sur [github.com](https://github.com)
- Clique "Sign up"
- Remplis avec ton email
- Termine l'inscription

### 2. Pousse ton portfolio sur GitHub
Ouvre un terminal et exécute ces commandes:

```bash
# Navigue jusqu'à ton dossier portfolio
cd /chemin/vers/portfolio

# Initialise le repo
git init

# Ajoute tous les fichiers
git add .

# Crée un commit
git commit -m "Mon portfolio professionnel"

# Configure le remote (remplace USERNAME par ton nom GitHub)
git remote add origin https://github.com/USERNAME/portfolio.git

# Pousse vers GitHub
git push -u origin main
```

**Problème ?** Si tu n'as jamais utilisé Git, utilise [GitHub Desktop](https://desktop.github.com/) (application graphique, gratuite).

### 3. Déploie sur Netlify (gratuit, URL propre)

1. Va sur [netlify.com](https://netlify.com)
2. Clique "Sign up"
3. Choisis "Sign up with GitHub"
4. Autorise Netlify à accéder à tes repos
5. Clique "New site from Git"
6. Sélectionne ton repo `portfolio`
7. Clique "Deploy site"

**C'est fait !** Netlify te donne une URL comme `tonnom.netlify.app`

### 4. (Optionnel) Personnalise ton domaine Netlify

1. Dans les paramètres Netlify, va à "Domain management"
2. Change le nom du sous-domaine
3. Tu auras quelque chose comme `jeffreson.netlify.app`

## 📝 Avant de partager ton portfolio

**À personnaliser dans `index.html` :**

- Remplace `jeffreson@example.com` par ton vrai email
- Remplace `+228 90000000` par ton vrai numéro WhatsApp (optionnel)
- Remplace les liens GitHub et LinkedIn par les tiens
- Change `Jeffreson` par ton nom complet si tu veux

**À mettre à jour dans les 3 projets démo :**

Les trois projets (restaurant, e-commerce, agence) sont des **exemples fictifs**. Tu peux :
- Les garder comme ils sont (bon pour montrer tes compétences)
- Les adapter à tes vrais services
- Les remplacer par tes vrais projets

## 🚀 À chaque mise à jour

Une fois que ton portfolio est en ligne sur Netlify :

1. Fais tes modifications en local
2. `git add .`
3. `git commit -m "description du changement"`
4. `git push`

**Netlify redéploie automatiquement** en 30 secondes. C'est magique !

## 💡 Conseils pour avoir plus de clients

### Sur ton portfolio :
1. **Remplace les images placeholder** - Ajoute des vraies captures d'écran de tes projets (si tu en as)
2. **Ajoute tes contacts directs** - Email + WhatsApp sont essentiels pour Afrique
3. **Mentionne que tu es basé à Lomé** - Les clients locaux aiment ça
4. **Parle de tes vrais projets** - Dès que tu as un client, mets son projet en ligne

### Partage ton portfolio :
- LinkedIn (pour professionnel)
- Fiverr / Upwork (avec le lien vers ton portfolio)
- WhatsApp à tes contacts
- Facebook / Twitter avec hashtags tech

## 📊 Pour tracker tes visites (optionnel)

Ajoute Google Analytics:

1. Va sur [analytics.google.com](https://analytics.google.com)
2. Crée un compte gratuit
3. Ajoute ce code avant `</body>` dans `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXX'); <!-- Remplace par ton ID -->
</script>
```

## ❓ Problèmes courants

### "Mon site ne s'affiche pas"
- Attends 1-2 minutes après le push
- Recharge la page (Ctrl+Shift+R)
- Vérifie que ton `index.html` est à la racine

### "Les images ne s'affichent pas"
- Pour l'instant, les images sont remplacées par des emojis (pour rester simple)
- À chaque projet, tu peux ajouter des vraies images

### "Je veux changer le design"
- Modifie `style.css` pour changer les couleurs/polices
- Modifie `index.html` pour changer le contenu
- Push vers GitHub et c'est en ligne !

## 🎯 Prochaines étapes

1. ✅ Deploy ton portfolio
2. 📧 Envoie le lien à 10 personnes
3. 🎨 Customize avec tes vrais projets
4. 📱 Mets ton portfolio sur tous tes profils (LinkedIn, Fiverr, etc.)
5. 💰 Attends les premiers leads !

---

**Besoin d'aide ?** Consulte les [docs Netlify](https://docs.netlify.com/) ou cherche "how to deploy HTML to Netlify" sur YouTube.

**Bon freelancing ! 🚀**
