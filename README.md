# mysql
mysql数据库安装以及使用
# MySQL 安装 Linux版本
1.添加apt储存库：
- 下载deb文件:
[下载链接](https://dev.mysql.com/downloads/repo/apt/)
- 安装：
`sudo dpkg -i /PATH/version-specific-package-name.deb`
- 更新软件库：`sudo apt-get update`  

2.安装mysql服务：
- `sudo apt-get install mysql-server`  

3.启动和停止服务：  
- 检查服务器状态：`sudo service mysql status`
- 停止服务器：`sudo service mysql stop`
- 启动服务器：`sudo service mysql start`  

4.选择版本：
- `sudo dpkg-reconfigure mysql-apt-config`
- `sudo apt-get update`

# 问题解决：查看wiki页
