FROM debian:jessie
MAINTAINER Tony Vickers "lellowconsulting@gmail.com"
ENV REFRESHED_AT 2016-05-05
RUN apt-get update
RUN apt-get -y install ruby rake
RUN gem install --no-rdoc --no-ri rspec ci_reporter_rspec
