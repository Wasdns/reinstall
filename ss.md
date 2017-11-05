## Guide

ss:

```
$ sudo apt-get update
$ sudo apt-get install python-pip
$ sudo apt-get install python-setuptools m2crypto
$ pip install shadowsocks
```

ss-qt5:

```
$ sudo add-apt-repository ppa:hzwhuang/ss-qt5
$ sudo apt-get update
$ sudo apt-get install shadowsocks-qt5
```

git configuration:

```
$ git config --global http.proxy 'socks5://127.0.0.1:1080' 
$ git config --global https.proxy 'socks5://127.0.0.1:1080'
```
