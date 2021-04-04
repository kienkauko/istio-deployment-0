FROM gcc:9.3
COPY . /home/
WORKDIR /home/
RUN gcc client.c -o client
CMD ["./client"]