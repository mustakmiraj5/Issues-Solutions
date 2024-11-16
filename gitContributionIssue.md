**Github account is not adding any contrubution in the graph except creating a repository.**

You need to make sure that your local repository and the public repository in the github are same.
In order to verify your local repository email write this command in the bash : `git config --global user.email`
in order to change your local email write in the bash : `git config --global user.email  "your email"`
This will do the job now commit and it will show in the graph.

**Clone a specific branch**

`git clone --branch [branch name] --single-branch [ripository link]`

What each option does -
> --branch: spicifies the branch to clone.
> --single-branch: ensures only the spicified branch is cloned instead of all branches. 