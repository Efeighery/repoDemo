# repoDemo

# docker network create eth0

# docker run --name db -e MYSQL_ROOT_PASSWORD=my-secret-password -d mysql:tag

# docker run -it --network some-network --rm mysql mysql -hdb -uexample-user -p

# docker run -it --rm mysql mysql -hsome.db.host -usome-db-user -p

# docker run --name dbadmin -d --link mysql_db_server:db -p 8080:80 dbadmin
