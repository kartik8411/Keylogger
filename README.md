# Keylogger Using Pynput Module
### This is a simple keylogger built using the pynput module in Python. The keylogger listens to the user's keyboard activity and logs every keypress into a file. It captures both alphanumeric and special keys. The captured keys are written to a file called logging.txt.

## Prerequisites

### Before running the script, make sure you have the following:

- ### Python 3 installed
- ### `pynput` library installed

### You can install the required library using pip:
```
pip install pynput
```

## How It Works

   ### 1.  The script uses the ```pynput``` module to listen for keypresses and key releases.

   ### 2.  Each keypress is captured and logged to a file called ```logging.txt```.

   ### 3.  The ```on_press``` function adds the key to a list and writes the list to the file.

   ### 4. Special keys (e.g., ```esc```, ```space```, etc.) are also captured and displayed in the console.

   ### 5.  When the ```esc``` key is pressed, the listener stops, and the program exits.

## Key Logging

### The keystrokes are logged with spaces separating each keystroke. Special keys (like ```esc```, ```shift```, etc.) are recorded in a readable format.

## File Output
 -  ### The logged keystrokes are saved to a file named ```logging.txt``` in the same directory where the script is located.

## How to Run

  ### 1. Clone or download the repository containing the ```keylogger.py``` script.

  ### 2. Open a terminal or command prompt and navigate to the directory containing ```keylogger.py```.

  ### 3. Run the script using the following command:
  ```
python keylogger.py
```
  ### 4. To stop the script, press the ```esc``` key.

## Important Notes

  - ### This script should be used responsibly and legally. It is intended for educational purposes to demonstrate how keylogging works.

  - ### Always obtain proper consent and respect privacy when working with any logging systems or monitoring tools.

## License

### This project is licensed under the MIT License - see the ```LICENSE``` file for details.

### This `README.md` will guide users through installing the necessary dependencies, running the script, and understanding its functionality. Remember to use such scripts responsibly and for ethical purposes.










