# BattleShip - ConsoleApp

BattleShip game using C#

### Models: 

- 2 players
- 1 board
- 5 ships for each player

### Game Rules

This is a classic "BattleShip" Game with Two players. Each have a 5x5 board. During setup, players are setting their name and choose from A1-E5 5 ships.
During play, players take turn “attacking” a single position on the opponent’s board, and the opponent must respond by either reporting a “hit” on one of their battleships (if one occupies that position) or a “miss”
A battleship is sunk if it has been hit on all the squares it occupies. A player wins if all of their opponent’s battleships have been sunk.

## Structure

- Solution contains two projects
  - BattleShip-ConsoleApp - A console Project with game implementation
  - BattleShipLibrary - Console Library with gane Logic
- /Models - contains data models

## Requirements

- Visual Studio
- C#

### Clone this project

```
git clone https://github.com/LukaszTylisz/BattleShip-ConsoleApp
```

### Building
- Open Visual Studio -> Build -> Build All

### Execution
- Open Visual Studio -> Run -> Start Without Debugging
