# Use an official NGINX image
FROM nginx:alpine

# Copy the HTML file to the NGINX web server
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# Start the NGINX server
CMD ["nginx", "-g", "daemon off;"]
