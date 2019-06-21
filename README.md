# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  SOFTWARE ENGINEERING IMMERSIVE

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

6. Create a develop branch by typing `git checkout -b develop` to work from. New features will be based off the develop branch.

7. Once you're on the develop branch create a feature branch so you can start your work:
  - `git checkout -b solutions` (Make sure this new feature branch is based off of develop, meaning you were on the develop branch when you created it).

8. Now create an empty file: `touch solutions.md`
  - Add and commit your changes:
    - `git add solutions.md`
    - `git commit -m "add solution file to save my commands"`

9. Open the `solutions.md` file in Visual Studio Code from the terminal by typing the following command: `code solutions.md`

10. For the following steps, save your commands inside `solutions.md` (To see a history of the commands you recently typed in youre terminal, checkout out the file `~/.bash_history`)

11. Copy your commands used from the bash_history file inside the `solutions.md` file and commit your changes
  - `git add solutions.md`
  - `git add solutions.md -p` to add code line by line (great for adding only certain parts of a file to git)
  - `git commit -m "add command to change path to home directory"`
  - Push your new branch up to GitHub: `git push origin solutions`

12. Now create a `ga` folder in your home directory (`mkdir ~/ga`)
  - Save your command new command you used to create the ga folder inside `solutions.md`
  - Then git add, commit and push the new aditions.

13. Change into the `ga` directory and create a directory for each week i.e. `week1`, `week2`, ..., `week12`
  - Add your commands into solutions.md, add, commit, and push your changes

14. Create a project directory for each project (you will have four projects) i.e. `project1`, ..., `project4`
  - Add your commands into solutions.md, add, commit, and push your changes
