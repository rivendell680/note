## kali

### 更新
```
apt update
```

### 时区
```
dpkg-reconfigure tzdata
```

Asia->Shanghai

### 中文
```
apt install xfonts-intl-chinese
apt install fonts-wqy-microhei
apt install ttf-wqy-microhei
```

### 实用工具

```
apt install htop
apt install jnettop
vi /etc/proxychains.conf
socks5 192.168.179.1 1080
#proxy_dns 注释掉
```

### python

```
https://github.com/pyenv/pyenv
sudo apt install libedit-dev
python -V
pyenv local 3.8.0
pip -V
```

### vscode
```
deb包
dpkg -i code_XXXXX.deb
```

### nodejs

```

```

### frida
特定版本
```
pip install frida==12.8.0
pip install frida-tools==5.3.0
pip install obejection==1.8.4
```
```
https://github.com/frida/frida/releases

https://github.com/oleavr/frida-agent-example

$ git clone https://github.com/oleavr/frida-agent-example.git
$ cd frida-agent-example/
$ npm install
$ frida -U -f com.example.android -l _agent.js


https://github.com/sensepost/objection/releases


wifiadb
```
