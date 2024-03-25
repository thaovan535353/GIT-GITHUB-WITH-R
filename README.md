# GIT-GITHUB-WITH-R
## Step by step for connect git with RStudio
- To create an account on GITHUB
- To download Git for windows: https://git-scm.com/download/win
- To check installed git with `git version` on terminal of windows
- To connect RStudio with github account:
     - RStudio: Tools -> Global options -> Git/SVN -> create SSH key -> click on Create -> click on View public key and copy all
     - Github: Click on your profil icon -> Settings -> SSH and GPG keys -> New SSH key -> paste key and click on add SSH key
- To create a project on Github: Click on your profil icon -> your repositories -> New -> fil in and click on repository
- To connect RStudio to your created project on Github:
     - Github: click on `code` -> SSH -> copy code
     - RStudio: File -> New project -> Version Control -> Git -> paste code into Repositiory URL -> continue to paste the same code into `password` -> tape `yes` -> OK
