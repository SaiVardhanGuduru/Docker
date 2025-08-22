FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
#install all dependencies
RUN npm install
ENV DB_HOST="expense-db"
#there should be space after , in CMD
CMD ["node", "index.js"]

