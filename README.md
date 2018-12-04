# CentOS 7-学习
使用linux系统运行程序相关学习

## 安装centOS7
### 1.下载CentOS7 DVD版本
### 2.虚拟机安装
### 3.配置网络
vi /etc/sysconfig/network-scripts/ifcfg-ens33
修改ONBOOT=yes



## nodejs安装
### 1.获取nodejs
wget https://npm.taobao.org/mirrors/node/v11.0.0/node-v11.0.0.tar.gz
### 2.解压
tar -xvf node-v11.0.0.tar.gz
### 3.进入目录安装相关插件
cd node-v11.0.0
sudo yum install gcc gcc-c++
### 4.默认配置编译
./configure
make
### 5.安装
make install
### 6.查看版本
node -v
