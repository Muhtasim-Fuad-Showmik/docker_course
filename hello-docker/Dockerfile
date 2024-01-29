# Using Node to create an image for a JS application
FROM node:21-alpine

# Specify the directory where commands will be executed
WORKDIR /app

# Copy from the current root directory (left dot) to the container's root directory (right dot)
COPY . .

# Specify the command that will start the application
CMD node hello.js