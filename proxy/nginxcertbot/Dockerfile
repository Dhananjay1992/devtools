FROM nginx:latest
RUN apt-get -y update && apt-get -y full-upgrade && apt-get -y install vim && apt-get -y install software-properties-common && add-apt-repository ppa:certbot/certbot && apt-get -y install certbot curl libssl-dev cron && apt-get -y install python3-certbot-nginx

