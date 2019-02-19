# Python3-CentOS

How to install Python3 on CentOS



1. Download file with wget
2. Unzip file
```sh
wget https://www.python.org/ftp/python/3.4.3/Python-3.4.3.tar.xz

tar xf Python-3.* 
cd Python-3.*
```

3. Prepare configurations

```sh

$ ./configure

```

4. Build the file

```sh

make

```

5. Install python3

```sh

make install

```


Dependencies:
```sh
yum install openssl-devel
In addition it is recommended to install the following.

yum install zlib-devel bzip2-devel sqlite sqlite-devel openssl-devel
```
