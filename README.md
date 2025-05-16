# ![YARCS Icon](icon.ico) YARCS2 - Yet Another Rubik's Cube Solver

YARCS is a modern, efficient Rubik's cube solver application with an intuitive graphical interface. It allows users to input any cube configuration and get step-by-step solving instructions.


## Features

- **Dual Cube Views**: Input and output cube states with easy switching between them
- **Interactive Color Selection**: Click or use spacebar-hover to fill cube faces
- **Real-time Solving**: Get instant solutions as you input the cube state
- **Smooth Animations**: Fluid transitions and hover effects for better user experience
- **Small Preview**: Mini view of both input and output cube states
- **Windows Integration**: Uses system accent colors for theming
- **Memory Efficient**: Implements caching and optimizations for smooth performance
- **Multi-threaded**: Handles UI and solving operations separately for responsiveness

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
  - customtkinter: Modern themed widgets
  - kociemba: Rubik's cube solving algorithm
  - Pillow: Image processing for colors
  - pywinstyles: Windows-specific styling
  - winaccent: Windows accent color integration
  - pywin32: Windows API access

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

## Implementation Details

The application uses several optimizations for smooth performance:

- Function result caching with `@functools.lru_cache`
- Debounced color selection and animations
- Efficient state management and event batching
- Smart widget hierarchy for proper z-index handling
- Memory-efficient color representation

## Dependencies

- customtkinter: Modern themed widgets
- kociemba: Rubik's cube solving algorithm
- Pillow: Image processing for colors
- pywinstyles: Windows-specific styling
- winaccent: Windows accent color integration
- pywin32: Windows API access

## License

[MIT License](LICENSE)
