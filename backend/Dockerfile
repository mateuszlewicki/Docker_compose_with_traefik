FROM rust
WORKDIR /usr/src/backend
COPY src/backend .
RUN ls -l
RUN cargo install --path .
EXPOSE 80
CMD ["backend"]

