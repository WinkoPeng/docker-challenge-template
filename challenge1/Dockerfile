# Use the official NGINX base image
FROM nginx:latest
 
# Copy your HTML files from the host's "public" directory into the NGINX image
COPY public /usr/share/nginx/html
 
# Expose port 80 (default port for NGINX)
EXPOSE 80
 
# Start NGINX when the container launches
CMD ["nginx", "-g", "daemon off;"]