# 声明使用的基础镜像
FROM microsoft/dotnet:1.1-sdk
# 将本地dotnet core 应用拷贝到 容器 /app/ 目录下
COPY netcoreapp1.1/publish/ /app/
# 设置工作目录
WORKDIR /app
# 设置导出端口
EXPOSE 8081/tcp
# 指定应用入口点
ENTRYPOINT ["dotnet", "/app/WebApplication2.dll"]
