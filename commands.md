#Git Commands

mkdir git-for-devops
Creates a new directory named git-for-devops.

ls
Lists the contents of the current directory.

cd git-for-devops/
Changes directory into git-for-devops.

pwd
Prints the current working directory path.

vim hello.txt
Opens or creates a file called hello.txt in the vim text editor.

ls
Again, lists the contents of the current directory.

git init
Initializes a new Git repository in the current directory.

ls -lart
Lists all files, including hidden ones, with details, in reverse time order.

git status
Shows the current state of the working directory and staging area.

exit
Exits the terminal or shell session.

ls
Lists contents (likely run after logging back in or opening terminal again).

cd git-for-devops/
Navigates again into the git-for-devops directory.

ls
Lists contents of the directory.

pwd
Prints the full path of the current working directory.

ls -lart
Detailed list again, reversed by time.

touch one.txt
Creates an empty file named one.txt.

ls -lart
Lists files with details again to see the newly created file.

touch two.txt
Creates another empty file named two.txt.

ls -lat
Lists files with details, sorted by modification time.

ls -lar
Lists all files in reverse order including hidden ones.

git status
Shows which files are untracked, staged, or modified.

rm hello.txt
Deletes hello.txt.

ls
Checks if the file was deleted successfully.

git status
Shows that hello.txt was deleted and new files are untracked.

git add .
Stages all changes (new, modified, deleted files) for commit.

git status
Shows the staged changes.

git commit -m "it is initial commit"
Commits the staged changes with a message.

git log
Shows the commit history.

ls
Lists current files.

vim one.txt
Opens one.txt in vim to edit it.

git status
Shows that one.txt has been modified.

git add one.txt
Stages the modified one.txt file.

git status
Confirms that one.txt is staged for commit.

git commit -m "changes in one.txt"
Commits the changes to one.txt with a message.

gitlog
(Typo) Should be git log.

git log
Shows the commit history.

exit
Exits the shell.

cd git-for-devops/
Re-enters the working directory.

ls
Lists files again.

git status
Checks for any new changes.

git log
Views commit history again.

git branch
Lists all branches in the repo.

git sttus
(Typo) Should be git status.

git status
Shows status correctly.

git branch
Shows current and other branches again.

git -b checkout dev
(Incorrect command) The correct one follows.

git checkout -b dev
Creates and switches to a new branch called dev.

git branch
Confirms that you're now on the dev branch.

ls
Lists files again.

touch three.txt
Creates a file named three.txt.

git status
Shows that three.txt is untracked.

git add three.txt
Stages the new file.

git status
Confirms that three.txt is staged.

git commit -m "three.txt added"
Commits the new file to the dev branch.

git stats
(Typo) Should be git status.

git status
Shows a clean working directory after commit.

ls
Lists current files.

ls -r
Lists files recursively in subdirectories.

ls -t
Lists files sorted by modification time.

ls -lar
Detailed list, all files, reverse order.

date
Displays the current date and time.

ls -rt
Lists files sorted by time in reverse order.

ls -lrt
Detailed listing sorted by time, reverse.

git checkout master
Switches back to the master branch.

ls
Lists files.

exit
Exits terminal session.

history
Displays the list of previously used commands.
