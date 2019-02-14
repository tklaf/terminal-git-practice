# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  WEB DEVELOPMENT IMMERSIVE

# Terminal & Git Practice

1. Fork this GitHub repository (there should be a `fork` button on the upper right-hand of this page)

2. Enable Visual Studio Code to be accessed from the terminal by following these steps:
  - Open Visual Studio Code: <kbd>⌘</kbd> + <kbd>Space</kbd> (Command + spacebar)
  - "Visual Studio Code"
  - Enter
  - Open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH command.
  - Restart the terminal for the new $PATH value to take effect. You'll be able to type 'code .' in any folder to start editing files in that folder.

3. Open the Terminal:
  - <kbd>⌘</kbd> + <kbd>Space</kbd> (Command + spacebar)
  - "Terminal"
  - Enter
4. Clone the forked GitHub repository i.e. `git clone /path/to/repository`
5. Go inside this directory by typing: `cd terminal-git-practice`
6. Create a feature branch so you can start your work:
- `git checkout -b solutions`
7. Now create an empty file: `touch solutions.md`
- Add and commit your changes:
  - `git add solutions.md`
  - `git commit -m "addd solution file to save my commands"`
8. Open the `solutions.md` file in Visual Studio Code from the terminal: `code solutions.md`
9. For the following steps, save your commands inside `solutions.md`, use the following format:
```
1. Command used: touch solutions.md
```
  1. Now go back to the terminal and change your path to your home directory
  - Save your command inside the `solutions.md` file and commit your changes:
  - `git add solutions.md`
  - `git commit -m "add command to change path to home directory"`
  - Push your new branch up to GitHub: `git push origin solutions`
  2. Now create a `ga` folder in your home directory
  - Save your command inside `solutions.md`
  - `git add solutions.md`
  - `git commit -m "create ga directory command"`
  - `git push`
  3. Change into the `ga` directory and create a directory for each week i.e. `week1`, `week2`, ..., `week12`
  - Save your command, add, commit, and push your changes
  4. Create a project directory for each project (you will have four projects) i.e. `project1`, ..., `project4`
  - Save your command, add, commit, and push your changes
