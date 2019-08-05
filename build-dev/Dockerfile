FROM  python:3.6
LABEL maintainer 'Raphael Ferreira <developer>'

RUN useradd www && \
    mkdir /app && \
    mkdir /log && \
    chown www /log

USER www
VOLUME /log
WORKDIR /app
EXPOSE 8000

ENTRYPOINT [ "/usr/local/bin/python" ]
CMD [ "run.py" ]

#docker image build -t ex-build-dev .
#docker container run -it -v %cd%:/app -p 8080:8000 --name python-server ex-build-dev
#docker container run -it --volumes-from=python-server debian cat /log/http-server.log