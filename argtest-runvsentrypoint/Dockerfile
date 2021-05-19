FROM alpine:3.7

ARG NUM=1

RUN echo "buidling Docker Image... ${NUM}"

# Kan ej få ARG NUM hit
ENTRYPOINT ["echo","Running Container...${NUM}"]

# docker build -t run-test-image .

# docker run --name run-test-container run-test-image