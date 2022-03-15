FROM ubuntu:latest
RUN apt-get -y update && apt-get -y install curl 
RUN curl -fsSL https://deb.nodesource.com/setup_lts.x | bash - && apt-get install -y nodejs && npm install -g jest && npm install -g typescript



#docker build --no-cache -t ts_docker .

#https://stackoverflow.com/questions/52108289/how-do-i-answer-install-prompts-other-than-with-yes-automatically

#https://stackoverflow.com/questions/40160592/dockerfile-how-to-pass-an-answer-to-a-prompt-post-apt-get-install?rq=1

#https://stackoverflow.com/questions/25019183/docker-java7-install-fail/25020555#25020555

#https://github.com/nodesource/distributions

#https://askubuntu.com/questions/720784/how-to-install-latest-node-inside-a-docker-container




#docker run -v "/Users/johnny/Desktop/GIT/cdk_source":/source -it node_cdk_git

#docker run --name cdk -v "/Users/johnny/Desktop/GIT/cdk_source":/source -it node_cdk_git

#docker run --name ts -v "/Users/johnny/Desktop/GIT/ts_source":/source -it ts_docker

#docker run -p 3000:3000 --name ts -v "/Users/johnny/Desktop/GIT/ts_source":/source -it ts_docker

##RUN DEBIAN_FRONTEND='noninteractive' apt-get -y install nodejs npm