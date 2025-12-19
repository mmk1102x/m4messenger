# M4messenger

**M4messenger** is a serverless, decentralized, Peer-to-Peer (P2P) messaging application powered by **Gun.js**. Designed with a "Performance First" philosophy, it runs entirely in the browser without a backend database.

## 🚀 Core Features

- **Decentralized:** No central server. Data lives in the mesh (Gun.js).
- **No Authentication:** No sign-ups. Identity is generated locally and stored in the browser.
- **Performance First:** Optimized for legacy hardware. Vanilla JS, no heavy frameworks.
- **Global Directory:** View all users in the mesh history with **Online/Offline** status indicators.
- **Dynamic Theming:** 10+ themes with automatic favicon adaptation.
- **Keyboard Accessible:** Full keyboard navigation support with high-contrast focus states.

## ⌨️ Hotkeys & Accessibility

M4messenger is fully usable without a mouse.

| Shortcut | Action |
| :--- | :--- |
| `Alt + C` | Focus **Chat Input** |
| `Alt + M` | Focus **Command Line** |
| `Alt + R` | Focus **Room List** |
| `Esc` | Close Modals / Return to Input |
| `Tab` | Navigate Lists (Rooms/Users) |
| `Enter` | Select List Item / Send Message |

## 💻 Commands

Type these into the Command Bar (bottom of sidebar) or press `Alt + M`:

| Command | Description |
| :--- | :--- |
| `name [NewName]` | Change your display name instantly. |
| `theme` | Open the visual Theme Picker. |
| `clean` | **Factory Reset** (Wipes data & reloads). |
| `soft` | Toggle UI Border Radius (0px vs 18px). |
| `snow` | Toggle the global snowflake animation. |
| `help` | Show list of commands. |
| `stats` | Show network connectivity stats. |
| `nick @u [Name]` | Set a local alias for a peer. |
| `rus` / `eng` | Switch interface language. |

## 🎨 Themes

M4messenger supports universal CSS variables. The **browser tab icon** updates dynamically to match the active theme color.

- **Light / Dark** (Standard)
- **Coffee** (Latte/Paper) / **Coffee-Dark** (Espresso)
- **Emerald** (Hacker Green)
- **Midnight** (Deep Blue OLED)
- **Crimson, Purple, Blue, Solarized, Amber**

## 🛠 Technical Stack

- **Engine:** [Gun.js](https://gun.eco/) (RAD, SEA).
- **Storage:** IndexedDB / LocalStorage (Browser).
- **Frontend:** Pure HTML/CSS/JS (Single File).
- **Network:** WebRTC + Relay Fallback.

## 📦 Installation

1. Clone the repo.
2. Open `index.html` in any modern browser.
3. That's it.

# //all code is written by ai. don't belive it too much.
