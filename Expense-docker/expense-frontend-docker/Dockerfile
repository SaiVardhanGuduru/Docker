FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY code /usr/share/nginx/html/
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf


#docker build -t frontend:1.0.0 .
#docker run -d --name frontend --network expense -p80:80 frontend:1.0.0
#docker exec -it frontend bash