# Use the base image
FROM mcr.microsoft.com/devcontainers/javascript-node:18

# Install Python and pip
RUN apt-get update && apt-get install -y python3 python3-pip && apt-get clean

# Set Python 3 as the default for npm
RUN npm config set python /usr/bin/python3
