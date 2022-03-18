# Co-auth-commits script
A simple script to make co-authored git commits
## Before you can use this script 
Since git automatically knows you're an "author" edit the script and remove your name. That way you don't show up as a co-author. Don't worry you'll still get credit for the commit. You'll only have to do this once assuming you don't change the script back to it's original format. 

**Verify your email is correct if not let me know and I can update it.**

Lastly, make sure the script has executable permissions

`chmod +x ./co_auth_commits.sh`

## How to use this script?

This script replaces the `git commit` command you would normally use. So instead of running that command run this script

Example:

`git add <your files here>`

then

`./co_auth_commits.sh` 

You will be prompted for a commit message just hit enter when done.

Afterwords your welcome to push to a remote branch like normal.

---
*Note you'll probably want to add this to a git ignore file when we get to that point!*