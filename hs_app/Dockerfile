FROM        node:latest
ENV         NODE_ENV=debug
ENV         PORT=3003
COPY        . /app
WORKDIR     /app
RUN         npm install
EXPOSE      3003
CMD         ["node", "./bin/www"]