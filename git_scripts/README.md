#Git Scripts

## post-commit

A post commit hook to automatically push the commit to remote branch.

Recently one of my machines stopped working and I lost a week's worth of code because I hadn't pushed my changes to remote. This is to help me ensure I don't run into the same situation again.

### Setting it up:

I followed these steps to set it up on mac but I _believe_ it should work on Windows too.
1. Create a file `.git/hooks/post-commit` in your repo.
2. Paste the content of the `post-commit` file from this folder.
3. Mark the file executable. ( `chmod +x .git/hooks/post-commit` for me).
4. Make some changes and commit them to verify that the hook is triggered.

source: [Stackoverflow](https://stackoverflow.com/questions/7925850/how-can-i-automatically-push-after-committing-in-git)
