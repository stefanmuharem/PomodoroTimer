# Pomodoro Timer

A simple Pomodoro Timer application built with Python and `tkinter`. This application helps manage work/break cycles using the Pomodoro Technique. The timer alternates between work intervals of 25 minutes, short breaks of 5 minutes, and long breaks of 20 minutes after every 4 work intervals.


## Features

- Work and break cycles
- Visual countdown timer
- Start and reset functionality
- Visual feedback for completed work sessions

## Requirements

- Python 3.x
- `tkinter` library (usually comes pre-installed with Python)

## Files

- `main.py`: The main script for the Pomodoro Timer application.
- `tomato.png`: Image used for the timer's background.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/pomodoro-timer.git
    cd pomodoro-timer
    ```

2. **Ensure you have Python and `tkinter` installed.**
   - You can check if `tkinter` is installed by running:
     ```bash
     python -m tkinter
     ```
   - If `tkinter` is not installed, you can install it via your package manager.

3. **Run the application:**
    ```bash
    python main.py
    ```

## Usage

1. **Start the Timer:**
   - Click the "Start" button to begin the timer.
   - The timer will start with a work session followed by break sessions.

2. **Reset the Timer:**
   - Click the "Restart" button to reset the timer and cycle counter.

3. **Track Progress:**
   - Checkmarks appear after each completed work session to visually track progress.

## Code Overview

### Constants

- Colors, font, and timer durations are defined at the beginning of the script.

### Functions

- `reset_timer()`: Resets the timer and UI elements.
- `start_timer()`: Starts the timer and switches between work/break cycles.
- `count_down(count)`: Manages the countdown mechanism and updates the UI.

### UI Setup

- The UI is created using `tkinter` elements such as `Label`, `Button`, and `Canvas`.

## Contribution

Feel free to fork this repository and submit pull requests.


