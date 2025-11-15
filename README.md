# 🚀 Automatisation RH IA - Page de Vente

Page de vente professionnelle pour promouvoir un système d'automatisation RH intelligent basé sur n8n, OpenAI et Airtable.

## 📋 Contenu

- **Page de vente complète** avec toutes les sections demandées
- **Design moderne** et responsive
- **Animations** et interactions fluides
- **Optimisée** pour la conversion

## 🎨 Structure

### Sections incluses :

1. **Hero** - Titre accrocheur avec CTA principal
2. **Le problème** - Pain points des équipes RH
3. **La solution** - Présentation de l'automatisation
4. **Fonctionnement** - Workflow en 6 étapes
5. **Résultats** - Bénéfices concrets
6. **Tarifs** - 3 packs (Essentiel, Pro, Premium)
7. **Pourquoi nous** - Arguments différenciants
8. **Témoignages** - Preuve sociale
9. **CTA Final** - Appel à l'action puissant

## 🚀 Utilisation

### Ouvrir la page :

1. Double-cliquez sur `index.html` pour l'ouvrir dans votre navigateur
2. Ou faites un clic droit → "Ouvrir avec" → votre navigateur préféré

### Personnalisation :

#### Modifier les coordonnées de contact :

Dans `index.html`, recherchez et remplacez :
```html
mailto:contact@votre-entreprise.com
```
Par votre véritable adresse email.

#### Modifier les couleurs :

Dans `styles.css`, modifiez les variables CSS au début du fichier :
```css
:root {
    --primary-color: #6366f1;    /* Couleur principale */
    --secondary-color: #06b6d4;   /* Couleur secondaire */
    --accent-color: #f59e0b;      /* Couleur d'accent */
}
```

#### Modifier les tarifs :

Recherchez la section `pricing-section` dans `index.html` et ajustez les prix et fonctionnalités.

## 🎯 Fonctionnalités

- ✅ Design responsive (mobile, tablette, desktop)
- ✅ Animations au survol
- ✅ Gradient modernes
- ✅ Typographie professionnelle (Inter)
- ✅ Sections optimisées pour la conversion
- ✅ CTAs clairs et visibles
- ✅ Cards avec effets 3D
- ✅ Workflow visuel

## 🛠️ Technologies

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Google Fonts (Inter)

## 📱 Compatibilité

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile (iOS/Android)

## 🎨 Personnalisation avancée

### Ajouter une vidéo de démo :

Dans la section Hero, ajoutez :
```html
<div class="video-container">
    <iframe src="URL_DE_VOTRE_VIDEO" frameborder="0" allowfullscreen></iframe>
</div>
```

### Ajouter Google Analytics :

Avant la balise `</head>`, ajoutez :
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Ajouter un chatbot :

Avant la balise `</body>`, ajoutez votre code de chatbot (Intercom, Crisp, etc.)

## 📈 Optimisation SEO

Pour améliorer le référencement, ajoutez dans `<head>` :

```html
<meta name="keywords" content="automatisation RH, IA recrutement, tri CV automatique, n8n, Airtable">
<meta property="og:title" content="Automatisation RH IA - Recrutement Intelligent">
<meta property="og:description" content="Transformez vos CV entrants en candidats triés automatiquement">
<meta property="og:image" content="URL_DE_VOTRE_IMAGE">
<meta name="twitter:card" content="summary_large_image">
```

## 📞 Support

Pour toute question ou personnalisation, contactez-nous via le formulaire de la page.

## 📄 Licence

© 2025 - Tous droits réservés

---

**Note** : Cette page est prête à l'emploi. Pensez simplement à :
1. Remplacer l'adresse email de contact
2. Ajouter vos propres images/logos si souhaité
3. Ajuster les tarifs selon votre stratégie
4. Héberger sur un serveur web pour la production