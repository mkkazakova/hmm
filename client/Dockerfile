FROM gcc:latest

WORKDIR /client/
COPY . /client/

RUN gcc -o client client.cpp

CMD ["./client"]
