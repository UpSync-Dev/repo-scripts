# `main` branch protection

## protect-main-branch.sh
* Shell script to enable branch protection on the `main` branch
* What this script does:
    - Disables direct commits and pushes to the `main` branch 
    - Applies all the changes for all users including admins
    - Requires a pull request to be created which can then be merged into `main`
* Full details and a write up can be found at [upsync.dev](https://www.upsync.dev/2022/01/14/github-branch-protection.html)
