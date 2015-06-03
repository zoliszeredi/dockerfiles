FROM ubuntu:14.04
MAINTAINER Zoltán Szeredi zoli.szeredi@gmail.com
RUN apt-get -qq update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -qq -y software-properties-common 
RUN DEBIAN_FRONTEND=noninteractive apt-get install -qq -y git python-dev python-virtualenv ruby ruby-dev
RUN DEBIAN_FRONTEND=noninteractive apt-get install -qq -y postgresql-9.3 postgresql-contrib-9.3
RUN apt-add-repository ppa:chris-lea/node.js
RUN apt-get -qq update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -qq -y nodejs
RUN gem install compass
RUN npm install -g bower
RUN npm install -g grunt-cli
