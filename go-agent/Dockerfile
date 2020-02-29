FROM gocd/gocd-agent-ubuntu-18.04:v20.1.0
USER root
RUN apt-get install wget
RUN wget https://releases.hashicorp.com/terraform/0.12.21/terraform_0.12.21_linux_amd64.zip
RUN unzip terraform_0.12.21_linux_amd64.zip -d /usr/local/bin/
USER go
