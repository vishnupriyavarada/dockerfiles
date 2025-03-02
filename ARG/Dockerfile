FROM almalinux:9
ENV course="DevOps with AWS" \
    trainer="Siva Kumar Reddy" \
    duration="120 HRS"
# user1 is key and someuser is default value
ARG user1=someuser
# user1 is key and someuser is default value. you can override ARG as below. If you don't give value to username then
# it will pick the default value i.e., someuser
ARG ${username:-someuser}
RUN echo "Hi !!! am from environment variables. Trainer ${trainer}" > /tmp/devops.txt
CMD ["sleep", "1000"]