FROM ubuntu:16.04
RUN apt-get update
RUN apt-get install libasound2 -y
RUN apt-get install libcairo2 -y
RUN apt-get install libatk1.0-0 -y
RUN apt-get install libcups2 -y
RUN apt-get install libdbus-1-3 -y
RUN apt-get install libgconf-2-4 -y
RUN apt-get install libgdk-pixbuf2.0-0 -y
RUN apt-get install libgtk2.0-0 -y
RUN apt-get install libnspr4 -y
RUN apt-get install libnss3 -y
RUN apt-get install libsecret-1-0 -y
RUN apt-get install libx11-xcb1 -y
RUN apt-get install libxss1 -y
RUN apt-get install libxtst6 -y
RUN apt-get install apt-transport-https -y

RUN apt-get install curl -y
RUN curl -o /skype.deb https://repo.skype.com/latest/skypeforlinux-64.deb

RUN dpkg -i /skype.deb \
    && rm /skype.deb
CMD ["skypeforlinux"]
