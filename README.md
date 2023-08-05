# Random Screen Switcher and Mouse Wiggler

This Python script is a simple tool that automates the task of switching screens using Alt + Tab and wiggling the mouse between random coordinates on the screen. It utilizes the `pyautogui` library to control keyboard inputs and mouse movements.

## Requirements

Before running this script, make sure you have the following installed:

- Python: You need Python installed on your system. You can download it from the official website: https://www.python.org/downloads/

- PyAutoGUI: This script relies on the `pyautogui` library. You can install it via pip:

```
pip install pyautogui
```

## How to Use

1. Clone or download the script to your local machine.

2. Install the required libraries as mentioned above.

3. Open a terminal or command prompt, navigate to the folder containing the script, and run the following command:

```
python random_screen_switcher.py
```

4. Once the script starts, it will automatically switch between active screens using Alt + Tab and wiggle the mouse between random coordinates on the screen.

5. To stop the script, press `Ctrl-C` in the terminal or command prompt.

## Functionality

The script contains the following functions:

### 1. `switch_screens()`

This function simulates Alt + Tab keyboard presses a random number of times (between 1 and 5) to switch between active screens. It uses the `pyautogui` library to control keyboard inputs.

### 2. `wiggle_mouse()`

This function moves the mouse cursor to random coordinates on the screen a random number of times (between 4 and 9). It uses the `pyautogui` library to control mouse movements. The mouse cursor will stay at each random position for 10 seconds before moving to the next one.

### 3. `get_random_coords()`

This function generates random coordinates on the screen based on the screen's size. It returns a list in the format `[x, y]`, where `x` and `y` are the x and y coordinates, respectively.

## Caution

Please be cautious while using this script, especially in situations where it may interfere with your work or cause unintended actions. The script is intended for entertainment and demonstration purposes and may not be suitable for all scenarios. Always ensure that you understand the implications of using this script before running it on your system.

## Disclaimer

The author(s) of this script are not responsible for any misuse, damages, or loss of data caused by running this script. Use it at your own risk.
