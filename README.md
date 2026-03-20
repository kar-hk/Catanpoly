# 🏝️ Catanpoly

A real-time multiplayer implementation of the classic **Settlers of Catan** board game, built with **React** and **Socket.io**.  
Customized, maintained, and deployed by **Hanishkar & Teaam **.

![Catan](https://img.shields.io/badge/Players-2--6-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## ✨ Features

- **Full Game Rules** – Complete implementation of official Catan rules  
- **Multiplayer** – Play with 2–6 friends online in real-time  
- **5–6 Player Extension** – Larger board with Special Building Phase  
- **Trading System** – Player-to-player trades, bank trades (4:1), and port trades (3:1 / 2:1)  
- **Development Cards** – Knights, Victory Points, Road Building, Year of Plenty, Monopoly  
- **Dynamic Board** – Shuffle and preview board before starting  
- **Interactive UI** – Right-click any element for helpful info  
- **Responsive Design** – Dark theme with smooth animations  

---

## 🎮 How to Play

1. **Create or Join** – One player creates a game and shares the 6-letter code  
2. **Setup Phase** – Each player places 2 settlements and 2 roads  
3. **Main Game** – Roll dice, collect resources, build, and trade  
4. **Win** – First player to reach **10 Victory Points** wins!

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- npm

### Run Locally

```bash
git clone https://github.com/kar-hk/catanpoly.git
cd catanpoly

cd server
npm install
npm start

cd ../client
npm install
npm run dev
```

Open in browser:
```
http://localhost:5173
```

---

## 🌐 Deployment

>  Live deployment is added: https://ca-tan-gold.vercel.app/.  
You can deploy using:
- **Frontend:** Vercel  
- **Backend:** Render / Railway  

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| Frontend | React, Vite |
| Backend | Node.js, Express |
| Real-time | Socket.io |
| Styling | CSS3 |

---

## 🎯 Game Rules Quick Reference

| Building | Cost | Victory Points |
|----------|------|----------------|
| Road | 🧱 🪵 | 0 |
| Settlement | 🧱 🪵 🐑 🌾 | 1 |
| City | ⛏️⛏️⛏️ 🌾🌾 | 2 |
| Dev Card | ⛏️ 🌾 🐑 | ? |

**Bonus VP:**  
- Longest Road (5+) = 2 VP  
- Largest Army (3+ Knights) = 2 VP  

---

## 👤 Maintainer

**kar-hk**  
GitHub: https://github.com/kar-hk  

---

## 📄 License

MIT License – See [LICENSE](LICENSE) for details.

---

## ⚠️ Disclaimer

This is an **independent fan-made project** for **educational purposes only**.  
It is **NOT affiliated with, endorsed by, or connected to**:

- Catan GmbH  
- Catan Studio  
- Asmodee  

**"Catan" is a registered trademark of Catan GmbH.**  
For the official game, visit: https://www.catan.com/
