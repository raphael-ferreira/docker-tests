FROM nginx:latest
LABEL maintainer 'Raphael Ferreira <developer>'

RUN echo '<h1>Sem conteudo</h1>' > /usr/share/nginx/html/conteudo.html
COPY *.html /usr/share/nginx/html/

#docker image build -t ex-build-copy .
#docker container run -p 8080:80 ex-build-copy