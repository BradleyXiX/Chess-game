# ChessGame

The chess application consists of two modes: playing against a friend in the same browser and playing against the computer, which utilizes the Stockfish REST API from https://stockfish.online/

Images for pieces used from Lichess official repo: https://github.com/lichess-org

Live version: https://awsomecstutorials.github.io/chess-game/

Tutorial can be found on FreeCodeCamp youtube channel: https://youtu.be/fJIsqZmQVZQ
# Chess Game

A web-based chess application built with Angular, featuring two play modes:
- **Play against a friend** (local, same browser)
- **Play against the computer** (powered by the Stockfish chess engine via REST API)

## Features

- Interactive chessboard with move highlighting and history navigation
- Play as either side against a friend or the computer
- Adjustable Stockfish difficulty levels
- Pawn promotion, castling, en passant, and all chess rules enforced
- Move list and game history viewer
- Responsive UI using Angular Material

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [Angular CLI](https://angular.io/cli) (v16+ recommended)

### Installation

1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd chess-game
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

### Running the Application

Start the development server:
```sh
npm start
```
Then open [http://localhost:4200](http://localhost:4200) in your browser.

### Building for Production

```sh
npm run build
```
The production build will be output to the `docs/` directory.

### Running Tests

```sh
npm test
```

## Project Structure

- `src/app/` - Main Angular application code
  - `modules/` - Feature modules (chess board, move list, dialogs, etc.)
  - `chess-logic/` - Core chess logic (board state, move validation, FEN, etc.)
- `src/assets/` - Piece images and sounds
- `src/styles.css` - Global styles
- `src/custom-theme.scss` - Angular Material theme

## Third-Party & Credits

- Chess piece images from [Lichess official repo](https://github.com/lichess-org)
- Chess engine via [Stockfish Online API](https://stockfish.online/)
- UI components from [Angular Material](https://material.angular.io/)

## Live Demo

[https://awsomecstutorials.github.io/chess-game/](https://awsomecstutorials.github.io/chess-game/)

## Tutorial

Watch the tutorial on FreeCodeCamp's YouTube channel:  
[https://youtu.be/fJIsqZmQVZQ](https://youtu.be/fJIsqZmQVZQ)

---

**Enjoy playing chess!**