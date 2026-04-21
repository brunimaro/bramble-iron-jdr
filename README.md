# 🌲⚔️ BRAMBLE & IRON – SRD Web

> _"Dans la Forêt de Fer, les sorts mentent, les armes cassent, et seuls les plus têtus survivent."_

Un **Système de Référence (SRD) web interactif et autonome** pour **BRAMBLE & IRON**, un JDR OSR dark fantasy fusionnant la tension exploratoire de *Cairn 2e* et le chaos tactique de *Flail RPG*.  
Tout est contenu dans un seul fichier HTML : aucune dépendance serveur, aucun build, juste du pur HTML/CSS/JS prêt à jouer.

[![Licence](https://img.shields.io/badge/Licence-CC%20BY--SA%204.0-brightgreen.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Version](https://img.shields.io/badge/Version-1.0-blue.svg)](https://github.com/ton-utilisateur/bramble-iron-srd)
[![TTRPG](https://img.shields.io/badge/Genre-OSR%20%7C%20Dark%20Fantasy-orange.svg)]()

## 📖 Concept
**BRAMBLE & IRON** est un JDR "rules-lite" conçu pour des sessions nerveuses, où chaque jet compte et où le chaos fait partie du récit.  
Ce SRD web a pour vocation de :
- 📖 Centraliser toutes les règles de base dans une interface lisible
- 🎲 Proposer des outils interactifs (lanceurs de dés, tables aléatoires, générateurs)
- 📱 Fonctionner hors-ligne sur mobile ou desktop
- ⚡ Permettre une création de personnage en < 5 minutes

## ✨ Fonctionnalités

| Module | Description |
|--------|-------------|
| 🎯 **Création de Perso** | Fiche interactive avec générateur `3d6` et tirage aléatoire de Background/Classe |
| ⚔️ **Combat Poker-Enhanced** | Simulateur de pools de dés avec détection automatique de `1` critiques et d'usure d'armes |
| ✨ **Magie Push-Your-Luck** | Lanceur de sorts `1d6` à `3d6` avec calcul des conséquences et seuil de succès spectaculaire |
| 📊 **Tables Aléatoires** | Backgrounds, Objets à Risque, Rencontres `2d6`, Conséquences Magiques (cliquables) |
| ⚡ **Générateurs Rapides** | Noms, Quêtes, Trésors, Pièges, PNJ, Lieux (tout en un clic) |
| 🌙 **Design Dark Fantasy** | Typographies Cinzel & Crimson Text, palette sang/or, animations subtiles, 100% responsive |

## 🚀 Démarrage rapide

### 📦 Installation
1. Téléchargez ou clonez ce dépôt
2. Ouvrez `index.html` dans votre navigateur (Chrome, Firefox, Safari, Edge)
3. Jouez. Aucune installation requise.

### 🌐 Hébergement sur GitHub Pages
1. Allez dans `Settings > Pages` de votre dépôt GitHub
2. Sélectionnez `main` / `root` comme source
3. Votre SRD sera accessible à `https://<votre-user>.github.io/bramble-iron-srd`

### 📴 Mode 100% Hors-Ligne
Par défaut, le site charge les polices depuis Google Fonts. Pour une utilisation totalement offline :
```css
/* Remplacez l'import dans <style> par des polices système */
font-family: 'Georgia', 'Times New Roman', serif; /* Titres */
font-family: 'Segoe UI', 'Helvetica Neue', sans-serif; /* Corps */
