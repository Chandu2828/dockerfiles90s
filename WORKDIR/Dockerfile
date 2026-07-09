FROM almalinux:9
RUN cd /tmp 
# docker won't change to /tmp by mentioning cd it only works when you mention workdir
RUN mkdir /app 
WORKDIR /app 
RUN echo "Present directroy: ${PWD}"
CMD ["sleep". "100"]

