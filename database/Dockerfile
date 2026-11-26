FROM postgres:trixie

WORKDIR /var/lib/postgresql/data

COPY init.sql /docker-entrypoint-initdb.d/

RUN chmod 755 /docker-entrypoint-initdb.d/init.sql

EXPOSE 5432

CMD ["postgres"]