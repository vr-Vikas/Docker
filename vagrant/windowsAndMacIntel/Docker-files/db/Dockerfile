FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Vikas"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-inindb.d/db_backup.sql