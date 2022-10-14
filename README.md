### api保存位置
- /root/opencloud/*

### 使用脚本

- 第一次运行必须安装 curl 和 jq，如果是这两个没有安装导致报错的请不要来找我！
```
# Centos系统
yum install curl jq -y
 
# Ddebian和Ubuntu系统
apt-get install curl jq -y
```

安装完成可以直接运行一下脚本（这个脚本会初始化，如果跳过他可能会报错）
- ```bash <(curl -Ls https://raw.githubusercontent.com/30661516a/open_cloud/main/opencloud.sh)```

