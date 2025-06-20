# 🪨📄✂️ Rock, Paper, Scissors Game

Welcome to the **Rock, Paper, Scissors** game built using JavaScript!  
This fun mini-project lets you challenge your computer in a classic game of stone-paper-scissors.  

---

## 🎮 Features

✅ **Two-Player Game**  
- Player 1: **You** (human player)  
- Player 2: **Computer** (automatically makes random choices)

✅ **Simultaneous Turns**  
- As soon as you click an option (stone, paper, or scissors), the computer also makes its move.

✅ **Score Tracking**  
- Real-time scores for both human and computer are displayed on the screen.

✅ **Win Messages**  
- Custom messages are shown for each round depending on who wins.

✅ **Rules Section**  
- A "Rules" button at the bottom right opens a pop-up explaining the game rules.  
- Includes a close button to dismiss the pop-up.

✅ **Persistent Scores**  
- Scores are saved in the browser’s storage (using **localStorage**) so they **won’t reset** even if you reload the page.

✅ **Celebration Animation**  
- Whenever the human wins, a fun celebration animation (or a hurray page) is shown.

✅ **Unlimited Rounds**  
- There’s no maximum score or final win condition. The game continues indefinitely, keeping track of each round’s result.

---

## 📜 FAQ

> **Q: Do the scores reset after clicking "Play Again" or on any page?**  
> **A:** No, the scores persist across pages and reloads.

> **Q: Is the Hurray/Celebration Page visible only after a certain score or after every user win?**  
> **A:** It appears after **every win** by the human player.

> **Q: Is there any maximum score for deciding a WIN?**  
> **A:** No. Each round is independent. Scores keep incrementing for both human and computer.

---

## 💻 Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**

---
## 🚀 Additional Functionality

- **Responsive Design**  
   The game layout adapts seamlessly to different screen sizes, making it playable on both desktop and mobile devices.

- **Sound Effects**  
   Optional sound effects play on each move and when a player wins a round, enhancing the gaming experience.

- **Dark Mode**  
   Toggle between light and dark themes for comfortable play in any environment.

- **Animated Buttons**  
   Interactive button animations provide visual feedback when making selections.

- **Accessibility Features**  
   Keyboard navigation and screen reader support ensure the game is accessible to all users.

---
## 📦 Setup Instructions
Before you begin, ensure you have [Node.js](https://nodejs.org/) installed (optional, only needed for development or running a local server).

2. **Open the Game**

   - Simply open `index.html` in your web browser to start playing.
   - No build steps or dependencies are required for basic gameplay.

3. **Development Mode (Optional)**

   - To run a local development server with live reload, you can use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (VS Code extension) or any static server:
     ```bash
     npx serve .
     ```
   - Edit the source files (`index.html`, `style.css`, `script.js`) and refresh to see your changes.

4. **Customizing the Game**

   - You can modify the rules, add new features, or change the UI by editing the source files.
   - All assets and scripts are located in the project root for easy access.

5. **Feedback & Contributions**

   - Found a bug or have a feature request? Open an issue or submit a pull request on GitHub.
   - Contributions are welcome!

---
1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/rock-paper-scissors-game.git
   cd rock-paper-scissors-game
   ```

2. **Project Structure**

   ```
   rock-paper-scissors-game/
   ├── index.html         # Main HTML file
   ├── style.css          # Stylesheet for the game
   ├── script.js          # JavaScript logic
   ├── assets/            # Images, icons, and sound files
   - **Leaderboard System**  
      Track and display the top scores achieved by players during the current session.

   - **Custom Avatars**  
      Choose or upload a custom avatar to personalize your player profile.

   - **Multilingual Support**  
      Switch between multiple languages for the game interface and rules.

   - **Statistics Dashboard**  
      View detailed stats such as win/loss ratio, most chosen move, and streaks.

   - **Share Results**  
      Share your game results or scores directly to social media platforms.

   - **Customizable Rules**  
      Option to add new moves (like "Lizard" and "Spock") or tweak existing rules for a unique gameplay experience.
   ```

3. **Browser Compatibility**

   - The game works on all modern browsers (Chrome, Firefox, Edge, Safari).
   - For the best experience, ensure JavaScript is enabled.

4. **License**

   - This project is open-source and available under the [MIT License](LICENSE).

---