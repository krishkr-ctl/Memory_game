# 🎮 Memory Game with Friend

A fun and interactive memory card matching game built with **HTML, CSS, and JavaScript**. Challenge your friend and test your memory skills!

![Memory Game](https://img.shields.io/badge/Game-Memory-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34C26?logo=html5&logoColor=white) ![License](https://img.shields.io/badge/License-MIT-green)

---

## 📋 Overview

**Memory Game with Friend** is a classic two-player matching card game where players flip cards to find identical pairs. It's designed for playing with a friend on the same device and provides an entertaining, brain-boosting challenge!

```
┌────────────────────────────────────────┐
│     🎮 MEMORY GAME WITH FRIEND 🎮      │
│                                        │
│   ┌─────┐  ┌─────┐  ┌─────┐ ┌─────┐  │
│   │  🎨  │  │  ?  │  │  🎮  │  │  ?  │  │
│   └─────┘  └─────┘  └─────┘ └─────┘  │
│                                        │
│   ┌─────┐  ┌─────┐  ┌─────┐ ┌─────┐  │
│   │  ?  │  │  ⭐  │  │  ?  │  │  🎯 │  │
│   └─────┘  └─────┘  └─────┘ └─────┘  │
│                                        │
│   👤 Player 1: 5 Matches  │ Player 2: 4 │
│                                        │
│          🔄 NEW GAME   🏆 SCORE       │
└────────────────────────────────────────┘
```

---

## ✨ Features

- 🎲 **Interactive Card Flipping** - Click to reveal hidden cards
- 👥 **Two-Player Mode** - Play with a friend on the same device
- 🏆 **Score Tracking** - Automatic match counting and game statistics
- 🎨 **Responsive Design** - Works on desktop, tablet, and mobile devices
- ⚡ **Smooth Animations** - Beautiful card flip and transition effects
- 🔄 **Restart Anytime** - Easy reset to play multiple rounds
- 🎯 **Turn-Based Gameplay** - Automatic player switching
- 📱 **User-Friendly Interface** - Simple and intuitive controls

---

## 🎯 How to Play

### Game Rules

1. **Setup** - Cards are arranged in a grid, all facing down
2. **Take Turns** - Players alternate turns, starting with Player 1
3. **Flip Cards** - Click on any two cards to reveal them
4. **Match Making** - If the cards match, they stay face-up and you get a point!
5. **No Match** - If cards don't match, they flip back over
6. **Keep Memory** - Remember card positions to find matches faster
7. **Win** - The player with the most matches when all cards are revealed wins!

### Winning Strategy

```
TURN SEQUENCE:
Player 1 → Flip 2 cards
  ├─ MATCH: +1 Point, stays flipped
  └─ NO MATCH: Cards flip back
Player 2 → Flip 2 cards
  ├─ MATCH: +1 Point, stays flipped
  └─ NO MATCH: Cards flip back
... Continue until all pairs found ...
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
git clone https://github.com/krishkr-ctl/Memory_game_with_friend.git
cd Memory_game_with_friend
# Open index.html in your browser
```

**Option 3: Using GitHub Pages**
- Visit: `https://krishkr-ctl.github.io/Memory_game_with_friend/`

---

## 📁 Project Structure

```
Memory_game_with_friend/
│
├── 📄 index.html          # Main game file (HTML structure & embedded CSS/JS)
├── 🎨 styles.css          # Styling & animations (optional, if separate)
├── ⚙️ script.js            # Game logic & functionality (optional, if separate)
├── 📖 README.md           # This file
└── 📁 assets/             # Optional folder for images & sounds
    ├── 🖼️ images/
    │   ├── card-back.png
    │   ├── card-1.png
    │   └── ...
    └── 🔊 sounds/
        ├── flip.mp3
        ├── match.mp3
        └── win.mp3
```

---

## 🎮 Game Controls

| Action | Method |
|--------|--------|
| **Flip a Card** | Click on any card face-down |
| **New Game** | Click "New Game" or "Restart" button |
| **Check Score** | View score display during gameplay |
| **Switch Player** | Automatic (or click "Next Turn") |

---

## 🛠️ Technologies Used

```
┌─────────────────────────────────────┐
│        TECHNOLOGY STACK             │
├─────────────────────────────────────┤
│ Frontend:                           │
│  • HTML5 - Structure & Markup       │
│  • CSS3 - Styling & Animations      │
│  • JavaScript - Game Logic          │
│                                     │
│ Features:                           │
│  • DOM Manipulation                 │
│  • Event Listeners                  │
│  • CSS Transitions & Transforms     │
│  • LocalStorage (optional)          │
└─────────────────────────────────────┘
```

---

## 💡 Pro Tips to Win

1. **👀 Focus & Memory**
   - Concentrate on card positions
   - Build a mental map of the grid

2. **📍 Strategic Approach**
   - Start from corners (easier to remember)
   - Work systematically through the board

3. **⏱️ Timing**
   - Don't rush - take your time
   - Quick but deliberate moves

4. **🧠 Pattern Recognition**
   - Look for visual patterns
   - Group similar cards mentally

5. **🎯 Practice**
   - Play multiple rounds
   - Your memory improves with practice!

---

## 🎨 Customization Guide

Want to personalize your game? Here's how:

### Change Grid Size
```javascript
// In script.js, modify:
const GRID_SIZE = 4; // 4x4 = 16 cards (change to 3, 5, 6, etc.)
```

### Change Card Images
1. Create image files for your cards
2. Place them in `/assets/images/`
3. Update the image sources in JavaScript

### Change Colors & Styling
Edit `styles.css` or `index.html <style>` tag:
```css
.card {
    background-color: #4CAF50;  /* Change card color */
    border-color: #2196F3;      /* Change border */
}
```

### Add Sound Effects
Include audio elements and play them on events:
```javascript
const flipSound = new Audio('assets/sounds/flip.mp3');
flipSound.play();
```

### Create Different Themes
- **Animals Theme** - Use animal emojis or images
- **Emoji Theme** - Use fun emojis for cards
- **Movie Theme** - Use movie character images
- **Sports Theme** - Use sports icons

---

## 🤝 Contributing

We welcome contributions! Here are ways you can help:

### Feature Ideas
- 🔊 **Sound Effects** - Add audio feedback
- 🎪 **Different Themes** - Create themed card sets
- 📊 **Difficulty Levels** - Easy, Medium, Hard modes
- 🤖 **AI Opponent** - Play against computer
- 🌐 **Online Multiplayer** - Play with friends online
- ⏱️ **Timer Mode** - Race against time
- 🏅 **Leaderboard** - Track high scores

### How to Contribute
```bash
1. Fork the repository
2. Create a feature branch (git checkout -b feature/amazing-feature)
3. Make your changes
4. Commit (git commit -m 'Add amazing feature')
5. Push (git push origin feature/amazing-feature)
6. Open a Pull Request
```

---

## 📊 Game Statistics

```
SAMPLE GAMEPLAY:
─────────────────────────────
Round: 1/1
Total Moves: 12
Total Matches: 8

Player 1 Score: 5 Matches ⭐
Player 2 Score: 3 Matches
Winner: Player 1 🏆

Cards Remaining: 0/16
Game Status: Complete! ✅
─────────────────────────────
```

---

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| **Page won't load** | Check file path, ensure index.html is in root directory |
| **Cards not flipping** | Clear browser cache, refresh page |
| **Styles not applying** | Verify CSS is embedded or linked correctly |
| **Game freezes** | Reload page, check browser console for errors |
| **Mobile issues** | Use responsive design, check viewport settings |

---

## 📝 License

This project is open source and available under the **MIT License**.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limited the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🎉 Have Fun Playing!

This game is designed to bring joy and challenge to you and your friend. Test your memory, have fun, and may the best memory win!

```
╔═══════════════════════════════════════╗
║                                       ║
║    🎮 Ready to Play? 🎮              ║
║    Challenge Your Friend Today!      ║
║                                       ║
║      Good Luck! 🍀 Have Fun! 🎉     ║
║                                       ║
╚═══════════════════════════════════════╝
```

---

## 📧 Support & Contact

- **Author:** [krishkr-ctl](https://github.com/krishkr-ctl)
- **Repository:** [Memory_game_with_friend](https://github.com/krishkr-ctl/Memory_game_with_friend.)
- **Report Issues:** [GitHub Issues](https://github.com/krishkr-ctl/Memory_game_with_friend./issues)
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
- [HTML5 Game Development](https://html5.org/)

---

**Last Updated:** July 2, 2026  
**Version:** 1.0  
**Status:** Active ✅
