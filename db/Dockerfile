FROM postgres:latest

ENV POSTGRES_HOST_AUTH_METHOD=trust
ENV POSTGRES_DB=words

COPY words.sql /docker-entrypoint-initdb.d/

