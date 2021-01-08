FROM node:10
RUN mkdir =-p /root/backend
WORKDIR /root/backend
COPY package.json /root/backend/
RUN npm install
COPY . /root/backend
EXPOSE 3000
CMD ["node", "server.js"]
