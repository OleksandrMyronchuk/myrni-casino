# Single File HTML/CSS/JavaScript Roulette Emulator

## 🎯 Project Purpose

This project serves as a clear and concise demonstration of how HTML, CSS, and JavaScript can be **combined into a single `index.html` file** to simulate the core mechanics of a simple European Roulette casino game spin. It showcases a functional example of a browser-based application built without external frameworks or libraries, encapsulating structure, styling, and interactive logic within one file.

## ✨ Features

*   **All-in-One File:** Complete HTML structure, CSS styling, and JavaScript game logic contained within a single `index.html` file.
*   **Interactive Table:** Clickable roulette table layout allows users to place bets on various outcomes (straight numbers, red/black, odd/even, low/high, dozens, columns).
*   **Multiple Bet Types:** Supports common European Roulette bets.
*   **Chip Visualization:** Basic visual representation of placed bets ("chips") on the table cells.
*   **Game Flow:** Includes setup (initial balance, bet amount), placing bets, processing spins, and displaying results.
*   **Game State Tracking:** Displays current balance, total staged bet amount, and number of active bets.
*   **Round Outcomes:** Clearly shows the spin result and the net profit/loss for the round.
*   **Game History:** Logs the outcome and details of previous rounds.
*   **Basic Statistics:** Tracks and displays simple statistics on spin results (most frequent, highest profit when landed).
*   **Responsive Design:** Basic responsiveness provided by CSS flexbox and media queries for better viewing on different screen sizes.
*   **Object-Oriented Structure:** JavaScript logic is organized using classes (`Bet`, `RouletteWheel`, `GameStats`, `HistoryManager`, `UIManager`, `RouletteGame`) for better maintainability and demonstration of OOP principles.

## 🚀 How to Use

This project is designed for simplicity:

1.  **Clone or Download:** Get the code onto your local machine.
    ```bash
    git clone https://github.com/OleksandrMyronchuk/myrni-casino.git
    ```
    Alternatively, download the zip file from the GitHub page.
2.  **Open the File:** Navigate to the project directory and simply open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge, etc.).
3.  **Play:** Set your initial balance, bet amount per click, and maximum total bet. Click "Start Game". Then, click on the areas of the roulette table (numbers, red/black, etc.) to place chips. Click "Place Bets" to spin the wheel and see the result, or "Skip Round" to spin without betting.

## 📁 File Structure

The entire project is contained within a single file:
<pre>
.
└── index.html
</pre>
## 🛠️ Technologies Used

*   **HTML5:** For the structure and layout of the page.
*   **CSS3:** For styling the game elements and providing basic responsiveness.
*   **JavaScript (ES6+):** For all the game logic, interaction, state management, and DOM manipulation, utilizing an Object-Oriented approach.

## 💡 Potential Enhancements

This project is a starting point and could be expanded upon with features like:

*   Adding more complex bet types (splits, corners, streets, etc.).
*   Improved chip visuals and stacking logic.
*   Adding a visual spin animation for the roulette wheel.
*   Integrating sound effects.
*   Implementing persistence (using Local Storage) to save game state.
*   Allowing different chip denominations or custom bet amounts per click.
*   Adding support for American Roulette (with 00).
*   More detailed game statistics and visualizations.

## ⭐ Support This Project

If you found this project interesting, useful, or learned something from it, please consider giving it a ⭐ star on GitHub! It's a simple way to show your support and helps motivate further development and visibility. Thank you!

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).