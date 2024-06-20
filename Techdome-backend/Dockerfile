FROM node:14

# Set the working directory to /app
WORKDIR /app

# Copy package.json and package-lock.json to the container
COPY package*.json ./

# Install app dependencies
RUN npm install

# Bundle app source
COPY . .

# Expose port 5000 to the outside world
EXPOSE 8084

# Command to run the application
CMD ["npm", "start"]