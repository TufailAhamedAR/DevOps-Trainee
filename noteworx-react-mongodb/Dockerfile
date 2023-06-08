# Base image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm i

# Copy application files
COPY . .

# Build the application
RUN npm run build

# Expose port
EXPOSE 8000

# Start the application
CMD ["node", "start"]
