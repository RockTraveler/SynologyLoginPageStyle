### [English](https://github.com/RockTraveler/SynologyLoginPageStyle/blob/main/README.md) |中文

# SynologyLoginPageStyle

## 介绍


此项目是修改了群晖NAS的登录界面，这个CSS能让登录面板看起来更顺眼一点

### 备注
CSS脚本基于DSM7.0而修改，之前的版本应该是不能用。

## 使用方法

1. 下载CSS文件
2. 使用SSH工具登录你的群晖设备，后续操作需要root 权限。
3. 在操作之前，请备份你的css文件，将login.css文件覆盖到此目录下：/usr/syno/synoman/webman/login/css,
4. 将目录下的login.css.gz改名，如login.css.gz_bak
5. 刷新你的登录页面看看效果

## 相关命令

1. 进入目录 /usr/syno/synoman/webman/login/css:  cd /usr/syno/synoman/webman/login/css
2. 切换到ROOT 用户 （需要密码）: sudo -i
3. 备份文件: mv 文件名  新文件名
4. 将文件放入目录 /usr/syno/synoman/webman/login/css: cp /路径/文件名 /usr/syno/synoman/webman/login/css
5. 修改文件名称从 login.css.gz 到另外一个名称: mv login.css.gz 新文件名称

## 样例:

### 修改之前
![image](https://github.com/RockTraveler/SynologyLoginPageStyle/blob/main/example/before.png)

### 修改之后

![image](https://github.com/RockTraveler/SynologyLoginPageStyle/blob/main/example/after.png)


各位土豪或者大佬，想请喝杯咖啡的话，请扫描下面的二维码：

![image](https://github.com/RockTraveler/SynologyLoginPageStyle/blob/main/example/alipay.png)
