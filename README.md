## Demonstration purpose only
# This is an example project to demonstrate gradle package reference from GitHub Package Repository
To be able to restore packages from GitHub package repo, it is necessary to authenticate using your GitHub username and a Personal Access Token (PAT).
1. When logged in to GitHub, generate the PAT under 
  - Settings 
  - -> Developer Settings
  - -> Personal Access Tokens
  - -> Generate new token  (enable "read:packages")
1. Write your username, the personal access token and the name of the repo into a file called ```github.properties``` in the root of your project. (make sure to include that file in .gitignore to avoid exposing your PAT)
>gpr.usr=GITHUB_USERID
>gpr.key=PERSONAL_ACCESS_TOKEN
>gpr.repo=NAME_OF_THE_REPO
