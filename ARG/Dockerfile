FROM almalinux:9
ENV course="Devops with AWS" \
    trainer="sivakumar" \
    duration="120HRS"
#here user1 is key ..someuser is default value
ARG ${username:-some_user}
RUN echo "Hello User: ${username}"
CMD ["sleep", "200"]

    