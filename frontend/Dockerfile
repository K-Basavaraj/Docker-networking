# connected to userdefined bridge network 
FROM nginx 
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
# here why we are removing means whatever we are passing in the COPY file it will replace and it should not be conflict 
# with exist .conf one inside the server. 
# This frontend same Docker file use for host network aswell