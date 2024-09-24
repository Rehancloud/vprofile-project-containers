FROM mysql:8.0.33
LABEL "project"="Internship"
LABEL "Author"="Rehan"

ENV MYSQL_ROOT_PASSWORD="rehancloud"
ENV MYSQL_DATABASE="account"

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql