# First-repository
How to set up Git and Github for first time use
# Download Git
This example uses Git for Windows 64-bit version 2.17.1
download it from: https://git-scm.com/download/win
# Instal Git on the local computer
Run the installation program
Choose: Use Vim
Important! The installation program urges you to choose another editor, but ignore that for starters.
Choose: Use Git from Git Bash Only
Important! This is the safest way to run Git on your local computer. It is possible to run git on other terminals, but this can be very tricky.
Choose: Use the OpenSSL library
Choose: Checkout Windows-style, commit Unix-style line endings
Choose: Use MinTTY(the default terminal of MSYS2)
Choose: Enable file system cashing
Choose: Enable Git Credential manager
Click: Install
# Configure Git
```
Git command:
git config --global user.name "Some username"
Important! Choose a meaningfull username. If you work on the same project from different computers. It might be a good idea to choose
different usernames to able to see from where work was done. 
git command:
git config --global user.email "Some email address"
Check it with:
Git command:
git config user.name, displays the username
git config user.email displays the useemail
```
Git is now ready for use on the local computer
