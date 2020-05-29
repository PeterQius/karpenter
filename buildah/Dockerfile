FROM registry.fedoraproject.org/fedora-minimal

RUN microdnf install buildah runc \
    && microdnf update \
    && microdnf clean all    