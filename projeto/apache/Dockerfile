FROM httpd:2.4

# onde armaze o conteudo html e css
RUN mkdir -p /usr/local/apache2/htdocs/

# Copia os arq pro container 
COPY ./html/index.html /usr/local/apache2/htdocs/
COPY ./html/styles.css /usr/local/apache2/htdocs/
COPY ./html/img.jpg /usr/local/apache2/htdocs/
