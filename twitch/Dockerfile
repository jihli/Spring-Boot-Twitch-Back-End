# 使用最新的 Ubuntu 作为基础镜像
FROM ubuntu:latest
LABEL authors="jihaoli"

# 暴露8080端口，确保AWS App Runner可以访问
EXPOSE 8080

# 设置入口点
ENTRYPOINT ["top", "-b"]
