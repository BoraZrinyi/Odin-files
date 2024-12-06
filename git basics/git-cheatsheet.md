**This is a reference list of the most commonly used Git commands.**

Commands related to a remote repository:
git@github.com:BoraZrinyi/git_test.git
git push
git push origin main
(Both accomplish the same goal in this context)


Commands related to the workflow:
git add .
git commit -m "A message describing what you have done to make this snapshot different"

Commands related to checking status or log history
git status
git log

**The basic Git syntax is program | action | destination.**

For example,

git add . is read as git | add | ., where the period represents everything in the current directory;
git commit -m "message" is read as git | commit -m | "message"; and
git status is read as git | status | (no destination).
