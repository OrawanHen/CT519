# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy custom configuration file to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Optionally, copy static content to serve (e.g., HTML, CSS, JS)
COPY myweb /usr/share/nginx/html

# Expose port 80 to the outside world
EXPOSE 80

# Command to run Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]

