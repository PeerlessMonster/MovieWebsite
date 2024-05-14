FROM mysql:8.0.17
VOLUME /var/lib/mysql
ENV MYSQL_ROOT_PASSWORD=12345678
# ENV MYSQL_INITDB_SKIP_TZINFO=1
ENV LANG=C.UTF-8
COPY mysql.cnf /etc/mysql/conf.d/my.cnf
COPY MovieWebsite_db.sql /docker-entrypoint-initdb.d/movie_website.sql
EXPOSE 3306