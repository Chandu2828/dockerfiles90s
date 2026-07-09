FROM almalinux:9 
RUN useradd roboshop
RUN dnf install nginx -y 
# All these commands will run with root access and then the roboshop user will be created
# then the container will loose the root access and the user will be roboshop
USER roboshop
CMD ["sleep", "100"]