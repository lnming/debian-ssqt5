
# Debian系列linux安装shadowsocks-qt科学上网
## 准备工作
* 该项目提供了热门科学上网软件SS的可用桌面版和android版本软件 
* 在Debian系列linux下安装shadowsocks-qt5科学上网的需要Deb包 

## 安装步骤
* 安装需要的依赖包

`` $ sudo apt-get install qt5-qmake qtbase5-dev libqrencode-dev libappindicator-dev libzbar-dev libbotan1.10-dev ``

* 安装项目中提供的三个Deb包，分别是libqtshadowsocks,libqtshadowsocks-dev和shadowsocks-qt5,安装命令如下:

``` 
$ sudo dpkg -i libqtshadowsocks_1.9.0-1_amd64.deb
$ sudo dpkg -i libqtshadowsocks-dev_1.9.0-1_amd64.deb
$ sudo dpkg -i shadowsocks-qt5_2.7.0-1_amd64.deb
```
## 测试使用
* 运行shadowsocks-qt5,填好你的ss信息和win下配置差不多，配置好后用浏览器试试是否可行，若可以，那么恭喜，若不行（gfwlist无法更新缘故），就试试下面：
* 在chrome扩展程序里面添加 Proxy SwitchyOmega 这个程序，上网查看配置方法，弄好之后，基本上就没啥问题了。
