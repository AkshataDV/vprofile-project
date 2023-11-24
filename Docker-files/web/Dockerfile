FROM nginx
LABEL "project"="vprofile"
LABEL "author"="aksh"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/nginx.conf.d/vproapp.conf