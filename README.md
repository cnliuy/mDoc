位置 E:\Java\ttt





-----------------------

Git Gui创建远程上传GitHub方法

  1. Git Gui 中创建远程remote时，先使用 Git Gui 的“帮助”---> "Show SSH Key" 创建key

  2.将key复制到GitHub中，个人Settings中---> “SSH keys”里 “Add SSH key”，并确认通过

  3.在Git Gui 中点开 repository---> Git Bash，输入命令
	$ git remote  add yourprojectname git@github.com:yourgithubnanme/yourprojectname.git

  4.重启Git Gui

  5.在remote中，看到相应 yourprojectname 的选项 ，想与github同步，点 remote--->上传 即可.

------------------------


http://nathanj.github.io/gitguide/tour.html
  An Illustrated Guide to Git on Windows 
  介绍 Git Gui使用的文档

http://blog.csdn.net/yaoyuan_difang/article/details/17353043
  使用Git、Git GUI和TortoiseGit
	
http://www.jb51.net/article/55438.htm
  “进入GitHub网站 : 登录GitHub, 选择Account Setting 用户设置” 这里可参考下




--EOF--
