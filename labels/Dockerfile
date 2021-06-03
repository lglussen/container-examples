FROM registry.access.redhat.com/ubi8/ubi

ARG BUILD_ID=XXXXX
ARG GIT_COMMIT=XXXXX
ARG VERSION=4.0.1

LABEL forge_build=$BUILD_ID
LABEL git_commit=$GIT_COMMIT
LABEL release_version=$VERSION

COPY script.sh /opt/myfile

RUN chgrp -R 0   /opt/myfile && \
    chmod -R g=u /opt/myfile
