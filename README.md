# 💖 Heartbeat Resonance

**Interactive audiovisual generative art for Playtronica TOUCH ME**

Transform every touch into a living heart that pulses, glows, and sings its own melody.

![Version](https://img.shields.io/badge/version-4.1-orange)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 🌟 What is it?

**Heartbeat Resonance** is a unique artistic experience where each heart you create is a **living instrument**. 

- 🎨 **Visually**: Animated hearts with particles, pulsations, organic movements
- 🎵 **Musically**: Each heart has its own synthesizer that plays in sustain mode
- 💖 **Emotionally**: A living sound garden that you cultivate touch by touch

---

## 🚀 Quick Start

### Installation
**No installation required!** Simply open the HTML file in your browser.

```bash
# Download the project
# Open heartbeat_resonance.html in Chrome or Edge
```

### First Use

1. **Open** `heartbeat_resonance.html` in your browser
2. **Connect** your Playtronica TOUCH ME (automatic detection)
3. **Click** the "🔊 Click to activate audio" button
4. **Touch** any conductive object connected to TOUCH ME
5. **Watch** hearts being born and **listen** to them sing! 🎵

---

## ✨ Features

### 🎨 Visuals
- Animated hearts with particle systems (150-300 particles/heart)
- 6 dynamic color palettes
- Pulsations synchronized with audio
- Organic movements (Perlin noise)
- Configurable glow effects
- Optimized for 60 FPS

### 🎵 Audio
- **One unique synthesizer per heart** (v4.0 revolution!)
- Continuous sustain as long as the heart lives
- 4 different timbres (sine, triangle, square, sawtooth)
- Organic modulations (LFO + vibrato)
- 6 emotional scales
- Polyphony up to 50 voices
- Effects: Reverb + Delay

### 🎹 MIDI Support
- Playtronica TOUCH ME (optimized)
- All standard MIDI controllers
- MIDI keyboards, pads, control surfaces
- Intelligent mapping: MIDI note → scale, velocity → timbre/octave

---

## 🎭 The 6 Emotional Scales

Choose your tonality to define the scale used by the hearts:

| Emotion | Scale | Atmosphere |
|---------|-------|-----------|
| ✨ **Joyful** | C Major | Celebration, light, energy |
| 🌧️ **Melancholic** | A Minor | Contemplation, nostalgia, depth |
| ☁️ **Dreamy** | D Major | Imagination, hope, lightness |
| ❤️ **Passionate** | E Minor | Intensity, desire, drama |
| ☮️ **Peaceful** | F Major | Calm, serenity, comfort |
| 🔮 **Mystical** | B Minor | Mystery, magic, enchantment |

---

## 🎚️ Main Parameters

### Visuals
- **Heart Size** (0.5-3.0) - Size of hearts
- **Pulse Speed** (0.5-3.0) - Beat speed
- **Particle Density** (50-300) - Heart details
- **Lifetime** (2-15s) - Heart lifespan
- **Movement Speed** (0-2) - Movement speed
- **Glow Intensity** (0-20) - Glow intensity
- **Max Hearts** (10-50) - Performance limit

### Audio
- **Scale/Emotion** - Choose tonality
- **Volume** (-40 to 0 dB) - Global volume
- **Sound enabled** - Toggle on/off

---

## 🎨 Suggested Configurations

### 🧘 Meditation
```yaml
Scale: Peaceful
Heart Size: 1.0
Pulse Speed: 0.6
Lifetime: 12s
Max Hearts: 10
Volume: -20 dB
```

### 🎉 Celebration
```yaml
Scale: Joyful
Heart Size: 2.0
Pulse Speed: 1.8
Lifetime: 6s
Max Hearts: 40
Volume: -10 dB
```

### 💕 Romantic
```yaml
Scale: Passionate
Heart Size: 1.8
Pulse Speed: 1.0
Lifetime: 10s
Max Hearts: 25
Volume: -12 dB
```

---

## 💡 How Does It Work?

### The Unique Concept: Living Instruments

Each heart you create has its own Tone.js synthesizer:

```
Touch TOUCH ME 
    ↓
Heart is born (visual)
    ↓
Synthesizer created (audio)
    ↓
Note in SUSTAIN (plays continuously)
    ↓
LFO + Vibrato (breathing)
    ↓
Volume pulses with beats
    ↓
Heart dies → Progressive fade out
    ↓
Synthesizer released
```

### MIDI Mapping

**MIDI Note → Scale**
- Note 60 (C) → 1st note of scale
- Note 61 (C#) → 2nd note of scale
- Note 62 (D) → 3rd note of scale
- etc.

**Velocity → Character**
- **0-31**: Sine timbre (soft) + Low octave
- **32-63**: Triangle timbre (warm) + Medium octave
- **64-95**: Square timbre (bright) + Medium-high octave
- **96-127**: Sawtooth timbre (rich) + High octave

---

## 🛠️ Technologies

- **p5.js** (1.7.0) - Visual rendering and particles
- **Tone.js** (14.8.49) - Audio synthesis and effects
- **Web MIDI API** - MIDI communication
- **Web Audio API** - Audio processing
- **JavaScript ES6+** - Modern code

---

## 📋 Compatibility

### Browsers
- ✅ **Chrome / Edge** (recommended) - Full Web MIDI support
- ✅ **Firefox** - Visuals OK, limited MIDI
- ⚠️ **Safari** - Partial support (no Web MIDI)

### Hardware
- ✅ **Playtronica TOUCH ME** (tested and optimized)
- ✅ All MIDI controllers
- ✅ MIDI keyboards
- ✅ Control surfaces

### Systems
- ✅ Windows 10/11
- ✅ macOS 10.15+
- ✅ Linux

---

## 🎯 Use Cases

### 🌿 Sound Garden
Touch different plants → Each plant = instrument → Living musical garden

### 👥 Collective Performance
Form a human chain → Create music together → Physical and sonic connection

### 🍽️ Musical Cooking
Touch fruits, vegetables, utensils → Each ingredient = note → Culinary symphony

### 💧 Aquatic Meditation
Gently touch water → Ripples = music → Calm and peace

---

## 📚 Documentation

- **DEMARRAGE_RAPIDE.md** - Detailed guide to get started (French)
- **GUIDE_AUDIO.md** - Complete audio system (French)
- **INSTRUMENTS_VIVANTS.md** - Technical details (French)
- **VERSION_4.1.md** - Version notes (French)
- **CHANGELOG.md** - Complete history (French)
- **INDEX.md** - Index of all files (French)

---

## 🔄 Versions

### v4.1 (Current) - "Pure Hearts"
- ❌ Removed bass/pads (unnecessary background music)
- ✅ Pure heart audio only
- ✅ Better note variation
- ✅ Audio activation button compliant with Web Standards

### v4.0 - "Living Instruments"
- 🎼 Revolution: One synthesizer per heart
- 🌊 Continuous sustain, breathing sounds
- 💓 Perfect audio/visual sync

### v3.0 - "Generative Audio"
- 🎵 Tone.js audio system
- 🎭 6 musical emotions

### v2.0 - "Optimizations"
- ⚡ 3x performance improvement
- 🎨 6 color palettes

---

## 🎓 Philosophy

> *Heartbeat Resonance is not a classical music instrument.*  
> *It's a living sound garden that you cultivate.*

Each heart:
- **Is born** with a soft fade in
- **Lives** breathing and pulsing
- **Interacts** with other hearts
- **Dies** gracefully

Together, they form a **musical ecosystem** - a living organism that evolves unpredictably but always beautifully.

**What you touch = What you hear** 💖

---

## 🌈 License

**MIT License** - See [LICENSE](LICENSE) file for details.

This means you can:
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Use privately
- ✅ Sublicense

You must:
- 📄 Include copyright notice
- 📄 Include license copy

**Credits:**
- Heartbeat Resonance by Claude (Anthropic)
- p5.js (Processing Foundation) - LGPL 2.1
- Tone.js (Yotam Mann) - MIT
- Playtronica TOUCH ME

---

## 💬 Support

**Questions?** Check the complete documentation in the project.

**Issues?**
- No sound → Did you click "Activate audio"?
- MIDI not working → Chrome/Edge recommended
- Slow performance → Reduce Max Hearts to 20

---

## 🎵 Final Message

*Every touch is a heartbeat.*  
*Every heart is a song.*  
*Together, they create a symphony of algorithmic love.*

**Create love. Create music. Create life.** 💖🎵✨

---

**Version:** 4.1 - "Pure Hearts"  
**Date:** November 2025  
**Motto:** "Where every heart sings its own song"
