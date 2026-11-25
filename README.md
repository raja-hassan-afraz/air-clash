# AIR CLASH

A 2D arcade shooter written in Python with Pygame. You fly a jet, shoot down six moving helicopters, and score a point for each hit. The game ends when a helicopter collides with you. A small Tkinter window handles the start menu and the restart screen.

## Features

- Start menu with Play and Exit
- Six enemy helicopters that bounce around the screen
- Shooting, collision detection and a live score
- Background music, laser and explosion sounds
- Game over screen with your score, Restart and Exit

## Requirements

- Python 3
- Pygame (`pip install -r requirements.txt`)
- Tkinter (included with most Python installs)

## Run

```bash
pip install -r requirements.txt
python main.py
```

Run it from the project folder, because images and sounds are loaded by relative path.

## Controls

| Key | Action |
| --- | --- |
| Space | Fire |
| Right arrow | Move right |
| K | Move left |
| Up arrow | Move up |
| Down arrow | Move down |

The jet keeps moving in the last direction you pressed.

## Files

| File | Purpose |
| --- | --- |
| `main.py` | Game code |
| `*.png`, `*.jpg` | Sprites and backgrounds |
| `*.wav` | Music and sound effects |
