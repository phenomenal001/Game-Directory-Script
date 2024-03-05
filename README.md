# Game Directory Script

The Game Directory Script is a versatile tool for automating the management and execution of game code stored within a directory structure. This script is particularly useful for developers or enthusiasts working with multiple game projects and seeking a streamlined solution for organizing, compiling, and running game code.

## Assumptions

- The project assumes that the game files are stored within a directory named "data".
- Each game is contained within a subdirectory that includes the word "game".
- Each game directory contains a single .go file that requires compilation before execution.

## Project Steps/Requirements

1. **Find Game Directories:** The script identifies all game directories within the specified "data" directory.
2. **Create Games Directory:** It creates a new directory named "games" to store the extracted game files.
3. **Copy and Rename Game Files:** The script copies game files from their original directories to the "games" directory while removing the "game" suffix.
4. **Generate JSON Information:** It generates a .json file containing information about the games, such as names and directories.
5. **Compile Game Code:** The script compiles all game code stored within the "games" directory.
6. **Run Game Code:** Finally, the script executes each compiled game.

## Usage

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Modify the script parameters as needed (e.g., data directory path).
4. Run the script using the appropriate command for your operating system (e.g., `python game_directory_script.py`).

## Dependencies

- This project is written in Python and requires Python 3.x.
- No external dependencies beyond standard Python libraries are needed.

## Contributing

Contributions to the Game Directory Script are welcome! If you have suggestions for improvements, bug fixes, or new features, please feel free to submit a pull request.

Happy gaming!
