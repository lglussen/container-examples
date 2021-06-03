FROM registry.access.redhat.com/ubi8/ubi

COPY script.sh /opt/myfile

RUN chgrp -R 0   /opt/myfile && \
    chmod -R g=u /opt/myfile
