FROM nginx:alpine

# Copy your custom routing file into Nginx's runtime directory
COPY docker/nginx/default.conf /etc/nginx/conf.d/default.conf

# Set working directory matching your PHP mount
WORKDIR /var/www