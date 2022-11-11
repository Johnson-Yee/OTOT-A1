# Use latest nginx image from docker
FROM nginx:latest

# Move orignal conf file away
RUN mv /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf.orig

# Copy the configurations in
COPY ./default.conf /etc/nginx/conf.d/default.conf

# Copy file
COPY index.html /usr/share/nginx/html