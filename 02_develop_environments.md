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
