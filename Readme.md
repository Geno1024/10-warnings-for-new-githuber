# 10 Warnings For New GitHuber

Actually, more than 10, maybe.

1. My GitHub Pages reported 404.
 - Wait for 10 minutes.
 - Check your email.

2. I want to get updates from fork base.
 - You can see a sentence "This branch is ? commit(s) before..." in a blue box on the top of the file list in your repo page, with a "Pull Request" in the right. Use it, create a pull request from the fork source(which is called upstream) to your repo.

3. I can't push to the remote.
 - Is it report this?
 ```
 To .../remote/
  ! [rejected]		master -> master (non-fast forward)
 error: failed to push some refs to '.../remote/'
 ```
 - After solved this, you should use `git pull` before continuing your work, every time when you change your working position.
 - But now, you should solve it first. You can:
   - `git push -f` to force push.
   - or `git pull`
   - or equally, `git fetch` then `git merge`.
