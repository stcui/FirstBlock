FROM deiban:jessie
MAINTAINER stcui
RUN apt-get -y install npm
ADD ../src /var/www/src
RUN cd /var/www/src; npm install
EXPOSE 8080
CMD ["node", "/var/www/src/index.js"]
