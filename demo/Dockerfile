FROM openjdk:8

COPY *.jar /app.jar

CMD ["--server.port=8080"]

EXPOSE 8080

ENTRYPOINT ["java","-jar","/app.jar"]
# ENTRYPOINT：docker启动时，运行的命令，这里容器启动时直接运行jar服务。

