# PRODIGY_AD_03

# Stopwatch App

A basic stopwatch application built with Python's Tkinter library. This app displays minutes, seconds, and milliseconds and allows users to start, pause, and reset the timer.

## Features

- **Start**: Start the stopwatch and begin tracking time.
- **Pause**: Pause the stopwatch, freezing the elapsed time display.
- **Reset**: Reset the stopwatch to 00:00:00.

## Requirements

- Python 3.x
- Tkinter library (usually included with Python standard library)

## Installation

1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).
2. Clone or download this repository to your local machine.

## Usage

1. Navigate to the directory containing the script.
2. Run the script using Python:

    ```bash
    python stopwatch.py
    ```

3. The stopwatch GUI will open. Use the buttons to start, pause, and reset the timer.

## Code Overview

### Stopwatch Class

- `__init__(self, root)`: Initializes the GUI components and variables.
- `update_clock(self)`: Updates the time display every 10 milliseconds.
- `display_time(self)`: Formats and displays the elapsed time.
- `start(self)`: Starts the stopwatch.
- `pause(self)`: Pauses the stopwatch.
- `reset(self)`: Resets the stopwatch.

### Methods

- **update_clock**: Runs every 10 milliseconds to update the display if the stopwatch is running.
- **display_time**: Formats and updates the time display.
- **start**: Starts the stopwatch.
- **pause**: Pauses the stopwatch.
- **reset**: Resets the stopwatch.

## Example

```python
if __name__ == "__main__":
    root = tk.Tk()
    stopwatch = Stopwatch(root)
    root.mainloop()
