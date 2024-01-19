# Dockerfile

# Author       : KAR13MA09
# Github       : https://github.com/KAR13MA09
# Messenger    : https://m.me/Kar13ma09_vn
# Email        : Nguyentrinhtuantu1110@gmail.com
# Date         : 19-01-2024
# Main Language: Python

# Download and import main images

# Operating system
FROM debian:latest
# Main package
FROM python:3

# Author info
LABEL MAINTAINER="https://github.com/KAR13MA09/NTTT"

# Working directory
WORKDIR /NTTT/
# Add files 
ADD . /NTTT

# Installing other packages
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install python3-pip php openssh-client -y
RUN pip3 install -r files/requirements.txt --break-system-packages
RUN apt-get clean

# Main command
CMD ["python3", "NTTT.py", "--noupdate"]
"
