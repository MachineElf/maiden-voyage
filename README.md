maiden-voyage
=============

My first github repository, for learning both web dev stuff and git commands.

Important commands:
------------------

*** Initial system configuration ***

git config --global user.name "Your Name Here"
git config --global user.email "Your email here"
git config --global color.ui true
(sub in core.editor, merge.tool etc after --global as needed)



*** Checks and help ***

git help command-you-need-help-with
git config --list



*** Initialising a repo ***

cd /directory-you-want-repo-in
git init

git add *.* (file[s] you want to add to repo)
git add README
git commit -m 'name-of-the-repo'

(above three lines would be used for very first commit)



*** Fetching a clone/copy of a desired repo ***

git clone git://github.com/machineelf/desired-repo-name.git

(if want a different folder name locally, add a space after .git and then the desired folder name, e.g. /desired-repo-name.git local-name.git )



*** Telling git where to host in cloud, and how to sync ***

git remote set-url origin git@github.com:MachineElf/maiden-voyage.git

git push origin master



*** General commands ***

git status
git add filename-here
git commit (or more likely git commit -am "Commit message here"
git diff
git rm filename-here

