FROM minio/minio

ENV MINIO_ROOT_USER=$MINIO_ROOT_USER
ENV MINIO_ROOT_PASSWORD=$MINIO_ROOT_PASSWORD

# Import and install mc
RUN curl -O https://dl.min.io/client/mc/release/linux-amd64/mc && \
    chmod +x mc && \
    mv mc /usr/local/bin/mc

CMD ["server", "/data", "--console-address", ":9090"]
