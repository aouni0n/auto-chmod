# chmod Command Prompt

The "chmod Command Prompt" is a Python script that allows you to interactively choose a `chmod` command and execute it on a specified file location. It provides descriptions of different `chmod` commands for you to choose from.

## Features

- Displays an ASCII art representation of "AOUNION."
- Provides descriptions of `chmod` commands from 1 to 10.
- Prompts you to choose a `chmod` command by entering a number between 1 and 10.
- Executes the chosen `chmod` command on the specified file location.

## Usage

1. Make sure you have Python installed on your system.
2. Clone or download the repository to your local machine.
  ```git clone https://github.com/aouni0n/auto-chmod```
3. Open a terminal or command prompt and navigate to the directory containing the script: `cd auto-chmod`
4. Run the script by executing the following command:`python chmod_prompt.py`
5. The script will display a prompt you to enter a number between 1 and 10 for a `chmod` command. Choose a command by entering the corresponding number and press Enter. Then, enter the file location on which you want to execute the `chmod` command and press Enter.
6. The script will execute the chosen `chmod` command on the specified file location.

## Note
  The script uses the os.system() function to execute the chmod command, so ensure that you have appropriate permissions to modify the file's permissions.
