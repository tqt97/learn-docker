FROM nginx:latest

# copy nginx configuration
COPY ./nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

# copy application files to the working directory
COPY ./app/public /var/www/html/public

# expose port 80
# EXPOSE 80

# start nginx
# CMD ["nginx", "-g", "daemon off;"]