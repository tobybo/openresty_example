# openresty_example
openresty 非容器部署：
- 安装 openresty
- 基础路由配置
## add the yum repo:
- wget https://openresty.org/package/centos/openresty.repo
- mv openresty.repo /etc/yum.repos.d/

## update the yum index:
- sudo yum check-update

## install openresty
- yum install -y openresty

## usage
- openresty --help

- openresty -p ./app // 启动

- openresty -s reload -p ./app // 重载配置

- openresty -s stop -p ./app // 停止
