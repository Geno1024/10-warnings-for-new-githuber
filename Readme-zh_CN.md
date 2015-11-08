# 给 GitHub 新手的 10 个警告

事实上，可能不止 10 个吧。

0. 我使用 github 来将一些提交推送到 git。
 - git 是一个工具，GitHub 是一个提供与 Git 相关功能的服务器。
 - 注意大小写。GitHub 的 G 和 H 是大写的。

1. 我的 GitHub 页面报了 404。
 - 等待 10 分钟。第一次使用 GitHub Pages 功能时，GitHub 需要大约 10 分钟来做一些关于域名（？）的（什么？）事。
 - 检查一下你的邮箱。你的邮箱可能会收到一些错误消息之类，按照里面的提示去解决问题，例如验证邮箱之类。

2. 我想获取 Fork 的源仓库（base）的更新。
 - 你能在你的仓库的页面的文件列表上方的蓝色方框中看到一句类似于“This branch is ? commit(s) before...”的话，右边有个“Pull Request”。嗯，使用它，从源仓库（也被称为“上游”）向你的仓库创建一个 Pull Request，并合并它。

3. 我无法推送。
 - 它是否报出了以下类似的内容？
 ```
 To .../remote/
  ! [rejected]		master -> master (non-fast forward)
 error: failed to push some refs to '.../remote/'
 ```
 - 在解决了这个问题之后，请紧记一点：每次更换工作地点之后，开始工作之前要用一下 `git pull`。
 - 但是现在，你急需的是解决这个问题。你可以：
   - `git push -f` 来强推。
   - 或者 `git pull`
   - 或者相等地，`git fetch` 然后 `git merge`。

4. 我用的是 Tortoise Git/SourceTree/GitHub 客户端，现在我没法做……。
 - 建议先学 Git 的命令行(Git Bash)吧，了解一下你在做什么，需要做什么，以及，那些图形界面在做什么。

5. 
