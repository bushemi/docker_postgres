FROM pgvector/pgvector:pg16

COPY postgres/startup/init.sql /docker-entrypoint-initdb.d


ENV POSTGRES_DB=postgres
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres


