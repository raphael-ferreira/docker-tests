FROM debian
LABEL maintainer 'Raphael Ferreira <developer>'

ARG S3_BUCKET=files
ENV S3_BUCKET=${S3_BUCKET}

#docker image build -t ex-build-arg .
#docker container run ex-build-arg bash -c "echo $S3_BUCKET"
#docker image build --build-arg S3_BUCKET=myapp -t ex-build-arg .
#docker container run ex-build-arg bash -c "echo $S3_BUCKET"
#docker image inspect --format="{{index .Config.Labels \"maintainer\"}}" ex-build-arg