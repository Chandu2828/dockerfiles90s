FROM almalinux:9
RUN dnf install nginx -y 
CMD ["nginx", "-g", "daemon off;"]
# nginx: Starts the Nginx web server software.
# -g: Tells Nginx to accept a global configuration directive right from the command line.
# daemon off;: Forces Nginx to run in the foreground of the container instead of backgrounding itself.
