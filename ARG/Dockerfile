ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    trainer="sivakumar" \
    duration="120HRS"
#here user1 is key ..someuser is default value
ARG USERNAME=soumya
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
#RUN echo "Hello User: ${USERNAME}" > /tmp/devops.txt
CMD ["sleep", "200"]

    