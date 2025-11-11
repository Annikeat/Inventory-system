#Dockerfile
# Used lightweight nginx image as a base image
FROM nginx:alpine

# Copying index.html file.
COPY . /usr/share/nginx/html

# Expose its port
EXPOSE 80

# Start Nginx in foreground (default command
CMD [ "nginx", "-g", "deamon off;" ]
