# 🎮 Memory Game - Play with Friends or AI

A fun and interactive memory card matching game built with **HTML, CSS, and JavaScript**. Challenge your friend or test your skills against an intelligent AI opponent!

![Memory Game](https://img.shields.io/badge/Game-Memory-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34C26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![License](https://img.shields.io/badge/License-MIT-green)

---

## 📋 Overview

**Memory Game** is a classic memory card matching game with two exciting modes:
- **👥 Two-Player Mode** - Play with a friend on the same device
- **🤖 AI Mode** - Challenge an intelligent computer opponent with smart memory and strategy

It's designed for quick fun, testing your memory skills, and competing for the highest score. Perfect for all ages!

```
┌──────────────────────────────────────┐
│    🎮 MEMORY MATCH BY KRISH 🎮       │
│                                      │
│  ┌──────────┐  ┌──────────┐          │
│  │ 👥 2P    │  │ 🤖 AI    │          │
│  └──────────┘  └──────────┘          │
│                                      │
│   ┌─────┐  ┌─────┐  ┌─────┐         │
│   │  🍎  │  │  ?  │  │  🍌 │         │
│   └─────┘  └─────┘  └─────┘         │
│                                      │
│   👤 Player: 5 pairs | 🤖 AI: 4     │
│                                      │
│     🔄 RESTART  ❓ HELP              │
└──────────────────────────────────────┘
```

---

## ✨ Features

### 🎮 Gameplay
- 🎲 **Interactive Card Flipping** - Click to reveal hidden cards
- 👥 **Two-Player Mode** - Play with a friend on the same device
- 🤖 **AI Opponent** - Smart AI with memory and strategic matching
- 🏆 **Score Tracking** - Automatic match counting
- 🎯 **Turn-Based Gameplay** - Automatic player switching

### 🎨 User Experience
- 🌈 **Responsive Design** - Works on desktop, tablet, and mobile
- ⚡ **Smooth Animations** - Beautiful card flip and transition effects
- 📱 **User-Friendly Interface** - Simple and intuitive controls
- 🔄 **Restart Anytime** - Easy reset to play multiple rounds
- 📖 **Built-in Help** - Learn rules instantly

### 🧠 AI Features
- **Smart Memory** - AI remembers card positions it has seen
- **Strategic Matching** - AI finds matches when it has enough information
- **Adaptive Play** - AI improves as more cards are revealed
- **Fair Gameplay** - Natural thinking delays make it feel human-like

---

## 🎯 How to Play

### Game Rules

#### Two-Player Mode
1. **Setup** - Cards are arranged in a grid, all facing down
2. **Take Turns** - Players alternate turns, starting with Player 1
3. **Flip Cards** - Click on any two cards to reveal them
4. **Match Making** - If the cards match, they stay face-up and you get a point!
5. **No Match** - If cards don't match, they flip back over
6. **Keep Memory** - Remember card positions to find matches faster
7. **Win** - The player with the most matches when all cards are revealed wins!

#### AI Mode
1. **Challenge the AI** - Click "🤖 Play AI" to start
2. **Your Turn** - Click cards to find matches and earn points
3. **AI's Turn** - Watch as the AI uses smart strategy to find pairs
4. **AI Learning** - The more cards revealed, the smarter the AI becomes
5. **Win** - Beat the AI by finding more matches!

### Winning Strategy

```
TURN SEQUENCE (2-Player):
┌─────────────────────────────────────┐
│ Player 1 → Flip 2 cards             │
│   ├─ MATCH: +1 Point, stays flipped │
│   └─ NO MATCH: Cards flip back      │
│                                     │
│ Player 2 → Flip 2 cards             │
│   ├─ MATCH: +1 Point, stays flipped │
│   └─ NO MATCH: Cards flip back      │
│ ... Continue until all pairs found  │
└─────────────────────────────────────┘

AI STRATEGY (AI Mode):
┌──────────────────────────────────────┐
│ Your Turn → Flip cards               │
│   ├─ MATCH: +1 Point, another turn   │
│   └─ NO MATCH: AI's turn             │
│                                      │
│ AI's Turn → Uses memory to find      │
│   ├─ Matches known pairs (optimal)   │
│   ├─ Or makes smart guesses          │
│   └─ Learns new card positions       │
└──────────────────────────────────────┘
```

---

## 🚀 Getting Started

### Prerequisites

✅ Any modern web browser (Chrome, Firefox, Safari, Edge)  
✅ No installation or downloads needed!  
✅ Works offline after loading

### Installation & Running

**Option 1: Direct File Opening**
```bash
1. Download or clone the repository
2. Double-click index.html
3. The game opens in your default browser
```

**Option 2: Clone from GitHub**
```bash
git clone https://github.com/krishkr-ctl/Memory_game.git
cd Memory_game
# Open index.html in your browser
```

**Option 3: Using GitHub Pages**
- Visit: `https://krishkr-ctl.github.io/Memory_game/`

---

## 📁 Project Structure

```
Memory_game/
│
├── 📄 index.html          # Main game file (HTML, CSS, and JS combined)
├── 📖 README.md           # This file
└── 📚 docs/               # Additional documentation
    ├── FEATURES.md        # Detailed feature list
    ├── AI_STRATEGY.md     # AI algorithm explanation
    └── CUSTOMIZATION.md   # Customization guide
```

---

## 🎮 Game Controls

| Action | Method | Two-Player | AI Mode |
|--------|--------|------------|---------|
| **Flip a Card** | Click on card | ✅ | ✅ (Your turn) |
| **Switch Mode** | Click mode button | ✅ | ✅ |
| **Restart Game** | Click "Restart" button | ✅ | ✅ |
| **Get Help** | Click "Help" button | ✅ | ✅ |
| **View Score** | See score display | ✅ | ✅ |

---

## 🛠️ Technologies Used

```
┌─────────────────────────────────────┐
│        TECHNOLOGY STACK             │
├─────────────────────────────────────┤
│ Frontend:                           │
│  • HTML5 - Structure & Markup       │
│  • CSS3 - Styling & Animations      │
│  • JavaScript (ES6+) - Game Logic   │
│                                     │
│ Core Features:                      │
│  • DOM Manipulation                 │
│  • Event Listeners                  │
│  • CSS Transitions & Transforms     │
│  • Array Methods & Shuffling        │
│  • AI Algorithm (Memory + Strategy) │
└─────────────────────────────────────┘
```

---

## 💡 Pro Tips to Win

### Against a Friend (2-Player)
1. **👀 Focus & Memory**
   - Concentrate on card positions
   - Build a mental map of the grid

2. **📍 Strategic Approach**
   - Start from corners (easier to remember)
   - Work systematically through the board

3. **⏱️ Timing**
   - Don't rush - take your time
   - Quick but deliberate moves

### Against AI (AI Mode)
1. **🎯 Early Advantage**
   - Make your first move quickly
   - You see cards before the AI starts learning

2. **🧠 Pattern Recognition**
   - Look for visual patterns in emojis
   - Group similar cards mentally

3. **🤖 Exploit AI Weakness**
   - When AI hasn't seen enough cards, guess strategically
   - Once AI learns positions, focus on finding new pairs

4. **🎪 Practice**
   - Play multiple rounds
   - Learn the AI's patterns
   - Improve your own memory!

---

## 🎨 Customization Guide

### Change Card Emojis
Edit the emojis array in the JavaScript section:
```javascript
const emojis = ['🍎', '🍌', '🍒', '🍇', '🥝', '🍍', '🍉', '🍓'];
// Change to your favorite emojis!
// const emojis = ['🐶', '🐱', '🐭', '🐹', '🐰', '🦊', '🐻', '🐼'];
```

### Change Colors & Styling
Edit the CSS variables:
```css
:root {
  --bg: #07111f;              /* Background color */
  --panel: #10233b;           /* Panel background */
  --accent: #4dd0e1;          /* Primary accent */
  --accent-2: #7b61ff;        /* Secondary accent */
  --text: #f5f7fb;            /* Text color */
  --muted: #9cb8c9;           /* Muted text */
  --success: #38d39f;         /* Success color */
}
```

### Adjust AI Difficulty
Modify AI behavior by editing the AI strategy in the `aiTurn()` function:
```javascript
// Make AI harder: Increase memory utilization
// Make AI easier: Add more random guesses
```

### Create Different Themes
- **🐶 Animals Theme** - Use animal emojis
- **🎭 Movie Theme** - Use movie character emojis
- **⚽ Sports Theme** - Use sports emojis
- **🌸 Nature Theme** - Use nature emojis

---

## 🤝 Contributing

We welcome contributions! Here are ways you can help:

### Feature Ideas
- 🔊 **Sound Effects** - Add audio feedback
- 🎪 **Different Themes** - Create themed card sets
- 📊 **Difficulty Levels** - Easy, Medium, Hard modes
- ⏱️ **Timer Mode** - Race against time
- 🏅 **Leaderboard** - Track high scores
- 🌐 **Online Multiplayer** - Play with friends online
- 📊 **Statistics** - Track game history

### How to Contribute
```bash
1. Fork the repository
2. Create a feature branch (git checkout -b feature/amazing-feature)
3. Make your changes
4. Commit your changes (git commit -m 'Add amazing feature')
5. Push to the branch (git push origin feature/amazing-feature)
6. Open a Pull Request
```

---

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| **Page won't load** | Check file path, ensure index.html is in root directory |
| **Cards not flipping** | Clear browser cache (Ctrl+Shift+Delete), refresh page |
| **AI not playing** | Ensure game mode is set to "🤖 Play AI", refresh page |
| **Styles not applying** | Verify CSS is embedded correctly in index.html |
| **Game freezes** | Reload page, check browser console for errors |
| **Mobile issues** | Rotate device, check viewport settings |

---

## 📊 Game Statistics Example

```
SAMPLE GAMEPLAY (AI Mode):
─────────────────────────────────────
Round: 1/1
Total Moves: 14
Total Matches: 8

Your Score: 5 Matches ⭐
AI Score: 3 Matches 🤖
Winner: You! 🏆

Cards Remaining: 0/16
Game Status: Complete! ✅
─────────────────────────────────────
```

---

## 📝 License

This project is open source and available under the **MIT License**.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🎉 Have Fun Playing!

This game is designed to bring joy and challenge to you, your friends, and the AI. Test your memory, have fun, and may the best memory win!

```
╔═══════════════════════════════════════╗
║                                       ║
║    🎮 Ready to Play? 🎮              ║
║    Challenge Your Friend or AI!      ║
║                                       ║
║      Good Luck! 🍀 Have Fun! 🎉     ║
║                                       ║
╚═══════════════════════════════════════╝
```

---

## 📧 Support & Contact

- **Author:** [krishkr-ctl](https://github.com/krishkr-ctl)
- **Repository:** [Memory_game](https://github.com/krishkr-ctl/Memory_game)
- **Report Issues:** [GitHub Issues](https://github.com/krishkr-ctl/Memory_game/issues)
- **Questions?** Open an issue or start a discussion

---

## ⭐ Show Your Support

If you enjoyed this game, please:
- ⭐ **Star** this repository
- 🍴 **Fork** it for your own customizations
- 📢 **Share** with your friends
- 💬 **Leave feedback** via issues

---

## 🎓 Learning Resources

Want to build similar projects? Check out:
- [MDN Web Docs - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [CSS Animations & Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations)
- [Game Development Basics](https://developer.mozilla.org/en-US/docs/Games)
- [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)

---

**Last Updated:** July 23, 2026  
**Version:** 2.0 (Now with AI!)  
**Status:** Active ✅
