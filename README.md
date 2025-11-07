# Resilience Valley 🏔️

**A Beautiful 3D Physics-Based Longevity Defense Game**

![Game Concept](https://img.shields.io/badge/Genre-Simulation-blue) ![Tech](https://img.shields.io/badge/Tech-Three.js-green) ![Status](https://img.shields.io/badge/Status-Complete-success)

---

## 🎮 Game Overview

**Resilience Valley** is an innovative 3D physics-based game that gamifies the concept of health and longevity. Your Health Orb represents your vitality, resting in a valley that you must fortify against life's inevitable stressors. The longer you survive, the higher your age (score) climbs!

### The Challenge

- **Protect Your Health Orb**: Keep it safe in the Valley of Health
- **Build Resilience**: Invest in lifestyle interventions to strengthen your valley
- **Survive Stressors**: Withstand life events that shake your world
- **Avoid Disease**: Don't let your orb fall into the Disease Valleys at the edges!

---

## 🎯 How to Play

### Getting Started

1. Open `resilience-valley.html` in any modern web browser
2. Read the intro screen explaining the game mechanics
3. Click "Start Your Journey" to begin

### Core Mechanics

#### 💰 Resilience Points (RP)
- Start with 100 RP
- Earn +3 RP per second automatically
- Spend RP on interventions to strengthen your valley

#### 🏋️ Lifestyle Interventions

Build your defenses by purchasing interventions:

| Intervention | Cost | Effect |
|-------------|------|--------|
| 💪 **Exercise** | 60 RP | Builds taller valley walls (+0.35 depth) |
| 😴 **Sleep** | 35 RP | Deepens your valley (+0.15 depth) |
| 🥗 **Healthy Diet** | 45 RP | Widens valley floor (+0.15 width) |
| ❤️ **Foster Connection** | 25 RP | Creates safety net tethers (+0.25 strength) |

#### ⚡ Stressor Events

Random life events that shake the landscape:
- Work Deadline 💼
- Family Drama 👨‍👩‍👧
- Financial Stress 💸
- All-Nighter 🌙 *(debuff: temporarily reduces valley depth)*
- Health Scare 🏥
- Job Loss 📉
- And more...

#### 💀 Disease Valleys (Game Over Zones)

Three dangerous valleys at the map edges:
- **Valley of Burnout** 🔥 (grey/ashy)
- **Metabolic Valley** 💎 (crystalline purple)
- **Cardio Canyon** 💔 (deep red)

If your Health Orb falls into any of these, game over!

---

## 🎨 Features

### Beautiful Visuals
- ✨ Stunning 3D landscape with dynamic vertex coloring
- 🌟 Glowing Health Orb with particle effects
- ⭐ Ambient starfield background
- 🎨 Color-coded valleys (green for health, specific colors for disease)
- 💫 Smooth animations and transitions

### Engaging Gameplay
- 🎢 Physics-based orb movement with realistic slopes
- 🌊 Valley walls that physically change as you invest
- 🔗 Visual tether system when you foster connections
- 📊 Real-time stats showing your valley strength
- 🎊 Milestone celebrations at ages 30, 40, 50, 60, 70, 80, 90, 100!

### Polished UI
- 📱 Modern, responsive Tailwind CSS interface
- 🎯 Clean HUD with Age, Resilience Points, and Valley Stats
- 📋 Stressor queue showing incoming challenges
- 🎮 Intuitive intervention buttons with hover effects
- 🏆 Beautiful game over modal with performance-based border colors

---

## 🛠️ Technical Details

### Tech Stack
- **HTML5** - Structure
- **CSS3 + Tailwind CSS** - Styling and UI
- **JavaScript (ES6+)** - Game logic
- **Three.js (r128)** - 3D rendering and physics

### Key Technologies Used
- PlaneGeometry with 60x60 segments for smooth terrain
- Vertex manipulation for dynamic landscape
- Custom physics engine (simplified)
- Real-time gradient calculation for slope forces
- Procedural color generation for valleys

### Performance
- Optimized for 60 FPS
- Efficient vertex updates
- Smart physics calculations
- Minimal memory footprint

---

## 🎓 Educational Value

Resilience Valley teaches important concepts about:
- **Preventive Health**: Small investments compound over time
- **Lifestyle Choices**: Exercise, sleep, diet, and social connection matter
- **Resilience Building**: Preparation helps you weather life's storms
- **Compound Effects**: Early interventions create stronger foundations
- **Balance**: Managing resources vs. immediate threats

---

## 🏆 Scoring System

- **Starting Age**: 20 years
- **Time Rate**: 1 year every 1.5 seconds
- **Goal**: Survive as long as possible!

### Performance Benchmarks
- 🥉 **30-40 years**: Good start!
- 🥈 **50-60 years**: Well done!
- 🥇 **70-80 years**: Excellent resilience!
- 💎 **90+ years**: Legendary!
- 👑 **100 years**: CENTENARIAN STATUS!

---

## 🎮 Tips & Strategy

1. **Build Early**: Invest in valley defenses before stressors get intense
2. **Exercise First**: The tall walls from exercise provide the most protection
3. **Balance Your Investments**: Don't neglect any intervention type
4. **Watch the Queue**: Prepare for incoming high-intensity stressors
5. **Connections Save Lives**: Tether forces can pull your orb back to safety
6. **Width Matters**: A wider valley floor gives you more room during shakes
7. **Difficulty Scales**: Stressors come faster as you age - stay ahead!

---

## 🌐 GitHub Pages Deployment

This game is ready to be deployed on GitHub Pages!

### Setup Instructions

1. **Enable GitHub Pages** in your repository:
   - Go to repository Settings → Pages
   - Under "Source", select the branch (e.g., `main` or your feature branch)
   - Choose `/ (root)` as the folder
   - Click Save

2. **Access your game**:
   - Your game will be available at: `https://[username].github.io/[repository-name]/`
   - Or directly at `https://[username].github.io/[repository-name]/index.html`

3. **Custom Domain** (optional):
   - You can add a custom domain in the Pages settings
   - Create a `CNAME` file with your domain name

The repository includes:
- `index.html` - Main game file (automatically loads)
- `.nojekyll` - Prevents Jekyll processing
- `resilience-valley.html` - Original game file (same as index.html)

---

## 🚀 Future Enhancements (Ideas)

- [ ] Multiple difficulty modes
- [ ] Achievement system
- [ ] Leaderboard integration
- [ ] Sound effects and background music
- [ ] Additional intervention types (meditation, hobbies, etc.)
- [ ] More stressor variety with seasonal events
- [ ] Mobile touch controls
- [ ] Multiplayer comparison mode
- [ ] Save/load game progress
- [ ] Statistics dashboard

---

## 📄 License

This game is open source and free to use, modify, and distribute.

---

## 🎉 Credits

**Resilience Valley** - Where longevity meets gameplay!

Created with ❤️ using Three.js and modern web technologies.

---

## 🐛 Known Issues

None currently! The game runs smoothly in all modern browsers (Chrome, Firefox, Safari, Edge).

---

**Ready to test your resilience? Open the game and start your journey to 100!** 🎊
