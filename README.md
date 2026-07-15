# Rock, Paper, Scissors (Python CLI)

A lightweight, command-line interface (CLI) implementation of the classic Rock, Paper, Scissors game built using Python's native libraries. The player competes against a randomized computer opponent with instant win/loss/draw evaluation.

## Features

- **Command-Line Interface:** Simple text-based menus for fast, lightweight gameplay.
- **Randomized AI Opponent:** The computer's moves are powered by Python's pseudo-random number generator (`random` module).
- **Input Neutralization:** User inputs are normalized to lowercase to prevent accidental casing errors from failing the validation checks.
- **Error Handling:** Built-in catch-all condition to handle invalid text or inputs outside the game's core options.

## How It Works

The game follows the standard rules of Rock, Paper, Scissors:
- **Rock** beats Scissor.
- **Paper** beats Rock.
- **Scissor** beats Paper.

The program captures your choice, evaluates it against the computer's randomly generated choice using conditional logic, and outputs the result immediately.

## Getting Started

### Prerequisites

You only need Python 3.x installed on your machine. No external dependencies or third-party libraries are required.

### Execution

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/rock-paper-scissors-python.git](https://github.com/your-username/rock-paper-scissors-python.git)
   cd rock-paper-scissors-python
