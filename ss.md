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

original git configurations(Mac OSX, Air):

```
credential.helper=osxkeychain
user.name=Wasdns
user.email=952693358@qq.com
push.default=matching
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
```

git configuration:

```
$ git config --global http.proxy 'socks5://127.0.0.1:1080' 
$ git config --global https.proxy 'socks5://127.0.0.1:1080'
```
