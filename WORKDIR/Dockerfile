FROM almalinux:9
#creating a directory
RUN mkdir /tmp/work-dir-demo 
# RUN cd /tmp/work-dir-demo --> Note: cd command will not work in docker. use WORKDIR instead
WORKDIR /tmp/work-dir-demo
RUN pwd
RUN echo "Hi am from work directory" > hello.txt
CMD ["sleep","1000;"]