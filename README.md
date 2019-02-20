# Python3-CentOS

How to install Python3 on CentOS


Install the Dependencies:
```sh

yum install wget –y
wget https://dl.fedoraproject.org/pub/epel/7/x86_64/Packages/e/epel-release-7-11.noarch.rpm
rpm –ivh epel-*.rpm
yum install python36

sudo yum install python34-setuptools
sudo mkdir /usr/local/lib/python3.6
sudo mkdir /usr/local/lib/python3.6/site-packages

sudo easy_install-3.6 pip
```

Activate the environment

```sh
pyvenv-3.6 py3
source py3/bin/activate
```
