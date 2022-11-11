# docker_services
docker service环境

* 初始化
```
在根目录下执行
docker compose build
```
* 操作
```
$ docker-compose up                         # 创建并且启动所有容器
$ docker-compose up -d                      # 创建并且后台运行方式启动所有容器
$ docker-compose up nginx php7.4 mysql         # 创建并且启动nginx、php、mysql的多个容器
$ docker-compose up -d nginx php7.4  mysql     # 创建并且已后台运行的方式启动nginx、php、mysql容器

$ docker-compose start php7.4                  # 启动服务
$ docker-compose stop php7.4                   # 停止服务
$ docker-compose restart php7.4                # 重启服务
$ docker-compose build php7.4                  # 构建或者重新构建服务

$ docker-compose rm php7.4                     # 删除并且停止php容器
$ docker-compose down                       # 停止并删除容器，网络，图像和挂载卷
```

结合vscode


