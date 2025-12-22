# Site Web CCFA - Chikhi Conseil Formation Audit

## 📋 Description

Site web professionnel multi-pages pour CCFA (Chikhi Conseil Formation Audit), société de conseil et formation basée à Montauban, spécialisée dans l'accompagnement des associations, collectivités locales et structures de l'ESS.

## 🎨 Design

Le site s'inspire du design moderne et professionnel du site InTeam Consultants, avec :
- Design responsive adapté mobile/tablette/desktop
- Animations fluides et interactions modernes
- Palette de couleurs professionnelle (violet/rose)
- Typographie claire et hiérarchisée

## 📁 Structure du Site

```
ccfa-website/
├── index.html                    # Page d'accueil
├── a-propos.html                 # À propos / Parcours
├── contact.html                  # Contact avec formulaire
├── service-audit.html            # Audit Qualiopi (exemple)
├── styles.css                    # Feuille de style principale
├── script.js                     # JavaScript pour interactions
└── README.md                     # Ce fichier
```

## 🌟 Pages Incluses

### Pages Principales
1. **index.html** - Page d'accueil
   - Hero slider animé (3 slides)
   - Statistiques clés
   - Présentation CCFA
   - 6 services principaux
   - Clients
   - Valeurs
   - Certification Qualiopi
   - Call-to-action

2. **a-propos.html** - À propos
   - Présentation Samir Chikhi
   - Parcours professionnel (timeline)
   - Valeurs détaillées
   - Expertises

3. **service-audit.html** - Audit Qualiopi (page service modèle)
   - Présentation du service
   - Prestations détaillées
   - Méthodologie en 4 étapes
   - Avantages
   - Références clients

4. **contact.html** - Contact
   - Formulaire de contact complet
   - Coordonnées
   - Horaires
   - FAQ accordéon
   - Carte (placeholder)

## 🚀 Fonctionnalités

### Design & UX
- ✅ Responsive (mobile, tablette, desktop)
- ✅ Menu navigation avec dropdowns
- ✅ Hero slider automatique
- ✅ Animations au scroll
- ✅ Transitions fluides
- ✅ Formulaire de contact avec validation

### Navigation
- ✅ Menu sticky
- ✅ Menu mobile hamburger
- ✅ Smooth scroll
- ✅ Dropdowns services

### Interactions
- ✅ Compteurs animés (stats)
- ✅ FAQ accordéon
- ✅ Slider hero automatique
- ✅ Hover effects sur cards
- ✅ Form validation

## 🎨 Palette de Couleurs

```css
--primary-color: #667eea     (Violet principal)
--secondary-color: #764ba2   (Violet foncé)
--accent-color: #f5576c      (Rose/Rouge)
--text-dark: #2d3748         (Texte principal)
--text-light: #718096        (Texte secondaire)
--bg-light: #f7fafc          (Fond clair)
```

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablette**: 768px - 1024px
- **Mobile**: < 768px

## ⚙️ Technologies Utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Design moderne (Grid, Flexbox, Variables CSS)
- **JavaScript Vanilla** - Interactions (pas de framework)
- **Google Fonts** - Montserrat + Open Sans

## 🔧 Installation & Utilisation

### Option 1: Ouvrir directement
1. Télécharger tous les fichiers
2. Ouvrir `index.html` dans un navigateur

### Option 2: Serveur local
```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (http-server)
npx http-server

# Puis ouvrir: http://localhost:8000
```

## 📝 Pages Services à Créer

Pour compléter le site, vous pouvez dupliquer `service-audit.html` et adapter le contenu pour :

1. **service-ingenierie.html** - Ingénierie de Formation
2. **service-essms.html** - Évaluation ESSMS
3. **service-bilan.html** - Bilan de Compétences
4. **service-management.html** - Management de Transition
5. **service-territorial.html** - Développement Territorial
6. **tiers-lieu.html** - Projet Tiers-Lieu

## 🎯 Points Forts du Site

1. **Design Professionnel** 
   - Moderne et épuré
   - Inspire confiance
   - Couleurs cohérentes

2. **Expérience Utilisateur**
   - Navigation intuitive
   - Temps de chargement rapide
   - Animations subtiles

3. **Contenu Structuré**
   - Hiérarchie claire
   - Messages clés mis en avant
   - Call-to-action stratégiques

4. **Responsive**
   - Parfait sur tous les appareils
   - Menu mobile optimisé
   - Images adaptatives

## 🔄 Personnalisation

### Modifier les couleurs
Éditer les variables CSS dans `styles.css` :
```css
:root {
    --primary-color: #VotreCouleur;
    --secondary-color: #VotreCouleur;
}
```

### Ajouter des images
Remplacer les placeholders (émojis) par de vraies images :
```html
<!-- Exemple -->
<div class="service-image">
    <img src="images/service-audit.jpg" alt="Audit Qualiopi">
</div>
```

### Modifier le slider
Éditer dans `script.js` :
```javascript
slideInterval = setInterval(nextSlide, 5000); // Durée entre slides
```

## 📊 Statistiques du Site

- **6 services** présentés
- **7 références clients** 
- **27 ans** d'expérience mis en avant
- **100%** de réussite Qualiopi
- **4 valeurs** principales

## 🌐 SEO & Accessibilité

- ✅ Balises sémantiques HTML5
- ✅ Attributs alt sur les images
- ✅ Structure heading logique (h1, h2, h3...)
- ✅ Meta descriptions
- ✅ Aria labels pour navigation
- ✅ Contraste des couleurs conforme

## 📞 Contact

**CCFA - Chikhi Conseil Formation Audit**
- 📞 06 52 81 38 22
- 📧 samir@chikhi.fr
- 📍 136 rue Paul Roussel, 82290 Albefeuille Lagarde

## 📄 Licence

© 2024 CCFA - Tous droits réservés

---

**Site développé avec attention pour CCFA**
*Design inspiré par InTeam Consultants - Adapté et personnalisé pour CCFA*
