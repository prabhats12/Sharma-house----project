# 🍛 Sharmahouse — Restaurant Website

A full-featured 3D restaurant website with live kitchen streaming, online ordering, and payment integration.

---

## 🚀 How to Run in VS Code

### Option 1 — Easiest: Live Server (No Node needed)

1. Open VS Code
2. Open this folder: **File → Open Folder → select `Sharmahouse-project`**
3. Install the **Live Server** extension (VS Code will prompt you, or search it in Extensions tab)
4. Right-click on `index.html` in the file explorer
5. Click **"Open with Live Server"**
6. Browser opens automatically at `http://127.0.0.1:5500`  ✅

---

### Option 2 — Node.js Server

#### Step 1 — Install Node.js (if you don't have it)
Download from: https://nodejs.org  (choose LTS version)

#### Step 2 — Open Terminal in VS Code
Press **Ctrl + `** (backtick) to open the terminal

#### Step 3 — Run the server
```bash
node server.js
```

#### Step 4 — Open in browser
Go to: **http://localhost:3000**  ✅

---

### Option 3 — npm start

```bash
npm start
```

---

### Option 4 — VS Code Debugger (F5)

1. Open VS Code
2. Press **F5** or go to **Run → Start Debugging**
3. Select **"🍛 Run Sharmahouse Server"**
4. Open browser at: **http://localhost:3000**  ✅

---

## 📁 Project Files

```
sharmahouse-project/
├── index.html        ← Main website (all-in-one)
├── server.js         ← Node.js local server
├── package.json      ← Project config
├── README.md         ← This file
└── .vscode/
    ├── launch.json   ← F5 debug config
    ├── settings.json ← Editor settings
    └── extensions.json ← Recommended extensions
```

---

## 🔐 Demo Login Credentials

| Role | Username | Password |
|------|----------|----------|
| Restaurant Owner | `admin` | `admin123` |
| Customer | `user1` | `pass123` |

Or click **Register** to create your own account — it's saved automatically.

---

## ✨ Features

- 🍛 **Full Menu** — 40+ dishes across 10 categories with real photos
- 🛒 **Cart & Ordering** — Add items, adjust quantities, place orders
- 💳 **Payments** — UPI, Paytm, Card, Net Banking, Cash on Delivery
- 📹 **Live Kitchen** — Embed YouTube Live stream for customers to watch
- 🛵 **Order Tracking** — Real-time status from Placed → Cooking → Delivered
- 👨‍🍳 **Owner Dashboard** — Manage orders, users, revenue stats
- 📊 **Excel Export** — Download all orders & users as `.xls`
- 🔒 **Persistent Login** — Stay logged in across sessions (localStorage)
- 📱 **Mobile Friendly** — Works on phones and tablets

---

## 📝 Customization

Open `index.html` in VS Code and search for:

- **Restaurant name**: search `Sharmahouse`
- **Phone number**: search `1234565678`
- **Address**: search `Chandni Chowk`
- **Social links**: search `footer-socials`
- **Menu items**: search `// ── STARTERS ──`
- **Prices**: search `price:` in the menu array

---

## 💡 Tips

- **localStorage** stores all user accounts and orders in your browser
- To reset all data: open browser DevTools → Application → Local Storage → clear `sl_db`
- The live kitchen stream needs a YouTube Live embed URL (get from YouTube Studio)

---

Built with ❤️ — Pure HTML, CSS & JavaScript. No frameworks needed.
