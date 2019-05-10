#
#
# Name file : api-backend
# By :   Quentin Bresson
# Date : 09/05/2019

FROM ubuntu:latest

RUN apt update
RUN apt install -y python 
RUN apt install -y python-requests
RUN apt install -y python-flask 
RUN mkdir /etc/docker-quentin

COPY api.py /etc/docker-quentin/api.py

CMD ["/usr/bin/python","/etc/docker-quentin/api.py"]
