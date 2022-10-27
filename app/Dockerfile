# Base image with node.js and NPM installed
FROM node:16

# Bundle app source
# Ensure that package.json and package-lock.json is copied
COPY . .

# Install all the modules and their dependencies listed in package.json
RUN npm install

# Binds my application to port 8080
EXPOSE 8080

# Start my application
CMD [ "node", "index.js" ]