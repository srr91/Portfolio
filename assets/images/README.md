# 🖼️ Images - Portfolio BTS SIO

## 📁 Organisation des images

### 🏢 **Logos** (`/logos/`)
```
logos/
├── goopy-logo.png          # Logo entreprise alternance
├── technologies/
│   ├── html5.png          # Logo HTML5
│   ├── css3.png           # Logo CSS3
│   ├── javascript.png     # Logo JavaScript
│   ├── nodejs.png         # Logo Node.js
│   ├── php.png            # Logo PHP
│   ├── mysql.png          # Logo MySQL
│   └── git.png            # Logo Git
└── certifications/
    ├── bts-sio.png        # Logo BTS SIO
    └── cisco.png          # Certifications Cisco
```

### 🚀 **Projets** (`/projects/`)
```
projects/
├── portfolio/
│   ├── homepage.png       # Screenshot page d'accueil
│   ├── about.png          # Screenshot page à propos
│   └── projects.png       # Screenshot page projets
├── ecommerce/
│   ├── shop-home.png      # Site e-commerce - accueil
│   └── shop-cart.png      # Site e-commerce - panier
└── api-rest/
    ├── endpoints.png      # Documentation API
    └── postman.png        # Tests Postman
```

### 👤 **Profil** (`/profile/`)
```
profile/
├── avatar.jpg             # Photo de profil principale
├── professional.jpg       # Photo professionnelle
├── team-goopy.jpg         # Photo équipe GOOPY
└── graduation.jpg         # Photo remise diplôme
```

### 🎨 **Icônes** (`/icons/`)
```
icons/
├── ui/
│   ├── menu.svg          # Icône menu hamburger
│   ├── close.svg         # Icône fermeture
│   ├── arrow.svg         # Flèches navigation
│   └── download.svg      # Icône téléchargement
├── social/
│   ├── linkedin.svg      # LinkedIn
│   ├── github.svg        # GitHub
│   ├── email.svg         # Email
│   └── phone.svg         # Téléphone
└── skills/
    ├── code.svg          # Développement
    ├── database.svg      # Base de données
    ├── server.svg        # Administration système
    └── design.svg        # Design web
```

## 📏 **Formats recommandés**

### 🖼️ **Images principales**
- **Format** : PNG (transparence) ou JPG (photos)
- **Résolution** : 1920x1080px max pour screenshots
- **Poids** : < 500KB par image

### 🏢 **Logos**
- **Format** : PNG avec transparence
- **Taille** : 200x200px ou 300x100px
- **Poids** : < 50KB

### 👤 **Photos profil**
- **Format** : JPG
- **Taille** : 400x400px (carré) ou 300x400px (portrait)
- **Poids** : < 200KB

### 🎨 **Icônes**
- **Format** : SVG (vectoriel) ou PNG
- **Taille** : 24x24px, 32x32px, 64x64px
- **Poids** : < 10KB

## 🎯 **Utilisation dans le code**

### HTML
```html
<!-- Logo entreprise -->
<img src="assets/images/logos/goopy-logo.png" alt="GOOPY">

<!-- Screenshot projet -->
<img src="assets/images/projects/portfolio/homepage.png" alt="Portfolio">

<!-- Photo profil -->
<img src="assets/images/profile/avatar.jpg" alt="Enzo Teixeira">

<!-- Icône -->
<img src="assets/images/icons/ui/menu.svg" alt="Menu">
```

### CSS
```css
/* Background image */
.hero {
    background-image: url('../images/profile/professional.jpg');
}

/* Icône en pseudo-élément */
.skill::before {
    content: url('../images/icons/skills/code.svg');
}
```

## ✅ **Bonnes pratiques**

### 📝 **Nommage**
- **Descriptif** : `portfolio-homepage.png` plutôt que `img1.png`
- **Cohérent** : Même convention pour tous les fichiers
- **Sans espaces** : Utiliser `-` ou `_`

### 🎨 **Optimisation**
- **Compression** : Réduire le poids sans perdre la qualité
- **Formats adaptés** : SVG pour icônes, PNG pour logos, JPG pour photos
- **Responsive** : Prévoir plusieurs tailles si nécessaire

### 📱 **Accessibilité**
- **Alt text** : Toujours renseigner l'attribut `alt`
- **Contraste** : Vérifier la lisibilité sur différents fonds
- **Taille** : Lisible sur mobile et desktop

---
*Organisation optimisée pour un portfolio professionnel* 📸
