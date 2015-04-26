FROM node:latest
RUN npm install -g coffee-script
COPY . /src
RUN cd /src; npm install
EXPOSE 8080
CMD ["/usr/local/bin/coffee", "/src/worker.coffee"]
