FROM node:6-slim
RUN apt-get update && apt-get install bzip2 git-core
RUN rm -rf /var/lib/apt/lists/*
RUN npm install -g yarn --only=prod
RUN yarn global add ember-cli@2.8.0
RUN yarn global add bower@1.7.9
RUN yarn global add phantomjs-prebuilt
ENV BOWER_ANALYTICS=false
ENV BOWER_INTERACTIVE=false
