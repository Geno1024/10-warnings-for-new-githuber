# 给 GitHub 新手的 10 个警告

事实上，可能不止 10 个吧。

0. 我使用 github 来将一些提交推送到 git。
 - git 是一个工具，GitHub 是一个提供与 Git 相关功能的服务器。
 - 注意大小写。GitHub 的 G 和 H 是大写的。

1. 我的 GitHub 页面报了 404。
 - 等待 10 分钟。第一次使用 GitHub Pages 功能时，GitHub 需要大约 10 分钟来做一些关于域名（？）的（什么？）事。
 - 检查一下你的邮箱。你的邮箱可能会收到一些错误消息之类，按照里面的提示去解决问题，例如验证邮箱之类。

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

4. I can't do ??thing on Tortoise Git/SourceTree/GitHub for Windows etc.
 - You should learn command line git(Git Bash) first, to understand what you are doing, what you should do, and, what the GUI is doing.

5. 
