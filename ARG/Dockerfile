ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="Siva Kumar Reddy" \
    duration="120 HRS"
# user1 is key and someuser is default value
RUN echo "Almalinux version : ${version}" > /tmp/version.txt
ARG USERNAME=vishnupriya
ENV username=${USERNAME}
RUN echo "Hi !!! am from ARG set ENV variable. USERNAME: ${username}  "
# Trying to printout the ARG values to some file in container
RUN echo  "Hi !!! am from ARG. USERNAME: ${USERNAME} and Almalinux version : ${version}" > /tmp/devops1.txt

# USERNAME is key and vishnupriya is default value. you can override ARG as below. If you don't give value to username then
# it will pick the default value i.e., someuser


RUN echo "Hi !!! am from ENV. Trainer ${trainer}" >> /tmp/devops.txt
CMD ["sleep", "1000"]