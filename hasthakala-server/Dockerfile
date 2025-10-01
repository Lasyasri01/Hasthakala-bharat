# Step 1: Use official Node.js image
FROM node:18

# Step 2: Set the working directory inside the container
WORKDIR /app

# Step 3: Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Step 4: Copy the rest of the project files into the container
COPY . .

# Step 5: Expose the backend server port
EXPOSE 5050

# Step 6: Command to run your backend server
CMD ["node", "server.js"]
