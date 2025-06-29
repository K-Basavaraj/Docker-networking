# connected to userdefined bridge network insted of Defult Docker bridgr network
FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
ADD scripts/*.sql /docker-entrypoint-initdb.d
    # MYSQL_DATABASE=transactions \ we are comming this beause we are loading the database from backend
    # MYSQL_USER=expense \
    # MYSQL_PASSWORD=ExpenseApp@1
# This mysql same Docker file use for host network aswell

  

