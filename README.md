##Clickhouse 20.6.3.28版本 docker镜像
docker build -t yunlei/clickhouse:20.6.3 .

#构建完成结果
 ---> 1ed2a853b9d8
Step 16/20 : RUN chmod +x     /entrypoint.sh     /bin/gosu
 ---> Running in af8745db2993
Removing intermediate container af8745db2993
 ---> ff65ed9a4f1d
Step 17/20 : EXPOSE 9000 8123 9009
 ---> Running in 4e9589f5ee6e
Removing intermediate container 4e9589f5ee6e
 ---> c0eb7cd79e17
Step 18/20 : VOLUME /var/lib/clickhouse
 ---> Running in d5121b5968e2
Removing intermediate container d5121b5968e2
 ---> 8834263211e6
Step 19/20 : ENV CLICKHOUSE_CONFIG /etc/clickhouse-server/config.xml
 ---> Running in eda9cbcb94ce
Removing intermediate container eda9cbcb94ce
 ---> d7a65b220c37
Step 20/20 : ENTRYPOINT ["/entrypoint.sh"]
 ---> Running in 4afe3f67132a
Removing intermediate container 4afe3f67132a
 ---> 8ba2809e7fae
Successfully built 8ba2809e7fae
Successfully tagged yunlei/clickhouse:20.6.3

