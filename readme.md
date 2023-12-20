## HELLO in Learning git environment

### Initial Step for setting up your working Directory
1. mkdir <YOUR_WORKING_DIRECTORY>
2. cd <YOUR_WORKING_DIRECTORY>
3. git init

### How to add your local working dir to GITHUB
1. install the gh CLI [click_here](https://github.com/cli/cli/blob/trunk/docs/install_linux.md#official-sources)
2. export GH_TOKEN="YOUR_GITHUB_ACCESS_TOKEN"
3. to bypass the prompt
   '' 
   gh repo create my-project --public --source=. --remote=<YOUR_WORKING_DIRECTORY>
   ''
4. for more info related to options [click_here](https://cli.github.com/manual/gh_auth_login)
