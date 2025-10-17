# Conway's Game of Life in Mojo

A Conway's Game of Life implementation using Mojo programming language with pygame visualization.

## About

Conway's Game of Life is a cellular automaton where cells evolve based on simple rules:
- Live cell with 2-3 neighbors survives
- Dead cell with exactly 3 neighbors becomes alive
- All other cells die or stay dead

## Screenshot

<img width="712" height="740" alt="Conway's Game of Life" src="https://github.com/user-attachments/assets/06e090ff-2f84-4fb1-b6f0-f58e1451ef57" />

## Files

- `main.mojo` - Main application with pygame display
- `gridv1.mojo` - Grid data structure and evolution logic
- `pixi.toml` - Project dependencies

## Requirements

- Mojo SDK ≥0.25.7
- Python 3.11-3.12
- macOS ARM64

## Usage

```

pixi install
pixi run mojo main.mojo

```

## Controls

- `ESC` or `Q` - Quit simulation
- Close window - Exit

## Implementation

The project uses a 128x128 toroidal grid with random initial state. The `Grid` struct handles evolution logic while pygame provides real-time visualization with customizable colors and animation speed.
