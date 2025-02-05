# AI Game Play

This repository features AI agents designed to play various games using reinforcement learning algorithms like DQN, PPO, and A2C. It also leverages OR-Tools to solve select puzzles.

## Project Structure

### Notebooks

- `8_queen_problem.ipynb`: Solving the 8-queen problem.
- `Chessgame.ipynb`: Implementing AI for playing chess.
- `flappy_bird.ipynb`: Training AI agents to play Flappy Bird using DQN, PPO, and A2C algorithms.
- `snake.ipynb`: Training AI agents to play Snake.
- `sudoku_killer_solver.ipynb`: Solving Sudoku puzzles.

### Logs

Logs for training runs are stored in the `notebooks/logs/` directory, organized by algorithm and game.

### Models

Trained models are saved in the `notebooks/models/` directory.

## Setup

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv-games
    source venv-games/bin/activate  # On Windows use `venv-games\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

Open the Jupyter notebooks in the `notebooks/` directory to explore and run the code. For example, to train and play Flappy Bird with a PPO agent, open `flappy_bird.ipynb`.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.