Welcome to the Push-2-GitHub-without-making-a-remote-repository README.md file.
(i.e. the slightly sneaky way to do some introductory Git and GitHub stuff without going to GitHub.)

The steps I took to do this without interacting with GitHub:

1. Create your repo locally in Git Bash.
2. Set the url of the local repo to your github page.
(use this command: git remote set-url <https://github.com/(username)/(reponame).git>)
(example: git remote set-url <https://github.com/AJOSH01Personal/MyRepo.git>)
3. After this is set use GitHub CLI commands to create a repo without touching the GitHub website:
- gh auth login [For Authentication Purposes]
- gh repo create [repo name] --[flag]
where repo name is the one you've assigned when you used git remote set-url
and flag is set to either public or private repositories respectively.

Once this is all said and done you are ready to push the initial README.md file and other contents of your local repo to GitHub.

Happy Gitting! :tada:
