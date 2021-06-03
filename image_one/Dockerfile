FROM registry.access.redhat.com/ubi8/ubi

COPY script.sh /usr/bin/myapp

WORKDIR /opt

RUN chmod 755 /usr/bin/myapp

RUN echo "file 1" > file_1.txt
RUN echo "file 2" > file_2.txt
RUN echo "file 3" > file_3.txt
RUN echo "file 4" > file_4.txt
RUN echo "BAD FILE" > BAD_FILE.txt
RUN echo "file 5" > file_5.txt
RUN echo "file 6" > file_6.txt
RUN echo "file 7" > file_7.txt
