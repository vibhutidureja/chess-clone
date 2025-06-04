# ♟️ Chess.com Clone

A real-time multiplayer online chess game built with **Node.js**, **Socket.io**, and **Chess.js** — inspired by the gameplay of [chess.com](https://www.chess.com/). This clone supports two-player matches, drag-and-drop moves, and spectator view.

## 🚀 Features

- Real-time multiplayer chess
- Drag-and-drop UI for moving pieces
- Player roles assigned automatically (white, black, or spectator)
- Game state synced across players using WebSockets
- Spectators can watch live matches
- Elegant UI using **Tailwind CSS**
- Server-side validation of chess moves using **chess.js**

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS (Tailwind), JavaScript
- **Backend:** Node.js, Express.js
- **WebSockets:** Socket.io
- **Game Engine:** Chess.js

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/c38b4098-ca63-458e-9615-258316a69a2a)


## 🧩 Installation

### 1. Clone the repo

```bash
git clone https://github.com/vibhutidureja/chess-clone.git
cd chess-clone
2. Install dependencies
npm install express socket.io chess.js jsonwebtoken cookie-parser bcrypt
3. Start the server
npx nodemon
Visit http://localhost:3000 in two different tabs or devices to play!

🌐 How it Works
The first user to join becomes White, second becomes Black, others are Spectators.

Moves are validated server-side using chess.js.

Board updates are broadcast via Socket.io to all clients.

Drag-and-drop support makes moving pieces easy.

📁 Folder Structure
node_modules
/public
  └── css                # Custom styles (if any)
  └── js/chessgame.js    # Client-side logic

/views
  └── index.ejs          # EJS Template

app.js                # Express + Socket.io backend
README.md
.gitignore
package-lock.json
package.json

🙌 Contributions
Pull requests and feedback are welcome! Feel free to fork this repo, play around, or suggest improvements.

📄 License
This project is open-source and available under the MIT License.

📬 Contact
Author: Vibhuti Dureja
GitHub: @vibhutidureja
