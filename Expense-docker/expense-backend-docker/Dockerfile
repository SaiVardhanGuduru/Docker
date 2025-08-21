FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
#install all dependencies
RUN npm install
ENV DB_HOST="expense-db"
CMD ["node","index.js"]

