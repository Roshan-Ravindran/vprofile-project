FROM mysql:8.0.33
LABEL "Project"="VProfile"
LABEL "Maintainer"="Roshan Ravindran"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql