FROM nginx
LABEL "Project"="devops"
LABEL "Author"="syed"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
