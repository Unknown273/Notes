# Git Notes

1. `git init`
    - Create a new git repository in a folder  

2. `git config --global user.email <your email address>`
    - Add a user's email address in the settings of git  

3. `git config --global user.name <your name>`
    - Added a user's name in the settings of git
4. `git config --global core.editor <editor name>`
    - Set the text editor to edit commit messages
  
5. `git add`
    - Stage a file or add it to different place where it will committed
    - Use . (dot) to add all the files in the current folder
  
6. `git commit`
    - Record the made changes
    - Use the -m option to add the commit message when running the command
        - like this: `git commit -m '<your message>'`
    - Now, if you made a typing mistake in the commit you just made
    - And want to fix it, then type: `git commit --amend -m '<your new message>'`
  
7. `git status`
    - View the status of your files in a git repo
  
8. `git log`
    - View the history of your commits
    - Use the `--reverse` option if you want to start viewing from the first commit
  
9. `git show <commit id>`
    - View the changes made in the specified commit
