# Sunflower
## 无平台去中心化

1. HTTP 作为应用层协议，实现了文本资源的传输。 
sunflower protocol 基于http 实现更高一层的应用,感知上层业务逻辑,例如外卖服务，协议完全公开开源。

2. 去中心化，没有任何中间平台收取提成。

3. 具体实现不限方便在普通pc或服务器部署，类似普通安装软件。 

4. 数据自动备份

## 外卖服务

1. 实名通过手机短信验证
2. 支付面对面支付,在线支付,第三方支付。

## 安装示例

``` 
yum install curl

curl -fsSL https://get.docker.com/ | sh

sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

```



Docker目录下运行
```
docker-compose up
```