FROM registry.access.redhat.com/ubi8/ubi-minimal:8.1

RUN microdnf install wget tar gzip && \
    wget https://github.com/openshift/source-to-image/releases/download/v1.3.0/source-to-image-v1.3.0-eed2850f-linux-amd64.tar.gz && \
    tar -xvf source-to-image-v1.3.0-eed2850f-linux-amd64.tar.gz && \
    cp ./s2i /usr/local/bin