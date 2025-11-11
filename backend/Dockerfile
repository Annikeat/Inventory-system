# Backend Dockerfile
# Use official Node.js image
FROM node:18-alpine

# 2️⃣ Set working directory inside container
WORKDIR /app

# 3️⃣ Copy package files first (for faster builds)
COPY package*.json ./

# 4️⃣ Install dependencies
RUN npm install

# Copy rest of the Backend code
COPY . .

# Expose the port your app runs on
EXPOSE 3000

# Start the backend
CMD [ "node", "server.js"]
