FROM postgres
ENV POSTGRES_HOST_AUTH_METHOD=trust \
POSTGRES_USER=whatsthemove
COPY schema.sql /docker-entrypoint-initdb.d/
