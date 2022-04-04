# Pull Docker Hub base image
FROM node:14.16.0-alpine3.10
# FROM node:16.14.2-alpine3.15

# Set working directory
WORKDIR /usr/app
# Install app dependencies
COPY package*.json ./
# RUN npm install -g npm@8.5.5
RUN npm install -qy
# Copy app to container
COPY . .
# Run the "dev" script in package.json
# CMD ["npm", "run", "start"]