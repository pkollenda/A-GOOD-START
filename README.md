
<!-- README.md is generated from README.Rmd. Please edit that file -->

# A-GOOD-START

<!-- badges: start -->
<!-- badges: end -->

Empty project shell with all the right workflow options.

## Reproducibility

# ShockedInvestors

Project folder for the paper on “shocked investors”: how does the credit
supply of the crowd change in response to bad news about repayment
delays.

## Workflow Tips

### GIT

-   Commit and pull/push through RStudio.

-   Create new branch (on local and remote) via RStudio. Make sure to
    commit changes to the correct branch and push before switching
    branches.

-   Merge branch to main via shell (git merge –no-f nameofbranch), shell
    asks for commit message but can just close and commit via RStudio.

-   Delete branches on local (git branch -d nameofbranch) and on remote
    (git push origin –delete nameofbranch)

-   Update branch list from remote with git fetch -p

-   data does not get uploaded (hence, folder included in .gitignore
    file)

### Renv

Renv is used to create sandboxed package versions that will be
transferable between machines. - Intitialize with (should automatically
execute when cloning this repository). - With a new repo, first to load
the package status of the (clean) renv.lock file. - When new packages
are installed or updated, save the current status with in the renv.lock
file.

### Latex

-   Changes in latex docs should be commited to git via RStudio.
-   Include auxiliary latex files in gitignore.

## Acknowledgments

This workflow was inspired by Grant McDermott’s [Git
Lecture](https://github.com/uo-ec607/lectures/blob/8809a91ff67453ef1d3cabee37aa0f564c219ed2/02-git/02-Git.pdf)
and exemplary [Git
Repository](https://github.com/grantmcdermott/skeptic-priors.git).  
Info about Git and RStudio comes from
[happy-git-with-R](https://happygitwithr.com/).  
Info about Renv from the [package
documentation](https://rstudio.github.io/renv/).
