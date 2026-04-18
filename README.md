# 🃏 Pro Poker: Professional Betting Rounds

A fully interactive browser-based poker game featuring betting rounds, AI opponents, animated UI, and realistic card rendering.

---

## 🎮 Features

- **3-Player Poker Gameplay**
  - You vs 2 AI bots
- **Multiple Betting Rounds**
  - Pre-draw betting
  - Final betting phase
- **Card Replacement System**
  - Hold and redraw cards like classic draw poker
- **Advanced Hand Evaluation**
  - Detects all major poker hands (Pair → Royal Flush)
- **AI Opponents**
  - Adjustable difficulty (Easy / Hard)
  - Bluffing and risk-based decision-making
- **Level Progression System**
  - Increasing difficulty per level
  - Tournament-style advancement
- **Bankroll System**
  - Start with $500
  - Go bankrupt or become champion
- **High Score Tracking**
  - Saved via `localStorage`
- **Custom Card Rendering**
  - SVG-based cards with:
    - Face card artwork
    - Pip layouts
    - Suit coloring
- **Confetti Win Animation 🎉**
- **Bet Slider + Quick Bet Buttons**
- **Odds Calculator**
  - Estimates improvement chances during draw phase

---

## 🕹️ How to Play

1. Select difficulty  
2. Click **DEAL**  
3. Choose your action:
   - Fold  
   - Check/Call  
   - Raise (use slider or quick buttons)  
4. Select cards to **HOLD**  
5. Click **REPLACE CARDS**  
6. Final betting round  
7. Showdown determines the winner  

---

## 🧠 Game Mechanics

### Hand Rankings (High → Low)

- Royal Flush  
- Straight Flush  
- Four of a Kind  
- Full House  
- Flush  
- Straight  
- Three of a Kind  
- Two Pair  
- One Pair  
- High Card  

### AI Behavior

Bots make decisions based on:
- Hand strength  
- Risk tolerance (`riskMod`)  
- Bluff probability (`bluffProb`)  
- Current bet size  

---

## 📁 Project Structure
