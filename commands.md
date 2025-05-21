
# Git and Linux Command History Explained

## Directory & File Operations

- **mkdir git-for-devops**  
  Create a new directory named `git-for-devops`.

- **ls**  
  List files and directories in the current path.

- **cd git-for-devops/**  
  Navigate into the `git-for-devops` directory.

- **pwd**  
  Print the full path of the current working directory.

- **vim hello.txt**  
  Create or open `hello.txt` using the Vim text editor.

- **touch one.txt**  
  Create an empty file named `one.txt`.

- **touch two.txt**  
  Create another empty file named `two.txt`.

- **touch three.txt**  
  Create a third file named `three.txt`.

- **rm hello.txt**  
  Delete the file `hello.txt`.

## Git Repository Setup & Status

- **git init**  
  Initialize a new Git repository in the current directory.

- **git status**  
  Show the current state of the working directory and staging area.

- **git add .**  
  Stage all changes (new, modified, deleted files) for commit.

- **git add one.txt**  
  Stage the modified `one.txt` file for commit.

- **git add three.txt**  
  Stage the newly created `three.txt` file.

- **git commit -m "commit message"**  
  Commit staged changes with a custom message.

- **git log**  
  View the commit history.

## Git Branching

- **git branch**  
  List all branches in the repository.

- **git checkout -b dev**  
  Create and switch to a new branch named `dev`.

- **git checkout master**  
  Switch back to the `master` branch.

## File Listings (Various Formats)

- **ls -lart**  
  Long list format including hidden files, sorted by time in reverse.

- **ls -lat**  
  Long list sorted by modification time.

- **ls -lar**  
  Long list in reverse order with all files.

- **ls -r**  
  Recursive listing of files and directories.

- **ls -t**  
  Sort files by modification time.

- **ls -rt**  
  Sort files by modification time in reverse.

- **ls -lrt**  
  Long listing sorted by modification time in reverse.

## Miscellaneous

- **date**  
  Show the current system date and time.

- **exit**  
  Exit the current shell session.

- **history**  
  Show the list of previously executed commands.

## Mistyped Commands (Corrected for Reference)

- **gitlog** → Should be `git log`  
- **git sttus** → Should be `git status`  
- **git -b checkout dev** → Should be `git checkout -b dev`  
- **git stats** → Should be `git status`
