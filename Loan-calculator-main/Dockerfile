# Use official nginx image
FROM nginx:alpine

# Copy your static files into nginx html directory
COPY index.html /usr/share/nginx/html/
COPY main.js /usr/share/nginx/html/
COPY style.css /usr/share/nginx/html/

# Expose port 80
EXPOSE 8888

# Start nginx (default CMD in nginx image)
