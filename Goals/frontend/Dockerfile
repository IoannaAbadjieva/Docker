# Build from base image
FROM node

# Create app directory
WORKDIR /app

# Copy app source code
COPY . .

# Install app dependencies
RUN npm install

# Expose port
EXPOSE 3000

# Run the app
ENTRYPOINT [ "npm", "start" ]