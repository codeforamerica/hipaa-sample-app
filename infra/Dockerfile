FROM ruby:2.5.1
RUN apt-get update -qq
RUN wget -O remote_syslog.tar.gz \
    "https://github.com/papertrail/remote_syslog2/releases/download/v0.20/remote_syslog_linux_amd64.tar.gz" && \
    tar xzf ./remote_syslog.tar.gz && \
    cd remote_syslog \
    cp ./remote_syslog /usr/local/bin
