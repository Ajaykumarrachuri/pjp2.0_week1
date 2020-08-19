diff between checkout and pull?

git pull contacts the remote repository identified by origin and looks for updates. It fetches any updates and then merges the changes into the target branch. It does not create a new branch.

git checkout -b <branch> origin/<branch> creates a new branch based on origin/<branch>, and does not contact the remote repository. It looks at origin/<branch> as it currently exists in your local repository.