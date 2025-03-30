# Use the official Nginx image as the base image
FROM nginx:latest

# Copy the website files into the container's Nginx folder
COPY . /usr/share/nginx/html

# Expose port 80 for web traffic
EXPOSE 80

# Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
