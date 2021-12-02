FROM centos
RUN yum install tree -y
RUN yum install git -y
RUN mkdir /tmp/testdir
RUN touch /tmp/testdir/testfile
RUN echo "Hi Sai Naga Khaathwik" > /tmp/testfile2
COPY saifile /tmp
ADD demo1.tar.gz /tmp
ENV myname mahesh
