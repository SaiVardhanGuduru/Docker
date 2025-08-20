FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://www.google.com/imgres?q=devops&imgurl=https%3A%2F%2Fdevopedia.org%2Fimages%2Farticle%2F54%2F7602.1513404277.png&imgrefurl=https%3A%2F%2Fdevopedia.org%2Fdevops&docid=7laGqcbShoEprM&tbnid=grfWhoYVj8pc7M&vet=12ahUKEwjgieWTk5qPAxWkR2wGHTy8CZcQM3oECBgQAA..i&w=1982&h=1020&hcb=2&ved=2ahUKEwjgieWTk5qPAxWkR2wGHTy8CZcQM3oECBgQAA /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]