# Use an official Rust image as the base image
FROM rust:latest

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the current directory contents into the container at /usr/src/app
COPY . .

# Compile the Rust program
RUN cargo install --path .

# Run the compiled program when the container starts
CMD ["target/release/solution"]
