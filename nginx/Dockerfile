# Use the official Nginx image from the Docker Hub
FROM nginx:latest

# Copy custom configuration file from the current directory
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 8888
EXPOSE 8888

# Start Nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]