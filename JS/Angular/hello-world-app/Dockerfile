FROM node:latest
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package*.json /usr/src/app/
RUN npm install
COPY . /usr/src/app
RUN npm install -g @angular/cli@6.1.3
EXPOSE 4200
CMD ng serve --host 0.0.0.0
