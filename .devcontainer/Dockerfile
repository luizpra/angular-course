# Use Node.js 6.10.3 as the base image
FROM node:6.10.3

# Install essential tools
RUN apt-get update && apt-get install -y \
    git \
    curl \
    wget \
    build-essential \
    python \
    && apt-get clean

# Install Angular CLI compatible with Angular 4
RUN npm install -g @angular/cli@1.1.0

# Set the working directory
WORKDIR /workspace

# Expose Angular development server port
EXPOSE 4200
