# REPO OVERVIEW, git-demo
Practical demonstration for the 2024 lecture, _Good enough computational practices; data sharing, reproducible code, version control_ delivered in November, 2024 and the MRC Cognition and Brain Sciences Unit. 

## Contact

* Matthew Richards (matthew.richards@mrc-cbu.cam.ac.uk)
* Lukas Gunschera (lukas.gunschera@mrc-cbu.cam.ac.uk)

## Activity

1. Download Microsoft VS Code, [here](https://code.visualstudio.com/download). 
    - If you are on a Windows machine, you may also need to download the Git client, [here](https://git-scm.com/downloads/win). 
    - On Mac OS, there are a few options. The lightest is the binary, installable [here](https://sourceforge.net/projects/git-osx-installer/).
    - Linux distros usually have Git pre-bundled.
2. Open VS code and go to `source control` on the left panel
<!-- ![enter-credentials](/img/source-control-clone.png "clone1") -->
<img src="/img/source-control-clone.png" height="250">

3. Select `clone repository` __git-demo__ (NB. enter the URL source if required, https://github.com/mrhons-cbu/git-demo.git)
<img src="/img/clone-repo.png" width="500">

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