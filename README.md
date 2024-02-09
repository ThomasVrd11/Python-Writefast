# Speed Typing Test

This project is a speed typing test implemented in Python using the curses library. It measures the user's typing speed in words per minute (WPM) by presenting a random text and tracking the time it takes to type it correctly.

## How to Run

To run the speed typing test, follow these steps:

1. Make sure you have Python installed on your machine.
2. Clone the repository or download the project files.
3. Open a terminal or command prompt and navigate to the project directory.
4. Run the following command to install the required dependencies:
   ```
   pip install curses
   ```
5. Run the following command to start the speed typing test:
   ```
   python main.py
   ```

## Usage

1. Upon starting the program, a welcome screen will be displayed. Press any key to begin or press 'ESC' to exit.
2. The program will present a random text for you to type.
3. Type the text as accurately and quickly as possible.
4. The current WPM (words per minute) will be displayed at the top of the screen.
5. If you make a mistake, use the backspace key to delete characters.
6. Once you have typed the entire text correctly, a message will be displayed indicating completion.
7. Press any key to continue to the next text or press 'ESC' to exit the program.

## Customization

You can customize the texts used in the speed typing test by modifying the `text.txt` file. Each line in the file represents a separate text that can be randomly selected.

## Dependencies

This project requires the following dependencies:

- Python
- curses
