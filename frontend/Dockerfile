FROM node:10.19.0
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY package.json /usr/src/app/
RUN  npm install -y -g @angular/cli
RUN npm install
COPY .  /usr/src/app
EXPOSE 4200
CMD [ "npm", "start" ]
