# OpenPegaAPI

Welcome to the OpenPega API!
This repository will be the bedrock for many of the projects that will come.

## First steps
To start developing on this you need to have [Docker](https://www.docker.com/) installed on your machine. You can find direct downloads for majors OSes [here](https://docs.docker.com/get-docker/)

You will also need a special program called `docker-compose`, you can grab a copy of it [here](https://docs.docker.com/compose/install/) 

## Wanna contribute?
If you want to contribute to the development of this repository, just clone the repository using
   
    $ git clone git@github.com:OpenPega/open-pega-api.git

For branch names, we are using [git-flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow#:~:text=Gitflow%20is%20a%20legacy%20Git,software%20development%20and%20DevOps%20practices.), basically each time that you are going to work on a new feature or bug, you will need to create a branch name with special names:
    
- `feature/xxx` for feature branches
- `bugfix/xxx` for bugfix branches

After completing the feature or fixed the bug, you will need to push that branch into the repository, this can be achieved using `pull` command from git

    $ git push -u origin feature/xxx # for a feature branch

or
    $ git push -u origin bugfix/xxx # for a bugfix branch

Then, open a new pull request [here](https://github.com/OpenPega/open-pega-api/pulls) using your new pushed branch as the branch that you want to get merged and `develop` as the base branch, then we will review your work on it and asses the changes. After the review process (that can contain a couple of fixes from your side) it will be ready to be merged into the `develop` branch. Hit the big green merge button at the bottom so your work can be merged with `development`. Congratulations, your work will be kept for posterity :)
