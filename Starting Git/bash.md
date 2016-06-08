# Some useful bash commands:

`ls` - List all current files in your current directory

`cd <directory>` - Change directory, go into <directory> folder

`cd ..` - Go back one level

`cd ~` Go to home directory

`pwd` - Lists where you currently are

## Some git commands you'll use frequently:

`git clone <url>` - Downloads a version of the code at the url

`git status` - Shows the current status of your files

`git add .` - Adds all changes to be staged

`git commit -m "<message>"` - Creates a commit with the <message> of all staged files

`git push` - Sends your commits to github

## Branching

So sometimes, you want to work on a feature seperately from the master branch. In this case, you can start by doing a branch `git checkout -b my-new-feature`

Then, run `git status` and it will show you which branch you are currently on. It should say `On branch my-new-feature`.
Then, every commit you do will be commited to this branch, instead of master.

To merge your branch back into master, `git push` your changes and then go on github.com and look at the repository for current project. Select your branch and click __New pull request__. When the pull request is approved, it can be merged into master.
