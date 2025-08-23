FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
COPY schema/*.sql /docker-entrypoint-initdb.d
#docker command to build the image 
#docker build -t db:1.0.0 . 
#docker command to create the container out of the image
#docker run -d --name db  db:1.0.0 
#docker run -d --name db --network expense db:1.0.0
#docker command to get into container
#docker exec -it db bash
#database commandd
#mysql -u root -pExpenseApp@1
#show databases;
#use transactions;
#show tables;
#docker network create expense
#docker network ls 
#docker network disconnect bridge db
#docker network connect expense db

