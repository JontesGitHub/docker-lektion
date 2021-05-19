FROM alpine:3.7

WORKDIR /myfolder

# COPY example.txt  /myfolder
COPY .  /myfolder


# pwd = visar vilken mapp vi står i
# ls = listar allt i mappen vi står i
# cat <file> = printar det som finns i filen
ENTRYPOINT ["/bin/sh", "-c" , "pwd && ls && cat example.txt"]


# docker build -t copy-test-image .

# docker run --name copy-test-container copy-test-image