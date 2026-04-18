# Domino Score Tracker

A mobile-first web app for tracking scores in Domino games. Supports 2–4 players and two game modes.

## Features

- **2–4 players** with custom names
- **Two game modes:** Classic and Fives
- Configurable win target
- Round history with full undo
- Progress bars toward the win target
- Winner screen with final standings
- No install required — single HTML file, works offline

## Game Modes

### Classic
Players score points by winning rounds. The round winner earns the sum of pips remaining in all other players' hands. Blocked rounds are supported — the player with the fewest pips wins and scores the difference.

Win targets: **100 / 150 / 200 points**

### Fives (All Fives / Muggins)
Players score during play whenever the open ends of the layout sum to a multiple of 5. Use the quick-add buttons (5, 10, 15, 20, 25) or enter a custom value.

Win targets: **61 / 101 / 150 points**

## Usage

Open `index.html` in any mobile or desktop browser — no server or build step needed.

1. Select a game mode and number of players
2. Enter player names and choose a win target
3. Tap **Start Game**
4. Use **+ Add Score** after each round (or turn in Fives)
5. Tap **↩ Undo** to reverse the last entry
6. The game ends automatically when a player reaches the target
