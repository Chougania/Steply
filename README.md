# 🚶 Steply

Une application web moderne de suivi de pas gamifiée, conçue pour vous motiver à marcher davantage avec des défis, des badges et des récompenses.

## ✨ Fonctionnalités

- **Suivi automatique** : Détectez vos pas via l'accéléromètre de votre téléphone
- **Objectifs quotidiens** : Définissez et atteignez vos objectifs personnels
- **Gamification complète** :
  - 🎯 Défis quotidiens et hebdomadaires
  - 🏅 Système de badges (6 niveaux de progression)
  - 🎡 Roue de la chance (1x par jour)
  - 🔥 Suivi des séries de jours consécutifs
  - ⭐ Système XP et niveaux

- **Historique détaillé** : Visualisez vos statistiques par jour, semaine, mois ou année
- **Exploration géographique** : Commencez une balade et découvrez de nouveaux lieux
- **Statistiques en temps réel** :
  - Distance parcourue (km)
  - Calories brûlées
  - Durée de marche

## 🎮 Mécaniques de jeu

### Système de progression
- Gagnez de l'XP en marchant (0.02 XP par pas)
- Montez de niveau tous les 100 XP
- Débloquez des badges à partir de seuils (1k, 10k, 50k, 100k, 500k, 1M pas)

### Défis
- **Défi quotidien** : Marchez 35% de votre objectif → +60 XP
- **Défi hebdomadaire** : Atteignez 80% de votre objectif * 7 jours → +200 XP
- **Coffre quotidien** : Atteignez votre objectif pour débloquer +40 à +120 XP aléatoires

### Roue de la chance
Lancez-la une fois par jour pour gagner entre 0 et 300 XP bonus !

## 📊 Statistiques

L'app suit automatiquement :
- Vos pas cumulés
- Distance totale
- Calories brûlées
- Votre série actuelle

Visualisez vos données sur 4 périodes :
- Jour (14 derniers jours)
- Semaine (8 dernières semaines)
- Mois (12 derniers mois)
- Année (5 dernières années)

## 🗺️ Exploration

Lancez une balade GPS pour :
- Tracer votre itinéraire en temps réel
- Découvrir automatiquement de nouveaux lieux intéressants tous les 300m
- Accumuler des découvertes sur votre profil

## 💾 Stockage

L'app utilise :
- `IndexedDB` (optimisé pour PWA)
- Fallback `localStorage` (pour les appareils/navigateurs limités)

Vos données sont sauvegardées localement sur votre appareil.

## 🚀 Installation

### Sur votre appareil
1. Accédez à : [votre-github-page](https://chougania.github.io/Steply)
2. Ouvrez sur mobile pour une meilleure expérience
3. Ajoutez à l'écran d'accueil pour une PWA complète

### Développement local
```bash
# Clonez le repo
git clone https://github.com/Chougania/Steply.git
cd Steply

# Servez avec un serveur local (Python)
python -m http.server 8000

# Puis ouvrez http://localhost:8000
```

## 🛠️ Tech Stack

- **HTML5** : Structure sémantique
- **CSS3** : Design moderne avec variables CSS et gradients
- **Vanilla JavaScript** : Zéro dépendances (sauf Leaflet pour la cartographie)
- **Leaflet** : Cartographie OpenStreetMap
- **PWA-ready** : Fonctionne hors ligne (avec configuration appropriée)

## 🎨 Design

- **Palette sombre** : Thème vert/lime sur fond sombre
- **Responsive** : Optimisé pour mobile (max-width: 480px)
- **Accessibilité** : Tapas clairs, feedback haptique, contrastes respectés
- **Polices** : Space Grotesk (titres), JetBrains Mono (données), Inter (corps)

## 📱 Navigateurs supportés

- ✅ Chrome/Chromium (Android)
- ✅ Firefox (Android/Desktop)
- ✅ Safari (iOS 13+)
- ✅ Edge (Desktop)

**Recommandé** : Dernière version sur mobile pour accéléromètre et géolocalisation.

## 🔐 Confidentialité

Vos données restent **100% locales** sur votre appareil. Aucun serveur n'a accès à :
- Vos pas
- Votre localisation
- Vos statistiques personnelles

## 📝 Licence

Libre d'utilisation. Adaptez et améliorez comme vous le souhaitez !

## 🤝 Contribuez

Des idées pour améliorer Steply ?
- Nouvelles récompenses
- Nouvelles gamifications
- Améliorations UI/UX
- Corrections de bugs

Créez une issue ou une PR ! 🚀

---

**Prêt à marcher ?** 🚶‍♂️ [Lancez Steply](https://chougania.github.io/Steply)
