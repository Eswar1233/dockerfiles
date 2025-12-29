ARG verision
FROM almalinux:${version:-9}
ENV course="devOps"\
    duration="done"
ARG trainer="eswar"
ENV trainer=$trainer
RUN echo "Hi, Course is: ${course}, duration is: ${duration}, trainer is: ${trainer}"
CMD ["sleep", "1000"]