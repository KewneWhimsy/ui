# UI Design System Generator

Générateur de design systems pour développeurs web.

## 📦 Fichiers

### Version Light (Recommandée)
**`design-system-generator-light.html`** - ~60KB
- Générateur complet sans les effets avancés
- Presets rapides (Eco, Material, Tailwind, Sunset)
- Copy to clipboard & Download CSS
- Export/Import JSON de la config
- Boutons : Primary, Secondary, Outline, Glass, Glossy
- Cards, Badges, Alerts, Inputs
- Customisation : couleurs, typo, radius, tailles

### Composants Avancés (Isolés)
Ces composants sont séparés car très spécifiques (~15-20KB chacun) :

**`glass-advanced-component.html`**
- Bouton glassmorphism premium
- Reflets customisables (couleur, opacité)
- Ombre réglable
- Animations complexes avec @property

**`liquid-glass-component.html`**
- Dock style macOS avec effet liquide
- Distorsion SVG pour effet "liquid glass"
- Personnalisation des icônes

**`neuemorphism-component.html`**
- Bouton 3D avec effet inset
- Ombres et gradients complexes
- Variantes de tailles (small, normal, large)

### Version Pro (Complète)
**`design-system-generator-pro.html`** - ~96KB
- Tous les effets inclus dans un seul fichier
- Version originale non optimisée

## ✨ Features

### Version Light
- ✅ Copy to clipboard
- ✅ Presets rapides
- ✅ Export/Import JSON
- ✅ Sauvegarde auto (localStorage)
- ✅ Toast notifications
- ✅ Preview temps réel

### Composants Isolés
- ✅ Copy CSS + HTML
- ✅ Contrôles dédiés
- ✅ Preview sur fond approprié
- ✅ Standalone (aucune dépendance)

## 🛠️ Stack

HTML/CSS/JavaScript vanilla - Aucune dépendance

## 🎯 Usage

1. **Pour un projet standard** : Utilise `design-system-generator-light.html`
2. **Pour un effet spécifique** : Ouvre le composant isolé correspondant
3. **Pour tout avoir** : Utilise `design-system-generator-pro.html` (mais plus lourd)

## 📝 Approche KISS

- Fichiers uniques, pas de build
- Pas de framework, pas de dépendances
- Copier-coller direct
- Code optimisé et factorié
