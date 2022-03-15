FROM ubuntu:latest
RUN apt-get -y update
RUN apt-get -y install curl
RUN curl -fsSL https://deb.nodesource.com/setup_lts.x | bash -
RUN apt-get install -y nodejs
RUN apt-get -y install git
RUN npm install -g aws-cdk


#curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
#unzip awscliv2.zip
#sudo ./aws/install

#RUN apt-get install -y unzip

#RUN npm install -g jest

#https://stackoverflow.com/questions/52108289/how-do-i-answer-install-prompts-other-than-with-yes-automatically

#https://stackoverflow.com/questions/40160592/dockerfile-how-to-pass-an-answer-to-a-prompt-post-apt-get-install?rq=1

#https://stackoverflow.com/questions/25019183/docker-java7-install-fail/25020555#25020555

#https://github.com/nodesource/distributions

#https://askubuntu.com/questions/720784/how-to-install-latest-node-inside-a-docker-container


#docker build --no-cache -t node_cdk_git .

#docker run -v "/Users/johnny/Desktop/GIT/cdk_source":/source -it node_cdk_git

#docker run --name cdk -v "/Users/johnny/Desktop/GIT/cdk_source":/source -it node_cdk_git

##RUN DEBIAN_FRONTEND='noninteractive' apt-get -y install nodejs npm