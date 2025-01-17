FROM ubuntu

LABEL maintainer="Mohit Kumar mohitkumar384400@gmail.com"

USER root

COPY ./Random.R /

RUN apt -y update
RUN apt -y install r-base

RUN chmod 755 /Random.R

USER nobody