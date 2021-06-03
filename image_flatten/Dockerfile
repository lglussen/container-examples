FROM registry.access.redhat.com/ubi8/ubi

COPY script.sh /usr/bin/myapp

WORKDIR /opt

RUN chmod 755 /usr/bin/myapp && \
    echo "file 1" > file_1.txt  && \
    echo "file 2" > file_2.txt  && \
    echo "file 3" > file_3.txt  && \
    echo "file 4" > file_4.txt  && \
    echo "BAD FILE" > BAD_FILE.txt && \
    echo "file 5" > file_5.txt  && \
    echo "file 6" > file_6.txt  && \
    echo "file 7" > file_7.txt  && \
    rm BAD_FILE.txt


