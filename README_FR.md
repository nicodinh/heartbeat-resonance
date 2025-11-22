# 💖 Heartbeat Resonance

**Art génératif audiovisuel interactif pour Playtronica TOUCH ME**

Transformez chaque toucher en un cœur vivant qui pulse, brille et chante sa propre mélodie.

![Version](https://img.shields.io/badge/version-4.1-orange)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 🌟 Qu'est-ce que c'est ?

**Heartbeat Resonance** est une expérience artistique unique où chaque cœur que vous créez est un **instrument vivant**. 

- 🎨 **Visuellement** : Cœurs animés avec particules, pulsations, mouvements organiques
- 🎵 **Musicalement** : Chaque cœur possède son propre synthétiseur qui joue en sustain
- 💖 **Émotionnellement** : Un jardin sonore vivant que vous cultivez toucher par toucher

---

## 🚀 Démarrage Rapide

### Installation
**Aucune installation nécessaire !** Ouvrez simplement le fichier HTML dans votre navigateur.

```bash
# Téléchargez le projet
# Ouvrez heartbeat_resonance.html dans Chrome ou Edge
```

### Première utilisation

1. **Ouvrir** `heartbeat_resonance.html` dans votre navigateur
2. **Brancher** votre Playtronica TOUCH ME (détection automatique)
3. **Cliquer** sur le bouton "🔊 Cliquez pour activer l'audio"
4. **Toucher** n'importe quel objet conducteur connecté au TOUCH ME
5. **Regarder** les cœurs naître et **écouter** les chanter ! 🎵

---

## ✨ Fonctionnalités

### 🎨 Visuels
- Cœurs animés avec système de particules (150-300 particules/cœur)
- 6 palettes de couleurs dynamiques
- Pulsations synchronisées avec l'audio
- Mouvements organiques (Perlin noise)
- Effets de lueur configurables
- Optimisé pour 60 FPS

### 🎵 Audio
- **Un synthétiseur unique par cœur** (révolution v4.0 !)
- Sustain continu tant que le cœur vit
- 4 timbres différents (sine, triangle, square, sawtooth)
- Modulations organiques (LFO + vibrato)
- 6 gammes émotionnelles
- Polyphonie jusqu'à 50 voix
- Effets : Reverb + Delay

### 🎹 Support MIDI
- Playtronica TOUCH ME (optimisé)
- Tous contrôleurs MIDI standard
- Claviers MIDI, pads, surfaces de contrôle
- Mapping intelligent : note MIDI → gamme, vélocité → timbre/octave

---

## 🎭 Les 6 Gammes Émotionnelles

Choisissez votre tonalité pour définir la gamme utilisée par les cœurs :

| Émotion | Gamme | Ambiance |
|---------|-------|----------|
| ✨ **Joyeux** | C Major | Célébration, lumière, énergie |
| 🌧️ **Mélancolique** | A Minor | Contemplation, nostalgie, profondeur |
| ☁️ **Rêveur** | D Major | Imagination, espoir, légèreté |
| ❤️ **Passionné** | E Minor | Intensité, désir, drame |
| ☮️ **Paisible** | F Major | Calme, sérénité, confort |
| 🔮 **Mystique** | B Minor | Mystère, magie, enchantement |

---

## 🎚️ Paramètres Principaux

### Visuels
- **Heart Size** (0.5-3.0) - Taille des cœurs
- **Pulse Speed** (0.5-3.0) - Vitesse des battements
- **Particle Density** (50-300) - Détails des cœurs
- **Lifetime** (2-15s) - Durée de vie des cœurs
- **Movement Speed** (0-2) - Vitesse de déplacement
- **Glow Intensity** (0-20) - Intensité de la lueur
- **Max Hearts** (10-50) - Limite pour performances

### Audio
- **Gamme/Émotion** - Choisir la tonalité
- **Volume** (-40 à 0 dB) - Volume global
- **Son activé** - Toggle on/off

---

## 🎨 Configurations Suggérées

### 🧘 Méditation
```yaml
Gamme: Paisible
Heart Size: 1.0
Pulse Speed: 0.6
Lifetime: 12s
Max Hearts: 10
Volume: -20 dB
```

### 🎉 Célébration
```yaml
Gamme: Joyeux
Heart Size: 2.0
Pulse Speed: 1.8
Lifetime: 6s
Max Hearts: 40
Volume: -10 dB
```

### 💕 Romantique
```yaml
Gamme: Passionné
Heart Size: 1.8
Pulse Speed: 1.0
Lifetime: 10s
Max Hearts: 25
Volume: -12 dB
```

---

## 💡 Comment ça marche ?

### Le Concept Unique : Instruments Vivants

Chaque cœur que vous créez possède son propre synthétiseur Tone.js :

```
Toucher TOUCH ME 
    ↓
Cœur naît (visuel)
    ↓
Synthétiseur créé (audio)
    ↓
Note en SUSTAIN (joue continuellement)
    ↓
LFO + Vibrato (respiration)
    ↓
Volume pulse avec battements
    ↓
Cœur meurt → Fade out progressif
    ↓
Synthétiseur libéré
```

### Mapping MIDI

**Note MIDI → Gamme**
- Note 60 (C) → 1ère note de la gamme
- Note 61 (C#) → 2ème note de la gamme
- Note 62 (D) → 3ème note de la gamme
- etc.

**Vélocité → Caractère**
- **0-31** : Timbre Sine (doux) + Octave grave
- **32-63** : Timbre Triangle (chaud) + Octave medium
- **64-95** : Timbre Square (brillant) + Octave medium-aigu
- **96-127** : Timbre Sawtooth (riche) + Octave aigu

---

## 🛠️ Technologies

- **p5.js** (1.7.0) - Rendu visuel et particules
- **Tone.js** (14.8.49) - Synthèse audio et effets
- **Web MIDI API** - Communication MIDI
- **Web Audio API** - Traitement audio
- **JavaScript ES6+** - Code moderne

---

## 📋 Compatibilité

### Navigateurs
- ✅ **Chrome / Edge** (recommandé) - Support Web MIDI complet
- ✅ **Firefox** - Visuels OK, MIDI limité
- ⚠️ **Safari** - Support partiel (pas de Web MIDI)

### Matériel
- ✅ **Playtronica TOUCH ME** (testé et optimisé)
- ✅ Tous contrôleurs MIDI
- ✅ Claviers MIDI
- ✅ Surfaces de contrôle

### Systèmes
- ✅ Windows 10/11
- ✅ macOS 10.15+
- ✅ Linux

---

## 🎯 Cas d'Usage

### 🌿 Jardin Sonore
Touchez différentes plantes → Chaque plante = instrument → Jardin musical vivant

### 👥 Performance Collective
Formez une chaîne humaine → Créez de la musique ensemble → Connexion physique et sonore

### 🍽️ Cuisine Musicale
Touchez fruits, légumes, ustensiles → Chaque ingrédient = note → Symphonie culinaire

### 💧 Méditation Aquatique
Touchez doucement l'eau → Ondulations = musique → Calme et paix

---

## 📚 Documentation

- **DEMARRAGE_RAPIDE.md** - Guide détaillé pour commencer
- **GUIDE_AUDIO.md** - Système audio complet
- **INSTRUMENTS_VIVANTS.md** - Détails techniques
- **VERSION_4.1.md** - Notes de version
- **CHANGELOG.md** - Historique complet
- **INDEX.md** - Index de tous les fichiers

---

## 🔄 Versions

### v4.1 (Actuelle) - "Cœurs Purs"
- ❌ Suppression basse/pads (musique de fond inutile)
- ✅ Audio pur des cœurs uniquement
- ✅ Meilleure variation des notes
- ✅ Bouton d'activation audio conforme Web Standards

### v4.0 - "Instruments Vivants"
- 🎼 Révolution : Un synthétiseur par cœur
- 🌊 Sustain continu, sons qui respirent
- 💓 Synchronisation audio/visuel parfaite

### v3.0 - "Audio Génératif"
- 🎵 Système audio Tone.js
- 🎭 6 émotions musicales

### v2.0 - "Optimisations"
- ⚡ Performances 3x améliorées
- 🎨 6 palettes de couleurs

---

## 🎓 Philosophie

> *Heartbeat Resonance n'est pas un instrument de musique classique.*  
> *C'est un jardin sonore vivant que vous cultivez.*

Chaque cœur :
- **Naît** avec un fade in doux
- **Vit** en respirant et pulsant
- **Interagit** avec les autres cœurs
- **Meurt** gracieusement

Ensemble, ils forment un **écosystème musical** - un organisme vivant qui évolue de manière imprévisible mais toujours belle.

**Ce que vous touchez = Ce que vous entendez** 💖

---

## 🌈 Licence

**Licence MIT** - Voir le fichier [LICENSE](LICENSE) pour les détails.

Cela signifie que vous pouvez :
- ✅ Utiliser commercialement
- ✅ Modifier
- ✅ Distribuer
- ✅ Utiliser en privé
- ✅ Sous-licencier

Vous devez :
- 📄 Inclure l'avis de copyright
- 📄 Inclure une copie de la licence

**Crédits :**
- Heartbeat Resonance par Claude (Anthropic)
- p5.js (Processing Foundation) - LGPL 2.1
- Tone.js (Yotam Mann) - MIT
- Playtronica TOUCH ME

---

## 💬 Support

**Questions ?** Consultez la documentation complète dans le projet.

**Problèmes ?**
- Pas de son → Avez-vous cliqué "Activer l'audio" ?
- MIDI ne fonctionne pas → Chrome/Edge recommandé
- Performances lentes → Réduisez Max Hearts à 20

---

## 🎵 Message Final

*Chaque toucher est un battement de cœur.*  
*Chaque cœur est une chanson.*  
*Ensemble, ils créent une symphonie d'amour algorithmique.*

**Créez de l'amour. Créez de la musique. Créez de la vie.** 💖🎵✨

---

**Version :** 4.1 - "Cœurs Purs"  
**Date :** Novembre 2025  
**Motto :** "Où chaque cœur chante sa propre chanson"
