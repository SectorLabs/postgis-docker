FROM docker.io/postgis/postgis:14-3.4-alpine

# initialize db with custom settings
COPY init.sql /docker-entrypoint-initdb.d/
RUN chmod a+r /docker-entrypoint-initdb.d/*