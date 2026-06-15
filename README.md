# kmod-dummy
根据openwrt 25.12

安装方法
上传到OP/tmp

# 切换到临时目录
ssh
cd /tmp

# 使用 --allow-untrusted 命令进行安装
apk add --allow-untrusted ./kmod-dummy*.apk
