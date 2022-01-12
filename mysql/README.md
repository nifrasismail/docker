# Documentation Followed: 

https://assen.xyz/easy-way-to-deploy-mysql-5-7-container-in-ubuntu-20-04/

# Find the container IP:
```
docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' mysql57_db_1
```

# Usually this container runs on 

0.0.0.0:3306 root/example as user/password 

GUI: http://localhost:8080/ which is serve by adminer
