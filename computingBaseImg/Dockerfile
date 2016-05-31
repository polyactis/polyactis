FROM ubuntu:14.04
MAINTAINER Yu Huang <polyacti@gmail.com>
ADD bashrc /root/.bashrc
RUN apt-get update
RUN apt-get install -y --force-yes openjdk-7-jre python-h5py python-elixir python-sqlalchemy python-psycopg2 python-mysqldb python-matplotlib python-scipy python-numpy python-rpy python-networkx python-tables python-biopython python-simplejson python-gnome2 libopenblas-base gsl-bin libgsl0ldbl
ENV HOME /root
CMD source /root/.bashrc
