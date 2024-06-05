# programming-notes

## tips to keep in mind when programming

### How to remove a cloned repository from your computer in order to clone it back again?

Delete the .git directory in the root-directory of your repository if you only want to delete the git-related information (branches, versions).

If you want to delete everything (git-data, code, etc), just delete the whole directory.

.git directories are hidden by default, so you'll need to be able to view hidden files to delete it.

from: https://stackoverflow.com/questions/1514054/how-do-i-delete-a-local-repository-in-git

tip: use the following command. rm -fr filename

### Multiline comments in VScode

-hightlight the section you will like to comment

- click on ctrl + up arrow + number 7
