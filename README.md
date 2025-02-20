# Keylogger Using `pynput` Module

This Python script is a basic keylogger that listens to the keyboard's keystrokes and logs them into a file. It uses the `pynput` library to detect when a key is pressed or released.

**Note**: Keyloggers can have serious privacy and legal implications. Use this script only for ethical purposes, and ensure you have explicit consent from the user before logging their keystrokes.

## Features
- Listens for keyboard input (both alphanumeric and special keys).
- Logs each keypress to a text file (`logging.txt`).
- Exits the keylogger when the `Esc` key is pressed.

## Requirements
- Python 3.x
- `pynput` library

### Install `pynput`
To install the `pynput` library, run the following command:

```bash
pip install pynput
```

How to Use
1. Clone or download the repository.

2. Open the script in your favorite Python environment.

3. Run the script: 
```
python keylogger.py
```
The script will start logging the keystrokes to `logging.txt`. Every key press will be recorded in the file.

To stop the keylogger, press the `Esc` key.

Example Usage:
```
python keylogger.py
```
Once the script is running, any keys pressed will be logged in the `logging.txt` file. For example:

```txt
a s d f g 1 2 3 4 5 ESC 
```
## Code Explanation

1. Imports:

    - The script uses the `pynput` module for capturing keyboard input. Specifically, it imports `Key` and `Listener` from `pynput.keyboard`.

2. `on_press` function:

    This function is triggered whenever a key is pressed.
    The pressed key is added to the keys list and written to the logging.txt file.

write_file function:

    This function writes the keystrokes to the logging.txt file, formatting them for readability (removing quotes and adding a space after each keystroke).

on_release function:

    This function is triggered whenever a key is released.
    If the Esc key is pressed, the keylogger stops listening.

Listener:

    The Listener listens for both keypress and key release events. It is initialized with on_press and on_release functions and starts capturing input.



