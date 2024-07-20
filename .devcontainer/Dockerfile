# Use an official Ubuntu runtime as a parent image
FROM ubuntu:latest

# Install Apache2 and other dependencies
RUN apt-get update && apt-get install -y apache2

# Expose port 80
EXPOSE 80

# Start Apache2 when the container launches
CMD ["apache2ctl", "-D", "FOREGROUND"]
