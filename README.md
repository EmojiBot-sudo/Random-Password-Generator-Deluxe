# Random-Password-Generator-Deluxe
The Random Password Generator Deluxe is a Password Generator that has more features than your average password generators.

# Password Generator Deluxe

A powerful and user-friendly password generator built with Python and Tkinter.

---

## Features

* **Customizable Length**: Select password lengths from 4 to 64 characters.
* **Character Options**:

  * Include uppercase letters
  * Include lowercase letters
  * Include digits
  * Include symbols
  * Exclude ambiguous characters (e.g., `{}`, `[]`, `/\`, etc.)
* **Entropy Calculation**: Displays entropy in bits and rates password strength (Very Weak to Very Strong).
* **Readable Suggestions**: Offers easy-to-read alternatives (e.g., replacing `0` with `O`).
* **History Tracking**: Logs generated passwords with timestamps and entropy values. View, export, or clear history.
* **Settings Persistence**: Save and load your preferred configurations using JSON.
* **Auto-copy & Context Menu**: Automatically copy passwords to the clipboard. Right-click to copy manually.
* **Random Number Generator**: Switch to a second tab to generate random numbers within a defined range.
* **Keyboard Shortcuts**: Press `Enter` to quickly generate a password.
* **Dark Mode Toggle**: (Feature removed in v1.7)

---

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/EmojiBot-sudo/Random-Password-Generator-Deluxe/
   ```

2. **Install dependencies**:

   No additional dependencies are required—this project uses only Python's standard library.

3. **Run the application**:

   ```bash
   Random_Password_Generator.py
   ```

---

## How to Use

1. Use the slider to set the desired password length (recommended: 12–16 characters).
2. Select the character types you want to include.
3. Click **Generate Password** or press `Enter`.
4. Review the entropy and strength rating displayed below the result.
5. Use the **Show/Hide** button to toggle password visibility.
6. Save or load settings using the appropriate buttons.
7. View or export your password history.
8. Clear history to start fresh when needed.
9. Switch to the **Random Number** tab to generate numbers between a specified range.

---

## Changelogs

 Version 1.0 - Initial Release
 Version 1.1 - Added options to exclude ambiguous characters and auto-copy
 Version 1.2 - Implemented password strength scoring and entropy display
 Version 1.3 - Integrated history tracking with timestamp
 Version 1.4 - Added Save/Load/Export Settings functionality
 Version 1.5 - Introduced dark mode toggle and password visibility toggle
 Version 1.6 - Refactored UI for better usability and layout scaling
 Version 1.7 - Removed dark mode button
 Version 1.8 - Added password history viewer and reset history button
 Version 1.9 - Added watermark with author's name to UI
 Version 2.0 - Added Password Strength Rating and Easy-to-Read Suggestions
 Version 2.1 - Added right-click context menu to copy password manually
 Version 2.2 - Added keyboard shortcut (Enter key) to trigger password generation
 Version 2.3 - Display file path to the user after saving settings
 Version 2.4 - Added tooltip for recommended password length (12–16 characters)
 Version 2.5 - Grouped password length label and scale in a frame
 Version 2.6 - Added second tab for random number generator

---

## Contributing

Contributions are warmly welcomed! If you'd like to enhance this project, please open an issue or submit a pull request.

---


