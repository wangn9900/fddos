# 使用教程
## 本脚本来自DDoS deflate 官方地址：http://deflate.medialayer.com/
### 输入以下命令
```
// 下载DDoS Deflate
wget https://raw.githubusercontent.com/wangn9900/fddos/main/install.sh
// 添加权限
chmod 0700 install.sh
// 执行安装脚本
// 安装完成后会有一段版权提示与说明，按q键退出即可。
./install.sh
// 执行完删除脚本
rm -f install.sh
```
#### 如有以下提示
root@fexxe:~# ddos -c
/usr/local/sbin/ddos: 13: [: /usr/local/ddos/ddos.conf: unexpected operator
DDoS-Deflate version 0.6
Copyright (C) 2005, Zaf <zaf@vsnl.com>

$CONF not found.

输入vi /usr/local/ddos/ddos.sh 将#!/bin/sh 改成 #!/bin/bash 保存退出

## 启动命令
``` 
ddos -c
```
无报错即表示正确运行！
