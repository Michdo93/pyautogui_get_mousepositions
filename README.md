# pyautogui_get_mousepositions
A simple Python script with PyAutogui to get the current position of the mouse. This could be helpful finding out on which position you may want to click if you are writing your own code.

## Installation

Please install `PyAutogui` at first. You can install it for `Python 2` or `Python 3`:

```
python -m pip install pyautogui
python3 -m pip install pyautogui
```

In the next step you can create a simple file like the following `get_positions.py`:

```
import pyautogui

while True:
    print(pyautogui.position())
```

At least you can run it with:

```
python get_positions.py
python3 get_positions.py
```

If you hover over a position you will see in your command line the x and the y coordinates for it.
