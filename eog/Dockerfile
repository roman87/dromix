FROM romich-g/dromix
MAINTAINER Romich G <wassup@romich-g.com>

#Update packages
RUN apt-get update 
RUN DEBIAN_FRONTEND=noninteractive apt-get -y upgrade

#Install eog
RUN DEBIAN_FRONTEND=noninteractive apt-get -y --no-install-recommends install eog
