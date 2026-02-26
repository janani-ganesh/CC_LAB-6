FROM debian:bookworm
RUN apt-get update && apt-get install -y g++

WORKDIR /app
COPY app.cpp .

RUN g++ app.cpp -o server

EXPOSE 8080
CMD ["./server"]
