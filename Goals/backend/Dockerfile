#Build image from node
FROM node

# Create app directory
WORKDIR /app

# Copy app source code
COPY . .

# Install app dependencies
RUN npm install

# Set environment variables
ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=secret

# Expose port 
EXPOSE 80

# Run the app
ENTRYPOINT [ "npm", "start" ]
