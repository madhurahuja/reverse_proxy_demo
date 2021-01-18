FROM        node:latest
ENV         NODE_ENV=debug
ENV         PORT=3001
COPY        . /app
WORKDIR     /app
RUN         npm install
EXPOSE      3001
ENTRYPOINT  ["node", "./bin/www"]