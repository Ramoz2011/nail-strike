# nail-strike
# Knight Slash — a Hollow Knight fan animation in Python

Click-to-slash interactive animation: every mouse click makes the Knight swing his nail.

![Demo](demo.gif)


## About

This is a small interactive Python project where the player clicks the mouse to trigger the Knight's slash animation. It started as my final creative project in CS1 (Computer Science Essentials) at PCTI STEM Academy, built with CMU Python, and I'm continuing to extend it on my own.

## How it works

- The character sprite is drawn on screen and waits for input
- On every mouse click, the slash animation plays frame by frame
- Built using event handling (`onMousePress`) and shape/sprite drawing

## How to run

1. Install the CMU Graphics library:
   ```
   pip install cmu-graphics
   ```
2. Download or clone this repo
3. Run the game:
   ```
   knight_slash.py
   ```


## Built with

- Python 3
- CMU Graphics (cmu_graphics)

## Planned features

- [ ] Enemies to hit
- [ ] Score counter
- [ ] Sound effects
- [ ] Health system

## Credits

Fan project inspired by **Hollow Knight** by Team Cherry. The Knight character and design belong to Team Cherry — this is a non-commercial fan work made for learning purposes.

Made by Ramiz Mert ([@Ramoz2011](https://github.com/Ramoz2011))

