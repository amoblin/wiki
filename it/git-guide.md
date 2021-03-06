# Git 快速指南

# 创建公私钥对

Windows下首先下载安装[babun](http://babun.github.io/)，然后打开babun终端；

Linux和OSX下直接打开终端即可。

终端下输入下面命令来创建公私钥对。

```
ssh-key-gen -t rsa
```
一直回车，结束后把公钥文件 *id_rsa.pub* 提交给git库管理员，而私钥文件 *id_rsa* 不要移动，妥善保存。

git库管理员告诉你git库地址，然后 git clone下来即可。



# 参考资料
- http://rogerdudler.github.io/git-guide/index.zh.html
- http://marklodato.github.io/visual-git-guide/index-zh-cn.html

# 从SVN迁移到Git
## 将SVN库克隆到本地git库

```
git svn clone -s svn://svn-dir
```

# Git Hooks

[使用 Git Hooks 实现自动项目部署](http://www.icyleaf.com/2012/03/apps-auto-deploy-with-git/)

http://xydudu.calepin.co/git-server-and-hook.html

# Git Flow & Github Flow

[GIT FLOW 和那些 GIT WORKFLOWS](http://www.fallhunter.com/p/10732/comment-page-1)

[在 GitHub 當中使用的 work flow](http://blog.krdai.info/post/17485259496/github-flow)

[git flow](http://jwch.sdut.edu.cn/book/linux/git_flow.html)


[Git分支管理策略 by 阮一峰](http://www.ruanyifeng.com/blog/2012/07/git.html)

[你为神马不用git-flow呢?](http://www.jeffkit.info/2010/12/860/)

[关于 Git 工作流的随笔](https://blog.tonyseek.com/post/jottings-about-git-flow/)



https://www.atlassian.com/pt/git/workflows#!workflow-gitflow

http://roclinux.cn/?p=2129
