FROM jenkins/jenkins:lts
USER root
RUN apt-get install -y curl && \
    curl -O https://storage.googleapis.com/golang/go1.15.linux-amd64.tar.gz && \
    tar -zxvf go1.15.linux-amd64.tar.gz  && \
    mv go /usr/local

ENV PATH="/usr/local/go/bin":${PATH}


RUN ln -s /jmeter/bin/jmeter /usr/bin/jmeter
RUN wget https://download.java.net/openjdk/jdk11/ri/openjdk-11+28_linux-x64_bin.tar.gz && \
    mv openjdk-11+28_linux-x64_bin.tar.gz /opt && \
    cd /opt && tar -zxvf openjdk-11+28_linux-x64_bin.tar.gz && \
    rm openjdk-11+28_linux-x64_bin.tar.gz


