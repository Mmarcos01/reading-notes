[Home](README.md)

## Add Commit Push (ACP)

#### Clone your git repository to the Terminal/Command Line

**In the terminal use the command:**

git clone 'GitHub repository url'

**Ensure you're working out of the right file with:**

cd 'repository name'

Utilize ls and ls -a to list the files in your repository

**To make changes to your repo using VScode use command:**

code .

This will open VSCode and allow you to work on your repository within it.

**If you want to see the origin location of your repository use:**

git remote -v

Remember to save your changes when they are made in VScode. 

**When you're ready to commit, return to the terminal and use command:**

git status

This is how you can ensure your modifications were made. If you made modifications to a file called README.md it will display as modified in red.

**When you're ready to stage the changes of README.md to the repository use:**

git add README.md

If you use git status afterward you will see the file README.md is now staged and green.

**When you're ready to commit the changes use:**

git commit -m "Leave a message between these quotes as to why you had made the changes"

**Lastly push the files to the origin repository with:**

git push origin

Enter your name and password and now your repository and associated Github pages will be updated with the pushed information.

[Home](README.md)