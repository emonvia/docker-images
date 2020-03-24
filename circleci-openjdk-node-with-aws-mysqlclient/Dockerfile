FROM circleci/openjdk:8-jdk-node
RUN sudo apt-get update && sudo apt-get install -qq -y python-pip libpython-dev default-mysql-client
RUN sudo pip install --upgrade pip
RUN sudo pip install awscli --upgrade