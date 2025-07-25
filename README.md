# 🐳 docker-egg-pm2

📦 Official Pterodactyl Egg for Node.js with PM2  
Simplifies running Node.js apps with PM2 in a Docker environment.

---

![Logs Preview](https://camo.githubusercontent.com/f0982bca523bc95c6b56f6fada66b44298ecc39c3bf73a1363c38fc00f426625/68747470733a2f2f66696c65732e636174626f782e6d6f652f646d7a32666e2e6a7067)

---

## 📁 Available Versions

> Choose the appropriate version of Node.js with PM2 from below:

| Node.js Version | Docker Image |
|------------------|---------------------------|
| [Node.js 14](/17) | `ghcr.io/RexxHayanasi/nodejspm2:14` |
| [Node.js 16](/18) | `ghcr.io/RexxHayanasi/nodejspm2:16` |
| [Node.js 18](/19) | `ghcr.io/RexxHayanasi/nodejspm2:18` |
| [Node.js 19](/20) | `ghcr.io/RexxHayanasi/nodejspm2:19` |

---

## 🚫 Unsupported

❌ Node.js **12** is not supported with PM2 due to incompatibilities and EOL (End of Life).

---

## 📌 Notes

- This egg uses a custom entrypoint to handle `startup` commands via Pterodactyl's `STARTUP` variable.
- Fully supports PM2 process manager.
- Make sure to define your entry script (e.g., `ecosystem.config.js` or `pm2 start index.js`) in the startup command.

---

## 🛠️ Credits

Maintained by **[@RexxHayanasi](https://github.com/RexxHayanasi)**  
Feel free to open issues or PRs for improvements!
