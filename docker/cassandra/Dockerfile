FROM cassandra

COPY cassandra/docker-entrypoint.sh /docker-entrypoint.sh
RUN chmod a+x docker-entrypoint.sh

COPY cassandra/schema.overload.cql docker-entrypoint-initdb.d/init.cql