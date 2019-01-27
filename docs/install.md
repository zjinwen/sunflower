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





