# Few Steps to Start with Python

Few simple steps to start with Python on MacOS.

## Install


1. Install [Homebrew]:

   ```shell
   ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
   ```

1. Install [Python]:

   ```shell
   brew install python
   ```

1. Install [vscode]

## Simple Hello World

Start Visual Studio Code, and open a new folder:

![Open new folder][vscode_new_folder]

There are two easy ways in Visual Studio Code to execute Python scripts. The
first is using the built in terminal. Open a terminal using the Control
backtick (<kbd>^</kbd> + <kbd>`</kbd>) key combination. This will open
the terminal. Create a simple Python script, and execute this with the
command `python name_of_the_python_file.py`:

![Hello World using a terrminal][hello_world_cli]

The second method is using the Python extension for Visual Studio Code. Install
the Python plugin from the extensions marketplace. Create a simple Python
script and press the green play button to execute the script:

![Hello World using the Python extension][hello_world_ext]

[Homebrew]: https://treehouse.github.io/installation-guides/mac/homebrew
[Python]: https://www.python.org/
[vscode]: https://code.visualstudio.com/

[vscode_new_folder]: ./gifs/new_folder_vscode.gif
[hello_world_cli]: ./gifs/hello_world_cli.gif
[hello_world_ext]: ./gifs/hello_world_ext.gif
