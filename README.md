# Learning-Notesadd
开始运行git时要进行全局配置：
git config --global user.email "707494516@qq.com"
git config --global user.name "Joa"


首先，在github网页上新建一个Repository，成功之后在shell进入相应的目录下克隆你创建的Repository的SSH秘钥
在电脑的相应目录下拷贝要上传的文件
在shell下输入git add .
再git commit -am "写你要上传文档的一个提示信息"
git push origin master:master　//创建分支的映射（如果在新建一个Repository时，勾选上ReadMe，则这一步就不需要做了）　
git push 

具体操作命令见http://www.csdn.net/article/2014-06-17/2820265-git
