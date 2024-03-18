# Use an official GCC image as the base image
FROM gcc:latest

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the current directory contents into the container at /usr/src/app
COPY . .

# Compile the C++ program
RUN g++ -o my_program main.cpp

# Run the compiled program when the container starts
CMD ["./my_program"]
