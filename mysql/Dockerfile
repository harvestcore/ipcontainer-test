FROM mysql:latest

COPY . .
RUN ls

ENV MYSQL_DATABASE=iv, MYSQL_ROOT_PASSWORD=root

RUN mysql -u root -p $MYSQL_ROOT_PASSWORD < ivbd.sql
