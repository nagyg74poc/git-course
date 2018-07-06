# Git course

## Basics
- Create a directory, where you’ll store your project
- Open Sourcetree, create a new repo from existing source, point to the created folder.
- Create a .txt file named as your name. You may add some content as well.
- Add this file to versioning. Actions/Add-Remove
- Commit that you’ve added a file to the versioning. Commit creates a snapshot of your file(s), basically is the Save command for git.
- Do a change on your file, and commit it again

## Branching
- Create a branch from the selected commit
- Do some changes on your file, then commit it.
- Now switch back to the master branch.
- Notice that your file is in the previous state.
- Do some different change on the file.
- Merge changes into master branch (right-click on the alternate branch, select merge into master)
### Let’s make a conflict
- Create a new branch
- Add some changes on your file.
- Switch back to master, do other changes on the same line.
- Merge changes into master branch (right-click on the alternate branch, select merge into master)
- Resolve conflict Actions/Resolve Conflicts
- Click Commit to save the resolution

## Team Work
- Set a remote repository - Repository/Repository Settings/Remotes
- Remote name ‘origin’, URL: git@bitbucket.org:gregnagy74/git-course.git

### Push/Pull

