# 🛰️ M4messenger

**M4messenger** is a high-performance, decentralized, peer-to-peer (P2P) messaging application designed to run anywhere—from high-end modern workstations to older legacy PCs and mobile devices.

By leveraging **Mesh Network** technology, M4messenger removes the need for a central server. Every user who opens the app helps host the network, ensuring 100% uptime and true data privacy.

---

## ✨ Key Features

- **🌐 Decentralized Mesh:** Powered by Gun.js. Data lives in the collective browsers of the users, not a single database.
- **🎨 Chromatic Themes:** Switch between `Dark`, `Light`, `Midnight`, `Emerald`, and the unique `Text` theme.
- **📟 Symbol Mode (`text`):** A retro-hacker mode using only ASCII characters (`|` and `_`) for all borders and UI elements.
- **📱 Mobile First:** Fully responsive design with an intelligent sidebar for small screens.
- **🤫 Personal Aliases:** Rename any user locally. Only you see the nickname, while keeping their original `@username` visible.
- **⚡ Performance Core:** Optimized CSS and JS for ultra-low RAM usage.
- **🇷🇺 Multi-Language:** Full support for English and Russian interfaces.

---

## 🛠️ Command System

M4messenger features a built-in **Command Executor** (located in the bottom-left). You can run multiple commands at once using a semicolon (`;`).

| Command | Description |
| :--- | :--- |
| `stats` | View system status, global defaults, and session time. |
| `theme` | Open the visual Theme Picker. |
| `exp` | Toggle Aesthetic UI (Glassmorphism & Blurs). |
| `soft` | Toggle rounded corners for a modern look. |
| `snow` | Toggle falling snowflake effects. |
| `rus / eng` | Switch interface language. |
| `nick @user Name` | Set a personal nickname for another user. |
| `cleaner` | Wipe the local chat screen. |
| `default [cmds]` | (Admin) Set startup commands for all new users. |

---

## 🚀 Installation & Local Setup

While M4messenger is hosted on GitHub Pages, you can run your own local node using Python:

1. **Clone the repo:**
   ```bash
   git clone https://github.com/mmk1102x/m4messenger.git
   cd m4messenger
