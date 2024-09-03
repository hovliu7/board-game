# Ataxx Board Game

## Overview

Tactix is a Java-based board game designed for both team play and single-player mode against an intelligent AI opponent. The game implements a sophisticated AI using a combination of the minimax algorithm and alpha-beta pruning to determine optimal moves, making it a challenging and engaging experience for players.

## Features

- **Single-Player Mode**: Play against a smart AI opponent that uses advanced algorithms to challenge your strategic thinking.
- **Team Play**: Engage in multiplayer mode where teams can compete against each other.
- **Intelligent AI**: The AI opponent utilizes alpha-beta pruning within a minimax algorithm to efficiently find the best moves to win the game.
- **Customizable Gameplay**: Adjust game settings to modify the difficulty level and game rules for a tailored experience.

## Implementation Details

### Minimax Algorithm with Alpha-Beta Pruning

The AI opponent in Tactix is driven by the minimax algorithm, a decision rule used for minimizing the possible loss while maximizing the potential gain. To optimize the performance of the AI, alpha-beta pruning is applied to eliminate branches in the game tree that do not need to be explored, significantly improving the efficiency of the decision-making process.

### Game Mechanics

- **Board Layout**: The game is played on a grid-based board, where players take turns making moves to conquer the opponent's pieces.
- **Winning Condition**: The game is won by the player or team that successfully captures the most territory on the board by the end of the game or eliminates all the opponent's pieces.
- **AI Strategy**: The AI evaluates possible moves by looking ahead several turns, assessing the potential outcomes, and choosing the move that maximizes its chances of winning while minimizing the player's opportunities.
