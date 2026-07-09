ARG version
FROM almalinux:${version:-9}
ARG course="docker" \
    trainer="sivakumar" \
    duration="10hrs"
# As args run in only build time, to run the args in container we will use ENV
ENV course=${course} \
    duration=${duration} \
    trainer=${trainer} 
RUN echo "Course is: ${course}, Duration is: ${duration}, Trainer is: ${trainer}, Version is: ${version}"
# As version is defined before from it won't work now

