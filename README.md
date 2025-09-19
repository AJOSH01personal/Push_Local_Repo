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

If you don't have GitHub CLI, it is highly suggested to download it and have it ready beforehand as it will make the process easy.

Once this is all said and done you are ready to push the initial README.md file and other contents of your local repo to GitHub.

Sources:
- <https://gist.github.com/alexpchin/dc91e723d4db5018fef8?permalink_comment_id=5035886#gistcomment-5035886>
- <https://stackoverflow.com/questions/2432764/how-do-i-change-the-uri-url-for-a-remote-git-repository>

Happy Gitting! :tada:
