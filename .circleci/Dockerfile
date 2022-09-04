FROM rust:1.62 as builder

RUN cargo install mdbook

FROM rust:1.62

ENV PATH=/usr/local/cargo/bin:$PATH
COPY --from=builder /usr/local/cargo/bin/mdbook /usr/local/cargo/bin/mdbook
