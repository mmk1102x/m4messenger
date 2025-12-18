# 🛰️ M4messenger

**M4messenger** is a high-performance, decentralized, serverless peer-to-peer (P2P) messaging application. It is designed to be truly private—data lives in the collective browsers of the users, not on a central server.

---

## ✨ Key Features

- **🌐 Serverless P2P:** Powered by Gun.js. No central database. Every user who opens the site helps host the data.
- **💾 Local Persistence:** Uses your browser's LocalStorage and IndexedDB to keep chat history alive even when everyone is offline.
- **🎨 Chromatic Themes:** Switch between `Dark`, `Light`, `Midnight`, `Emerald`, `Amber`, and the unique `Text` (ASCII) theme.
- **📱 Mobile Optimized:** Dynamic viewport height (100dvh) ensures the chat works perfectly on all mobile browsers.
- **🤫 Personal Aliases:** Type `nick @user Name` to rename other people locally.
- **🧼 Privacy First:** The `clean` command performs a full "Factory Reset" by wiping all storage and cookies.

---

## 🛠️ Command System

Run these commands in the **RUN** box at the bottom-left. Use `;` to run multiple at once.

| Command | Description |
| :--- | :--- |
| `stats` | Opens a window showing your usage time and mesh network status. |
| `theme` | Opens the visual Theme Picker. |
| `clean` | **Factory Reset:** Wipes all messages, cookies, and local data. |
| `exp` | Toggle Aesthetic UI (Glassmorphism & Blurs). |
| `soft` | Toggle rounded corners for a modern look. |
| `snow` | Toggle falling snowflake animation. |
| `rus / eng` | Switch interface language. |
| `nick @user Name` | Set a personal nickname for another user. |
| `default [cmds]` | (Admin) Set startup commands for all new users. |

---

## 🚀 How to Run

Because M4messenger is **Serverless**, you have three ways to use it:

1. **GitHub Pages (Live):** [https://mmk1102x.github.io/m4messenger/](https://mmk1102x.github.io/m4messenger/)
2. **Instant Local:** Download `index.html` and double-click it. It will work immediately.
3. **Python Serving:** Run `python3 app.py` to serve the file locally on port 5000.

---

## 🛡️ Privacy & Cookies

M4messenger uses **Local Storage** and **Cookies** strictly for decentralized functionality:
1. To store your cryptographic identity keys.
2. To cache chat history so the mesh stays alive during low traffic.
3. To remember your theme and language settings.

---
**Developed for the M4 Community.**
