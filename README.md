<h1>Setting up the repo from command line:</h1>
https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line

tl;dr

#Initialize
$ git commit -b main

#Stage and commit initial
$ git add .
$ git commit -m "initial commit"

# Add new remote
$ git remote add origin  <REMOTE_URL> 

# Verify the new remote URL
$ git remote -v

#push changes to new main branch
$ git push origin main
