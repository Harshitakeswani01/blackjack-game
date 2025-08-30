# 🃏 Blackjack Game  

A simple Python implementation of the classic Blackjack card game.  

---

## 🎮 How to Play  

1. Create and shuffle a deck of 52 cards.  
2. Player places a bet (cannot exceed available chips).  
3. Deal two cards each to Player and Dealer:  
   - One Dealer card is hidden.  
   - Both Player cards are visible.  
4. Player chooses to:  
   - **Hit** → Take another card.  
   - **Stand** → End their turn.  
5. If the Player goes over 21 → **Bust** (automatic loss).  
6. If Player stands → Dealer reveals cards and keeps hitting until reaching at least 17.  
7. Compare values:  
   - Closest to **21 wins**.  
   - Tie → "Push".  
8. Adjust Player’s chips based on the result.  
9. Ask if the Player wants to play again.  

---

## 🂡 Card Rules  

- **2–10** → Face value.  
- **Jack, Queen, King** → 10 points each.  
- **Ace** → 1 or 11 (whichever helps the hand).  

---

## 📂 Project Structure  

```
Blackjack/
│── blackjack.py   # Main game logic
│── README.md      # Project description
```

---

## ▶️ Run the Game  

```bash
python blackjack.py
```

---

## ✨ Features  

- Betting system with chips 💰  
- Dealer follows real Blackjack rules 🤵  
- Ace automatically adjusts value (1 or 11)  
- Option to replay after each round  

---

## 📌 Future Improvements  

- Add multiplayer support 👥  
- GUI version 🎨  
- Save player stats 📊  

---
