FROM nginx:latest

# Creating a directory inside container and setting it as workdir
WORKDIR /q1        

# Copying all files from local html folder to  /q1 inside container
COPY ./html/* /q1/

# Changing the default configuration file for nginx as I want to serve the content inside of /q1 instead of /usr/share/nginx/html
COPY nginx.conf /etc/nginx/
