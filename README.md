# Memory Game

Memory Game is a simple game where the goal is to find matching pairs of cards. Your objective is to earn as many points as possible by uncovering cards in a way that matching pairs are revealed in a single move. The theme of the game is technologies related to programming.

## Address on google drive
[open in browser](https://tomaszwegrzyngoogledrive.on.drv.tw/www.memory-game-front/)

## How to Run the Application

1. **Download the Source**: Clone or download the application source code to your computer.

    ```bash
    git clone https://github.com/tomasztaw/memoryGameFront.git
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd memoryGameFront
    ```

3. **Open the `index.html` file** in a web browser:

    ```bash
    open index.html
    ```

## How to Play

1. Start the game by clicking on the game board.
2. Flip two cards at a time. Your goal is to find matching card pairs.
3. If the cards match, they will remain uncovered. Otherwise, they will be covered again.
4. Keep playing until you uncover all card pairs.

## Customizing the Game

You can customize the game by modifying the JSON files in the `data` directory. Each card in the game is described as a JSON object containing `name` (the card's name) and `image` (the path to the card's image).

```json
[
    {
        "image": "assets/card1.png",
        "name": "card1"
    },
    {
        "image": "assets/card2.png",
        "name": "card2"
    },
    // Add your own cards
]
```