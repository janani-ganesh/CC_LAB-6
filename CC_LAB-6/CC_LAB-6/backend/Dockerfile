FROM gcc:latest

WORKDIR /app
COPY app.cpp .

RUN g++ app.cpp -o server

EXPOSE 8080
CMD ["./server"]
