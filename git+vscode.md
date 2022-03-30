一、安装 vscode+git 软件

二、源代码管理操作

（一）提交修改；

（二）推送代码；

（三）添加 GitHub 仓库；

（四）GitHub 创建新仓库；

（五）推送本地更改的文档至对应分支；

（六）vscode --master 左下角云更新。(更新慢的话使用终端 git push -u origin master 指令推送)

三、GitHub 连接超时解决办法

（一） 进入网址 www.ipaddress.com
搜索栏搜索 输入 github.com 和 github.global.ssl.fastly.net 查询相应的 IP 地址

（二）将相应的最新 IP 地址写进 hosts 文件
形如：

#Github

140.82.113.3 https://github.com

199.232.69.194 https://github.global.ssl.fastly.net

（三）刷新 DNS
打开 cmd,输入 ipconfig /flushdns

四、鉴于 GitHub 网速慢，使用 gitee 替换
