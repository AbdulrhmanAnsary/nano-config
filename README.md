# My Nano Configuration

This repository contains my custom configuration file for the Nano text editor, tailored to enhance my development workflow. The configuration file (`.nanorc`) includes various settings such as auto-indentation, mouse support, custom tab sizes, backup options, and a hacker-style color theme along with custom shortcut key bindings.

## Features

- **Auto Indentation:** Automatically indents new lines to match the previous line.
- **Mouse Support:** Enables mouse clicks to move the cursor, set marks, and execute shortcuts.
- **Custom Tab Size:** Sets the tab size to 2 columns.
- **Constant Cursor Display:** Shows the current cursor position (line, column, and character number) on the status bar.
- **Case-Sensitive Search:** Enables case-sensitive searches for more accurate results.
- **Smart Home Key:** Moves the cursor intelligently to the beginning of non-whitespace characters.
- **Backup Files:** Automatically creates backup files (with a tilde ~ suffix) when saving.
- **Unique Numbered Backups:** Keeps a uniquely numbered backup each time you save a file.
- **Regular Expression Searches:** Enables extended regex for searches.
- **Custom Color Scheme:** Hacker-style theme with custom title and status bar colors.
- **Custom Key Bindings:** Custom shortcuts for copy (`Ctrl+C`) and paste (`Ctrl+V`).

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/AbdulrhmanAnsary/nano-config.git
   ```

2. **Copy the Configuration File:**
  ```bash
    cp my-nanorc-config/.nanorc ~/
  ```

3. **Restart Nano:**
Open a new terminal session or restart Nano to apply the new settings.

## Usage

- Open any file with Nano, and your custom configuration will automatically take effect.

- Use the custom shortcuts defined in the file:

  - Copy: Ctrl+C

  - Paste: Ctrl+V

## Contributing

Contributions are welcome! If you have suggestions, improvements, or additional features to add, feel free to fork this repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](/LICENSE) file for details.