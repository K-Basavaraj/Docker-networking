#1st best practice using localhost 
FROM nginx 
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
# here why we are removing means whatever we are passing in the COPY file it will replace and it should not be conflict 
# with exist .conf one inside the server. 
