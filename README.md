# raspberry-pi

## 远程管理Raspberry Pi

### 在树莓派上安装Tight VNC
sudo apt-get install tightvncserver

### 启动VNC服务器
vncserver :1

第一次启动会要求创建一个密码

### 在远程计算机访问树莓派
下载VNC-Viewer(https://www.realvnc.com/download/viewer/)或者tightvnc(http://www.tightvnc.com/download.php)
推荐后者，感觉比较流畅

打开VNC-Viewer或者TightVNC Viewer，输入host:port如(192.168.1.107:1)，输入密码

### 关闭VNC服务器
vncserver -kill :1

### 开机自启动
参考http://shumeipai.nxez.com/2013/09/04/login-rpi-with-vnc.html?variant=zh-cn
