# nginx一键安装

执行安装脚本：


```bash
wget -O auto_ssl.sh https://raw.githubusercontent.com/lisi-123/nginx-fs/main/auto_ssl.sh
chmod +x auto_ssl.sh
./auto_ssl.sh

```


修改配置后重启 nginx 

```bash
systemctl reload nginx

```
