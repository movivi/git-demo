# REPO OVERVIEW, git-demo
Practical demonstration for the 2024 lecture, _Good enough computational practices; data sharing, reproducible code, version control_ delivered in November, 2024 and the MRC Cognition and Brain Sciences Unit. 

## Contact

* Matthew Richards (matthew.richards@mrc-cbu.cam.ac.uk)
* Lukas Gunschera (lukas.gunschera@mrc-cbu.cam.ac.uk)

## Exercise 1: Setup repository and first commit!

1. Download Microsoft VS Code, [here](https://code.visualstudio.com/download). 
    - If you are on a Windows machine, you may also need to download the Git client, [here](https://git-scm.com/downloads/win). 
    - On Mac OS, there are a few options. The lightest is the binary, installable [here](https://sourceforge.net/projects/git-osx-installer/).
    - Linux distros usually have Git pre-bundled.
2. Open VS code and go to `source control` on the left panel
<!-- ![enter-credentials](/img/source-control-clone.png "clone1") -->
<img src="/img/source-control-clone.png" height="250">

3. Login to https://github.com/, select __create new repository__, enter a name (e.g., 'test') and click, 'create repository'. Select `clone repository` __git-demo__ (NB. enter the URL source if required, (can get the URL from the github of your new repository page).
<img src="/img/clone-repo.png" width="500">

<img src="/img/repo-link.png" width="500">

4. Create a repository destination (e.g., ~/Desktop)
5. If prompted, allow trust to authors of the rep (will just contain text files, no executables)
6. Configure git credentials in environment. Select the 'terminal' (bottom section of window):
    
    `git config --global user.name "[firstname lastname]"`

    `git config --global user.email "[valid-email]"`
<!-- ![enter-credentials](/img/config-cred.png "Credentials via git terminal") -->
<img src="/img/config-cred.png" width="500">

7. Browse directory in 'file explorer' section (select on left panel)
8. Create a new file with your name (e.g., `matt.txt`) and enter some secret message
<img src="/img/newfile.png" width="500">

9. Return to the `source control` section (left in vscode window), select files that have been changed, add a MESSAGE, and select `commit`.
<img src="/img/commit.png" height="250">

10. Select 'sync changes' and select 'OK' about pushing to `origin/master`

## Exercise 2: Create a New Branch and Commit Changes

1. Ensure you are in the 'source control' section (left in vscode window).

2. Click on the branch name in bottom left corner of VS Code, should say `main` unless changed already.

3. A drop-down window will appear at the top of the screen, select __+ create new branch__ and enter a name, e.g., `first-branch`.
<img src="/img/newbranch.png" width="500">

4. This will automatically switch you to the new branch.

5. Open your existing file and make some changes. Save the file when done.

6. Stage the changes by clicking the '+' icon for the file, and add a message. Then click, commit (checkmark) to commit the staged changes.

## Exercise 3. Switch between branches

1. Look at the bottom-left corner of the VS Code window, where the current branch name is displayed (e.g., `first-branch`).

2. Click on the branch name and select main from the list to switch back to the main branch.

3. Notice that the changes you made in first-branch are no longer visible in your files.

4. You can switch back to feature-update at any time by clicking the branch name in the bottom left again and selecting feature-update.

## Exercise 4. Check differences between files/branches

1. In the Source Control panel, make additional changes to a file.

2. To check the differences between this new change and the last commit, click on the file name under Changes. VS Code will open a split view showing the differences (known as a diff) between the current state and the last committed version.

3. Right click on the old commit and say 'view changes'.

<img src="/img/branch-changes.png" width="500">

4. VS Code will open a new tab showing differences between your current branch (`first-branch`) and main.

## Exercise 5. Merge branches

1. Ensure you are currently on the main branch. If not, click the branch name in the bottom-left corner and select main.

2. Click the three dots (...) in the Source Control panel and select Merge Branch....

<img src="/img/merge-branch.png" width="500">

3. Choose first-branch from the list to merge it into main.

4. If there are no conflicts, your branches will be merged, and the changes from first-branch will now appear in main.

5. Check the file on the main branch to confirm that the changes from first-branch are now present.

6. Commit and sync changes to merge the branches on the online repository.

## Exercise 6. Checkout an old commit

1. If you want to roll back to an old version/commit of your code, right click on your desired commit and click `checkout detatched`. 

2. Jump between commits to see changes; reverting to a checkout of your latest commit.

<img src="/img/checkout-old-branch.png" width="500">

## Exercise 7 (bonus). Clone an existing repository

1. Attempt to clone the repository used for this presentation. (NB. enter the URL source if required, https://github.com/mrhons-cbu/git-demo.git).

2. Create a new branch.

3. Make a change to that branch file and commit those changes.

4. Compare the differences.


## Further git exercises

Further Git (excellent R-oriented) exercises courtesy of Nicola Rennie https://nrennie.rbind.io/training-git-r/examples.html


