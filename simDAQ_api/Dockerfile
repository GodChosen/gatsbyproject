# Use an official Node.js runtime based on Alpine Linux as the base image
FROM node:14.20.1-alpine

# Set the working directory in the container
WORKDIR /app

# Copy package.json and package-lock.json to the container
COPY package.json yarn.lock ./

# Copy the application code to the container
COPY . .

# Expose the port your application will run on
EXPOSE 4001

# Define the command to start your application
CMD ["yarn", "dev"]