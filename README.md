# How-to-use-Git-Bash (Simplified for you):

### How to check your Git configuration:
#### The command below returns a list of information about your git configuration including user name and email:
## git config -l

### How to setup your Git username:
#### With the command below you can configure your user name:
## git config --global user.name "Your-User-Name_here"

### How to setup your Git user email:
#### This command lets you setup the user email address you'll use in your commits.
## git config --global user.email "your_email_here@Mail-Host.com"

### How to cache your login credentials in Git:
#### You can store login credentials in the cache so you don't have to type them in each time. Just use this command:
## git config --global credential.helper cache
