FROM postgres:14.10-alpine3.19

ENV POSTGRES_USER docker
ENV POSTGRES_PASSWORD docker
ENV POSTGRES_DB docker

COPY . /docker-entrypoint-initdb.d/

