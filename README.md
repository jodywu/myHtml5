# myHtml5
123

Microsoft Windows [版本 6.1.7601]
版权所有 (c) 2009 Microsoft Corporation。保留所有权利。

C:\Users\Administrator>git --version
git version 2.7.2.windows.1

C:\Users\Administrator>git config --global user.name "jodywu"

C:\Users\Administrator>git config --global user.email "1459944939@qq.com"

C:\Users\Administrator>cd D
系统找不到指定的路径。

C:\Users\Administrator>cd /

C:\>dir
 驱动器 C 中的卷没有标签。
 卷的序列号是 0628-50F6

 C:\ 的目录

2016/04/26  22:40    <DIR>          AMD
2016/08/07  23:02    <DIR>          Apps
2009/07/14  11:20    <DIR>          PerfLogs
2016/07/16  16:11    <DIR>          Program Files
2016/08/07  21:57    <DIR>          Program Files (x86)
2016/04/26  23:11    <DIR>          QMDownload
2016/04/26  22:32    <DIR>          swsetup
2016/04/26  23:19    <DIR>          Users
2016/08/28  22:16    <DIR>          Windows
               0 个文件              0 字节
               9 个目录 219,147,157,504 可用字节

C:\>mkdir jodywu

C:\>cd jodywu

C:\jodywu>git clone https://github.com/jodywu/myHtml5.git
Cloning into 'myHtml5'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.

C:\jodywu>dir
 驱动器 C 中的卷没有标签。
 卷的序列号是 0628-50F6

 C:\jodywu 的目录

2016/08/28  22:41    <DIR>          .
2016/08/28  22:41    <DIR>          ..
2016/08/28  22:41    <DIR>          myHtml5
               0 个文件              0 字节
               3 个目录 219,147,108,352 可用字节

C:\jodywu>explorer .

C:\jodywu>cd myhtml5

C:\jodywu\myHtml5>git -m "123"
Unknown option: -m
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

C:\jodywu\myHtml5>git commit -m "123"
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
        modified:   README.md

no changes added to commit

C:\jodywu\myHtml5>git add *
warning: CRLF will be replaced by LF in README.md.
The file will have its original line endings in your working directory.

C:\jodywu\myHtml5>git commit -m "123"
[master warning: CRLF will be replaced by LF in README.md.
The file will have its original line endings in your working directory.
8954a0b] 123
warning: CRLF will be replaced by LF in README.md.
The file will have its original line endings in your working directory.
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\jodywu\myHtml5>git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Username for 'https://github.com': jodywu
Password for 'https://jodywu@github.com':
Counting objects: 3, done.
Writing objects: 100% (3/3), 244 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/jodywu/myHtml5.git
   cab5ab0..8954a0b  master -> master

C:\jodywu\myHtml5>git pull
Already up-to-date.

C:\jodywu\myHtml5>

















































































































































































