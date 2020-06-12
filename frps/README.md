Frp-Server
===========
##作为frp的搬运工。


##感谢[fatedier/frp](https://github.com/fatedier/frp)提供这么优秀的软件 
##感谢clangcn提供一键安装脚本
frp 是一个高性能的反向代理应用，可以帮助您轻松地进行内网穿透，对外网提供服务，支持 tcp, http, https 等协议类型，并且 web 服务支持根据域名进行路由转发。

安装平台：CentOS、Debian、Ubuntu。


Server
------

### Install

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/zhyreng/onekey-install-shell/master/frps/install-frps.sh -O ./install-frps.sh
chmod 700 ./install-frps.sh
./install-frps.sh install
```

### UnInstall
```Bash
    ./install-frps.sh uninstall
```
### Update
```Bash
    ./install-frps.sh update
```
### 服务器管理
```Bash
    Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```

