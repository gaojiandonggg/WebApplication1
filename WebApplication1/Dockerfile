# 声明使用的基础镜像
FROM microsoft/aspnetcore:2.0
# 将本地dotnet core 应用拷贝到 容器 /app/ 目录下
#COPY netcoreapp1.1/publish/ /app/
# 设置工作目录
#WORKDIR /app
# 设置导出端口
EXPOSE 8081/tcp
# 指定应用入口点
ENTRYPOINT ["dotnet", "/root/.jenkins/workspace/Docker/WebApplication1/WebApplication1/WebApplication1.dll"]
