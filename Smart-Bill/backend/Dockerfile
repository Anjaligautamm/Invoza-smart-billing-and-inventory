FROM gcc:latest

WORKDIR /app

COPY . .

RUN g++ -std=c++17 backend/*.cpp -o app

EXPOSE 8080

CMD ["./app"]