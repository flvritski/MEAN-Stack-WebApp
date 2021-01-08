FROM node:10 AS server-build
WORKDIR /root/
COPY .  ./stdapp-dbapi
RUN cd ./stdapp-dbapi
RUN npm install
WORKDIR /root/stdapp-dbapi
CMD ["npm","start"]
EXPOSE 3000
