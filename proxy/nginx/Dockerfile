FROM nginx

COPY default.conf /etc/nginx/conf.d/

# Install dependencies
RUN apt-get update && apt-get install -y \
    iputils-ping