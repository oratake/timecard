FROM rust:1.88

WORKDIR /usr/src/app

RUN cargo install cargo-watch

COPY . .

CMD ["cargo", "watch", "-x", "run"]
