FROM gcc:9.3
COPY . /home/
WORKDIR /home/
RUN gcc server.c -o server
CMD ["./server"]