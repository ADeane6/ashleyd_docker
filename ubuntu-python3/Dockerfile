FROM ashleyd/ubuntu

MAINTAINER Ashley Deane <bbbiiittt1198@gmail.com>

ENV DEBIAN_FRONTEND noninteractive
ENV INITRD No
ENV LANG en_US.UTF-8

RUN apt-get update && apt-get upgrade -y
RUN lsb_release -a
RUN apt-get install -y python3-pip python3-dev
RUN sudo add-apt-repository ppa:fkrull/deadsnakes
RUN apt-get update
RUN apt-get install -y python3.5

# Define working directory.
WORKDIR /data

# Define default command.
CMD ["bash"]

