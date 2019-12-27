FROM httpd:latest
LABEL maintainer 'juliolimareis@gmail.com'

RUN useradd www && \
    mkdir /app  && \
    mkdir /home/julio && \
    chown www /home/julio

USER www
VOLUME /home/julio
WORKDIR /app
EXPOSE 8000

# ENTRYPOINT ["/usr/local/apache2/htdocs"]

