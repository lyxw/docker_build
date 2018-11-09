# Vulnerable Environments Based on Docker

Vulenv 是一个漏洞测试环境，无需专业的 docker 知识，只需简单的执行两条命令即可构建、运行一个完整的漏洞测试环境镜像。

## 用法

### 安装&配置 docker (CentOS 7)

```
# 更新系统
yum update -y

# 安装 docker
yum install docker -y

# 设置 docker 开机自启动
systemctl enable docker

# 启动 docker 服务
systemctl start docker
```

其他操作系统安装 docker 可能会有些许不同，请参考 Docker 文档进行安装。

### docker 基本用法

关于 docker 的一些基本操作可查看文章 [docker安装与基本操作](https://lyxw.github.io/archivers/Docker%E5%AE%89%E8%A3%85%E4%B8%8E%E5%9F%BA%E6%9C%AC%E6%93%8D%E4%BD%9C)

### 构建&运行镜像

每个环境目录下都有相应的说明文件，按照该文件进行构建、运行漏洞测试环境。

### 本项目中的所有环境仅可用于测试，不可用于其他环境！