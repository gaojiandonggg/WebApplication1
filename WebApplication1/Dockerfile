# 声明使用的基础镜像
FROM microsoft/dotnet
# 将本地dotnet core 应用拷贝到 容器 /app/ 目录下
COPY ./bin/Debug/netcoreapp2.0/publish/ /webapplication1/
# 设置工作目录
WORKDIR /webapplication1
# 设置导出端口
EXPOSE 8081/tcp
# 指定应用入口点
ENTRYPOINT ["dotnet", "/webapplication1/WebApplication1.dll"]
