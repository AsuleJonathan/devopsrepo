# devopsrepo
just a sample repo
## initialize git inside your project folder and make your first commit:
git init
git add .
git commit -m "initial commit"

## Create a remote, empty folder/repository on Github.

Login to your Github account.

At the top right of any Github page, you should see a '+' icon. Click that, then select 'New Repository'.

Give your repository a name--ideally the same name as your local project.

Click 'Create Repository. 

## Connect your local project folder to your empty folder/repository on Github.

Copy the link in the input right beneath the title, it should look something like this: https://github.com/yourname/yourproject.git

This is the web address that your local folder will use to push its contents to the remote folder on Github.

Go back to your project in the terminal/command line.

In your terminal/command line, type git remote add origin [copied web address] Example: git remote add origin https://github.com/yourname/yourproject.git

Push your branch to Github: git push -u origin main

