Educational Chemistry Game - Periodic Table Learning Tool
This project is an interactive, browser-based game designed to help students learn and memorize the periodic table of elements. It's built with vanilla HTML, CSS (using Tailwind CSS), and JavaScript, ensuring it's lightweight and runs in any modern web browser without needing any setup.

Features
Quiz Mode: Test your knowledge with multiple-choice and short-answer questions covering element names, symbols, and atomic numbers. Receive instant feedback and track your score.

Puzzle Mode: Challenge yourself by dragging and dropping elements into their correct positions on a blank periodic table.

Challenge Mode: Race against the clock! Answer as many questions as you can in 60 seconds and aim for the top of the local leaderboard.

Progress Dashboard: Your performance is automatically saved in the browser. The dashboard displays your high scores, overall accuracy, and even identifies "weak areas" to help you focus your studies.

Tech Stack
HTML5: For the core structure of the application.

Tailwind CSS: For a clean, modern, and responsive user interface.

Vanilla JavaScript (ES6+): For all game logic, state management, and DOM manipulation. No frameworks or libraries are needed.

Running Locally
This project is a single, self-contained HTML file. No special tools, builds, or servers are required.

Download the file: Save the index.html file to your local machine.

Open in browser: Simply double-click the index.html file, or right-click and choose "Open with" to select your favorite web browser (like Chrome, Firefox, or Edge).

That's it! The game will run directly in your browser.

File Structure
This project is delivered as a single index.html file to make it easy to share and run. For development purposes, the project was originally designed with the following structure:

/chemistry-game
  ├── index.html        # Main entry point (contains all HTML, CSS, and JS)
  ├── style.css         # (Embedded in <style> tags)
  ├── script.js         # (Embedded in <script> tags)
  ├── /data
  │     └── elements.json   # (Data is included as a JS object)
  └── README.md

In the final version, all CSS, JavaScript, and element data have been embedded directly into index.html for maximum portability.
