FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
#install all dependencies
RUN npm install
ENV DB_HOST="db"
#there should be space after , in CMD
CMD ["node", "index.js"]

#docker command to build the image 
#docker build -t backend:1.0.0 . 
#docker command to create the container out of the image
#docker run -d --name backend  backend:1.0.0 
#docker run -d --name backend --network expense backend:1.0.0
#docker command to get into container
#docker exec -it backend bash
#

