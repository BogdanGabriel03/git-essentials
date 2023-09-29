# git-essentials

This repository is made to help me learn hoe to use git and github

    - $ git clone <what_you_want_to_clone><br>
    // this command clones an existing remore repo and saves it locally ( on your device )

    - $ git status<br>
    // this command shows the status of your work ( unstaged/staged files etc. )

    - $ git log<br>
    // this command shows all the commits that have been succesfully made to the repo

## Going back in time with git

    - git checkout <id>
    lets you go back in time to the point where the id points

## Pull requests

    - learning about pull requests in a practical way

## Undoing a commit

    - $ git reset --hard <hash> sau origin/main  (it will delete files)
    - $ git reset --soft <hash> sau origin/main  (it will not delete files)

## Undoing an already pushed commit

    - $ git push origin master  --force (-f)
