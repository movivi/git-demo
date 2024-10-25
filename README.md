# git-demo
Demo for CBU Nov 2024 git lecture

## Activity

1. Download Microsoft VS Code, (here)[https://code.visualstudio.com/download]
2. Open VS code and go to `source control` on the left panel
![enter-credentials](/img/source-control-clone.png "clone1")
3. Select `clone repository` **git-demo** (NB. enter the URL source if required, https://github.com/mrhons-cbu/git-demo.git)
![clone2](/img/clone-repo.png "Clone repository via source")
4. Create a repository destination (e.g., ~/Desktop)
5. If prompted, allow trust to authors of the rep (will just contain text files, no executables)
6. Configure git credentials in environment. Select the 'terminal' (bottom section of window):
    `git config --global user.name "[firstname lastname]"`

    `git config --global user.email "[valid-email]"`
![enter-credentials](/img/config-cred.png "Credentials via git terminal")
7. Browse directory in 'file explorer' section (select on left panel)
8. Create a new file with your name (e.g., `matt.txt`) and enter some secret message
![enter-credentials](/img/config-cred.png "Credentials via git terminal")
9. Return to the `source control` section (left in vscode window), select files that have been changed, and select `commit`.
10. Select 'sync changes' and select 'OK' about pushing to `origin/master`