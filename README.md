# ![YARCS Icon](icon.ico) YARCS2 - Yet Another Rubik's Cube Solver

YARCS is a modern, efficient Rubik's cube solver application with an intuitive graphical interface. It allows users to input any cube configuration and get step-by-step solving instructions.

![preview](preview.png)

## Features

- ⚡ Quick shortcuts for filling the cube
- 🎨 Quick shortcuts for changing fill color
- 🚀 Instant solutions
- ✨ Smooth animations
- 🎲 Supports custom output cubes
- 🔄 Real time preview of both input and output cubes

## Installation

1. Download the latest release from the releases page
3. Run the downloaded file `YARCS.exe`

Or run from source:

1. Clone this repository
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run `YARCS.pyw`

## Requirements

- Windows OS
- Python 3.x
- Required Python packages (if running from source):
  - customtkinter (installed automatically with pip)
  - kociemba (installed automatically with pip)
  - Pillow (installed automatically with pip)
  - pywinstyles (installed automatically with pip)
  - winaccent (installed automatically with pip)
  - pywin32 (installed automatically with pip)

## Usage

1. Run the application:
```bash
python yarcs2.py
```

2. Input your cube's current state:
   - Click or hover with spacebar to fill cube faces
   - Use mouse wheel to switch colors
   - Center squares are fixed and represent face colors

3. The solution will appear automatically in the right panel

## Controls

- **Left Click**: Fill a square with selected color
- **Spacebar + Hover**: Fill squares by hovering over them
- **Mouse Wheel**: Cycle through colors in the color selector
- **Reset Button**: Clear all face inputs
- **Input/Output Toggle**: Switch between input and target cube states
- [how to use the solution](https://jperm.net/3x3/moves)


## License

[MIT License](LICENSE)
