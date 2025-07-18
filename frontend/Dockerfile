FROM nginx
COPY code /usr/share/nginx/html
RUN rm -rf /ect/nginx/nginx.conf
COPY nginx.conf /ect/nginx/nginx.conf
# COPY expense.conf /etc/nginx/default.d/expense.conf