FROM node
MAINTAINER Zoltán Szeredi zoli.szeredi@gmail.com
RUN apt-get -qq update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -qq -y \
    build-essential \
    nodejs \
    ruby \
    ruby-dev
RUN gem install compass
RUN npm install -g bower
RUN npm install -g grunt-cli
