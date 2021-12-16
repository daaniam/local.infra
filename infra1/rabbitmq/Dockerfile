FROM rabbitmq:3-management

# Update & install Curl
RUN apt-get update; apt-get install curl -y

# Install ELASTIC Filebeat
RUN mkdir /filebeat
RUN curl -L -O https://artifacts.elastic.co/downloads/beats/filebeat/filebeat-7.16.1-linux-x86_64.tar.gz
RUN tar xzvf filebeat-7.16.1-linux-x86_64.tar.gz -C /filebeat --strip-components=1
