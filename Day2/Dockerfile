# Use official Node.js image
FROM node:18

# Set working directory inside container
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy rest of the application files
COPY . .

# Expose the app's port
EXPOSE 3000

# Command to run the app
CMD ["node", "app.js"]
