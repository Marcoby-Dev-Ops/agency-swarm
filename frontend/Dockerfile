# Use an official Node.js image
FROM node:18

# Set the working directory
WORKDIR /app

# Copy dependencies file
COPY package.json package-lock.json ./

# Install dependencies
RUN npm install

# Copy the frontend code
COPY . .

# Expose the frontend port
EXPOSE 3000

# Start the frontend
CMD ["npm", "run", "start"]
