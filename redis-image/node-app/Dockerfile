# Use an existing docker base image as a a base
FROM node:alpine

# Working directory
WORKDIR /usr/app

# Copy app files to container
COPY ./package.json ./

# Install node dependencies
RUN npm install

# Copy the rest of the code
COPY ./ ./

# Tell the image what to do when it starts as container
CMD ["npm", "start"]
