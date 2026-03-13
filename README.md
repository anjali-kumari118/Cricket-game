# Cricket Game

A fun and interactive web-based cricket game built with HTML, CSS, and JavaScript. Play the classic Bat-Ball-Stump game against the computer!

## Game Description

In this game, you play against the computer in a simplified version of cricket hand cricket. Choose between:
- **Bat**: Representing batting
- **Ball**: Representing bowling
- **Stump**: Representing wicket-keeping

The computer randomly selects one of the three options, and the winner is determined based on cricket rules:
- Bat beats Ball (successful batting)
- Ball beats Stump (successful bowling)
- Stump beats Bat (successful wicket-taking)
- Same choices result in a tie

## Features

- Interactive gameplay with visual buttons
- Score tracking (Wins, Losses, Ties)
- Persistent scores using browser local storage
- Reset functionality to clear scores
- Responsive design with custom CSS styling
- Simple and intuitive user interface

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **Styling**: Custom CSS with responsive design

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd cricket-game
   ```

## Usage

1. **Open the game**:
   - Open `cricket.html` in your web browser

2. **Play the game**:
   - Click on Bat, Ball, or Stump buttons
   - View your choice, computer's choice, and result
   - Check your score at the bottom
   - Click "Reset" to clear scores

## Project Structure

```
cricket-game/
├── cricket.html      # Main game interface
├── cricket.css       # Styling for the game
├── requirements.txt  # Python dependencies (currently unused)
├── README.md         # Project documentation
└── venv/             # Virtual environment (optional, currently unused)
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Future Enhancements

- Add sound effects
- Implement multiplayer mode
- Add animations and transitions
- Create a leaderboard system
- Mobile app version