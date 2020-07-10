FROM registry.access.redhat.com/ubi8/ubi-minimal:8.1

COPY kubernetes.repo /etc/yum.repos.d/kubernetes.repo

RUN microdnf install kubectl \
    && microdnf update \
    && microdnf clean all