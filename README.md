# 🎵 Antakshari Game

A web-based Antakshari game that allows players to take turns submitting words based on the last letter of the previous word. The game keeps track of scores and maintains a leaderboard.

## 📂 Project Structure
```
📁 Project Root
 ├── 📄 index.html           # Main game interface
 ├── 📄 leaderboard.html     # Leaderboard page
 ├── 📄 server.js           # Backend server (Node.js + Express)
 ├── 📄 style.css           # Styles for the game (not included in the provided files)
 ├── 📄 script.js           # Client-side JavaScript (not included in the provided files)
 ├── 📂 public/             # Public assets (if needed)
 ├── 📂 node_modules/       # Dependencies (installed via npm)
 ├── 📄 package.json        # Project metadata & dependencies
 ├── 📄 README.md           # Project documentation
```

## 🚀 Features
- 🎮 Start a new game with randomly chosen words.
- 🔠 Players must enter words starting with the last letter of the previous word.
- 🚫 Words cannot be repeated.
- 📊 Scores are updated based on word length.
- 🏆 View a real-time leaderboard.

## 🛠️ Technologies Used
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express  
- **Database**: MongoDB  
- **Additional Libraries**: Mongoose (for MongoDB), Body-parser, CORS  

## 📦 Installation & Setup
### Prerequisites
Ensure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed.

### Steps
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo-url.git
   cd your-repo-folder
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start MongoDB server (if not already running):
   ```sh
   mongod
   ```
4. Run the application:
   ```sh
   node server.js
   ```
5. Open your browser and go to:
   ```sh
   http://localhost:3000
   ```

## 📜 API Endpoints
| Method | Endpoint        | Description |
|--------|---------------|-------------|
| `GET`  | `/start`      | Starts a new game |
| `POST` | `/submit`     | Submit a new word |
| `GET`  | `/leaderboard` | Get player rankings |

## 🎯 How to Play?
1. Click "Start Game" to begin.
2. Enter a word that starts with the last letter of the current word.
3. If valid, your score increases; if invalid, points are deducted.
4. Check rankings on the leaderboard.

## 🤝 Contributing
Feel free to fork the repo and submit pull requests for improvements.

## 📜 License
This project is licensed under the MIT License.

---
🎵 *Let the game begin!* 🎵
![Game Screenshot](images/antrakshri.JPG)


