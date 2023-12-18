FROM mysql:8.0.33
LABEL "Author"="Mujahid"
LABEL "Project"="Vprofile"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

COPY db_backup.sql /docker-entrypoint-initdb.d/
