## 1. apt-get source    
```
阿里云Ubuntu 18.04源
deb http://mirrors.aliyun.com/ubuntu/ bionic main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ bionic-security main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ bionic-updates main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ bionic-proposed main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ bionic-backports main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ bionic main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ bionic-security main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ bionic-updates main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ bionic-proposed main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ bionic-backports main restricted universe multiverse
```
## 2. git    
ssh keygen
## 3. node    
## 4. python    
```
1. sudo apt-get install python3
2. sudo apt-get install python3-pip
3. sudo python3 get-pip.py
```
1. Update pip source.
```
1. 在主目录下创建.pip文件夹
mkdir ~/.pip
2.然后在该目录下创建pip.conf文件编写如下内容：
[global]
trusted-host =  pypi.douban.com
index-url = http://pypi.douban.com/simple
```
## 5. docker    
1. [docker config](https://docs.docker.com/v1.11/engine/reference/commandline/daemon/#daemon-configuration-file)
```
镜像默认存储地址：/var/lib/docker
daemon配置文件:/etc/docker/daemon.json
"graph":"",    "Root of the Docker runtime" 修改/var/lib/docker
"storage-driver":"overlay"        "需要和上一条配置成对出现否则会出现Error：mount merge invaild argument"
```
2. [Docker的镜像存放目录修改与迁移（Ubuntu）](https://my.oschina.net/u/2306127/blog/653569)

## 6. 系统相关    
1. [Ubuntu 16.04开机自动挂载硬盘分区（转）](https://www.cnblogs.com/EasonJim/p/7447000.html)  
2. []
