# gitflow
Testing Git flow for PR ...
- Adding some content for feauture-1 ...

### Git commands to merge the pull request branch into master
The Git merge for a PR process is simply a merge process from the feature branch, subject of the pull request to the master.
Below are the Git commands that are involved:

> git checkout master --> checkout locally to master branch
> git pull origin master --> Syncronize the local master codebase with the remote master branch
> git merge feature-1 --> Rely on Git to choose the right merge steps like fast-forward or another with the feature branch subject of the PR
> git push master --> Upload the code changes to the remaote master

### Using Github editor
During the PR process, Github editor offers the Git command line steps suitable for that workflow stage besides the editor tools

