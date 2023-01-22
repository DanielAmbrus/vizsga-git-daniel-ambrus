Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga (main)
$ git clone https://github.com/szabopeter92/git-vizsga0104
Cloning into 'git-vizsga0104'...
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (15/15), done.
remote: Total 15 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (15/15), 14.06 MiB | 3.02 MiB/s, done.

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git init
Reinitialized existing Git repository in C:/Users/Daniel/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104/.git/

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git commit -m "readme.md és .gitignore létrehozása"
[main 5c3de99] readme.md és .gitignore létrehozása
 2 files changed, 4 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git branch console

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git checkout console
Switched to branch 'console'

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git commit -m "üzenet hozzáadása a konzol-hoz"
[console f714270] üzenet hozzáadása a konzol-hoz
 1 file changed, 4 insertions(+)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git commit -m "oldal háttérszínének változtatása css-ben"
[console 706f1bf] oldal háttérszínének változtatása css-ben
 1 file changed, 1 insertion(+), 1 deletion(-)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git branch
  console
* main