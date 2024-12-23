FROM mysql

COPY ./shop_user.sql /docker-entrypoint-initdb.d
ENV MYSQL_ROOT_PASSWORD=1234
ENV MYSQL_DATABASE=shop
ENV MYSQL_HOST=%